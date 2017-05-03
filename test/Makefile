
src = $(wildcard *.c ./sub/*.c)
dir = $(notdir $(src))
obj = $(patsubst %.c,%.o,$(dir))
obj2 = $(dir:%.c=%.o)

all:
	@echo $(src)
	@echo $(dir)
	@echo $(obj)
	@echo $(obj2)
	@echo "end"

