# Making Assembler Notes:

## Native Code
* 命令プリフィックス		1Byte	//16ビット演算など特殊な時に使われる 
* オペコード              1-2Byte	//命令がかかれる
* ModR/M				1Byte	//レジスタ・メモリを参照する際のアドレッシングモード 
* SIB					1Byte	//レジスタ・メモリを参照する際のアドレッシングモード 
* ディスプレースメント    1-4Byte
* 即値                 1-Byte

