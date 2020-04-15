# usage:

EXE = ~/git/github/rs_pbrt/target/release/rs_pbrt

all: usage

clean:
	-rm -f *~ *.png
	-rm -f bdpt_01.pbrt
	-rm -f bdpt_02.pbrt
	-rm -f bdpt_03.pbrt
	-rm -f bdpt_04.pbrt
	-rm -f bdpt_05.pbrt

usage:
	@echo "make clean"
	@echo "make bdpt_01"
	@echo "make bdpt_02"
	@echo "make bdpt_03"
	@echo "make bdpt_04"
	@echo "make bdpt_05"

bdpt_01: conference_room.pbrt bdpt_01.patch
	patch -i bdpt_01.patch -o bdpt_01.pbrt conference_room.pbrt
	$(EXE) bdpt_01.pbrt
	mv pbrt.png bdpt_01.png

bdpt_02: conference_room.pbrt bdpt_02.patch
	patch -i bdpt_02.patch -o bdpt_02.pbrt conference_room.pbrt
	$(EXE) bdpt_02.pbrt
	mv pbrt.png bdpt_02.png

bdpt_03: conference_room.pbrt bdpt_03.patch
	patch -i bdpt_03.patch -o bdpt_03.pbrt conference_room.pbrt
	$(EXE) bdpt_03.pbrt
	mv pbrt.png bdpt_03.png

bdpt_04: conference_room.pbrt bdpt_04.patch
	patch -i bdpt_04.patch -o bdpt_04.pbrt conference_room.pbrt
	$(EXE) bdpt_04.pbrt
	mv pbrt.png bdpt_04.png

bdpt_05: conference_room.pbrt bdpt_05.patch
	patch -i bdpt_05.patch -o bdpt_05.pbrt conference_room.pbrt
	$(EXE) bdpt_05.pbrt
	mv pbrt.png bdpt_05.png
