EMULDIR = ../emul

.PHONY: run
run:
	$(MAKE) -C $(EMULDIR) zasm/zasm zasm/avra runbin/runbin shell/shell
	cd unit && ./runtests.sh
	cd zasm && ./runtests.sh
	cd avra && ./runtests.sh
	cd shell && ./runtests.sh
