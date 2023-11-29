CC = /opt/riscv/bin/riscv64-unknown-elf-gcc
WHISPER = /whisper/build-Linux/whisper

build_origin_c:
	$(CC) sm3.c  -mabi=ilp32 -march=rv32imc -static -g -o sm3

build_origin_s:
	$(CC) sm3.s  -mabi=ilp32 -march=rv32imc -static -g -o sm3

build_opt:
	$(CC) sm3opt.s  -mabi=ilp32 -march=rv32imc -static -g -o sm3

build_opt1:
	$(CC) sm3opt_1.s  -mabi=ilp32 -march=rv32imc -static -g -o sm3

build_opt_2:
	$(CC) sm3opt_2.s  -mabi=ilp32 -march=rv32imc -static -g -o sm3

build_opt3:
	$(CC) sm3opt_3.s  -mabi=ilp32 -march=rv32imc -static -g -o sm3

test:
	$(WHISPER) sm3