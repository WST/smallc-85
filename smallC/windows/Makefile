all: build

FILES = \
  code8080.c \
  data.c \
  error.c \
  expr.c \
  function.c \
  gen.c \
  initialise.c \
  io.c \
  lex.c \
  main.c \
  preproc.c \
  primary.c \
  stmt.c \
  sym.c \
  while.c

build:
	cd .. && cl /Fewindows/cc8080.exe $(FILES)

clean:
	del *.obj *.exe
