�ڿ��������ʱ���ȰѴ�ģ�鿽������Ӧ�Ĺ����ļ�����.
��дMAIN�ļ�,�������������C���Ժ���,����USER�ļ�����.

STM32λ����ַת����ʽ��	#define BITBAND(addr, bitnum) ((addr & 0xF0000000)+0x2000000+((addr &0xFFFFF)<<5)+(bitnum<<2))

����#define LED1 *((__O uint32_t *)(BITBAND((GPIOA_BASE+12), 0)))
