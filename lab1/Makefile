
call_shellcode: call_shellcode.c
	gcc -z execstack -o call_shellcode call_shellcode.c

exploit: exploit.c
	gcc exploit.c -o exploit

stack: stack.c
	 gcc -DBUF_SIZE=24 -o stack -z execstack -fno-stack-protector stack.c
