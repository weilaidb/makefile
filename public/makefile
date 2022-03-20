
-include "public.include"
#source "public.include"
include make2/jia.mk


all:
	@echo "done"

words:
	@echo $(words foo bar ha wo)
	@echo $(word $(words TEXT),TEXT)

current:
	@echo $(realpath ./)
	@echo $(shell pwd)
	@echo $$PWD
	@echo $(MAKEFILE_LIST);    
	@echo $(lastword $(MAKEFILE_LIST));
	@echo $(dir $(lastword $(MAKEFILE_LIST)));
	@echo $(realpath $(dir $(lastword $(MAKEFILE_LIST))));
	@echo $(shell pwd);
