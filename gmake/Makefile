# GNU Make solution makefile autogenerated by Premake
# Type "make help" for usage help

ifndef config
  config=release
endif
export config

PROJECTS := ResourceRW

.PHONY: all clean help $(PROJECTS)

all: $(PROJECTS)

ResourceRW: 
	@echo "==== Building ResourceRW ($(config)) ===="
	@${MAKE} --no-print-directory -C . -f ResourceRW.make

clean:
	@${MAKE} --no-print-directory -C . -f ResourceRW.make clean

help:
	@echo "Usage: make [config=name] [target]"
	@echo ""
	@echo "CONFIGURATIONS:"
	@echo "   release"
	@echo "   debug"
	@echo ""
	@echo "TARGETS:"
	@echo "   all (default)"
	@echo "   clean"
	@echo "   ResourceRW"
	@echo ""
	@echo "For more information, see http://industriousone.com/premake/quick-start"
