CXXFLAGS =	-O2 -g -Wall -fmessage-length=0

OBJS =		CompilerProject.o

LIBS =

TARGET =	CompilerProject

$(TARGET):	$(OBJS)
	$(CXX) -o $(TARGET) $(OBJS) $(LIBS)

all:	$(TARGET)

clean:
	rm -f $(OBJS) $(TARGET)
