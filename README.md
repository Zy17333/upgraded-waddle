C-- Compiler

Linux GCC

>> Lexical Analysis: lexical.l
>> Parsing: syntax.y
>> Semantic Analysis: semantic folder (hash.c && semantic.c)
>> Generate Intercode: intercode folder (intercode.c && show.c)
>> Generate MIPS Codes: mipscode folder (functionField.c && mipscode.c)

running order: ./parser input_filename.c output_filename.asm
		
	input_filename.c is the test c source file
	output_filename.asm is the output file, it can be run on Qtspim

The whole Program is finished by ZY independently. Finishing date: 2018/1/13
Reference : CSDN Blof and Github.
