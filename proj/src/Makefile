PROG=proj

SRCS = proj.c display.c graphics.c keyboard.c mouse.c timer.c utils.c single_player.c multi_player.c rtc.c settings.c serial_port.c

# __LCOM_OPTIMIZED__ disables most of the LCF's overhead (and functionality!)
CPPFLAGS += -pedantic -D __LCOM_OPTIMIZED__

DPADD += ${LIBLCF}
LDADD += -llcf

.include <minix.lcom.mk>
