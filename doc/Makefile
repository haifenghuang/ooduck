.PHONY: all
all:
	@which doxygen >/dev/null 2>&1
	@(cd ../include/ooduck && doxygen ../../doc/Doxyfile)

.PHONY: clean
clean:
	@rm -rf html
