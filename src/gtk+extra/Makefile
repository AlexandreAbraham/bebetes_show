OBJS_GE=gtkplot.o gtkplotdata.o gtkplotcanvas.o gtkplotcanvasplot.o gtkplotcanvastext.o gtkplotcanvaspixmap.o gtkplotcanvasellipse.o gtkplotcanvasline.o gtkplotcanvasrectangle.o gtkpsfont.o gtkplotgdk.o gtkextra-marshal.o gtkplotpolar.o gtkplot3d.o gtkplotpc.o gtkplotarray.o gtkextra.o gtkplotps.o gtkplotsurface.o gtkplotdt.o gtkplotbar.o gtkplotprint.o

GTK_DEPS=`pkg-config --cflags --libs gtk+-2.0`
GLEXT_DEPS=`pkg-config --cflags --libs gtkglext-1.0`
GTK_DEPS2=`pkg-config --cflags gtk+-2.0`
GLEXT_DEPS2=`pkg-config --cflags gtkglext-1.0`

GCC=gcc

.c.o:
	$(GCC) ${GTK_DEPS2} ${GLEXT_DEPS2} -c $< -o $@ 
all: ${OBJS_GE}
