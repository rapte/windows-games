CXX=i586-mingw32msvc-g++

SOURCE=final.cpp

LIBS= \
	-L./../WinBGIm \
	-lbgi \
	-lcomdlg32 \
	-lgdi32 \
	-lole32 \
	-loleaut32 \
	-luuid \
	-lwinmm \

INCLUDE=-I./../WinBGIm

OUTPUT=final.exe

all:
	$(MAKE) --directory=../WinBGIm
	$(CXX) -o $(OUTPUT) $(SOURCE) $(LIBS) $(INCLUDE)

clean:
	$(MAKE) --directory=../WinBGIm clean
	rm $(OUTPUT)
