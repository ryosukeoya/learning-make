# hello: hello.o
# 	${CC} -o $@ $^

# .SUFFIXES: .c .o
# .c.o:
# 	${CC} ${CFLAGS} -c $<

aaa/bbb/foo:
	echo $@
	echo $(@D)
	echo $(@F)

output/foo: input/bar input/baz
	echo $?
	echo $(?D)
	echo $(?F)
