For Meraki Z1 with spi nor-flash use only.
Move the resistance R699 to R90 , sold a spi nor-flash and pull up CLK with a 10K resistance .

libc0607 replied��
LED ������Wi-Fi ����
������취����ԭ�� NAND Flash �ڵ����ݣ�ART ����� 128k ��
ԭ�� ART �� 128k �ģ��½�һ�� 64k ��ȫ�� 0xff �Ŀ��ļ���Ȼ��ԭ�� ART �� 0x1000+0x440 д�����ļ��� 0x1000 ���� �ٽ�ԭ�� ART �� 0x15000+0xeb8 д�����ļ��� 0x5000 ������ʵ���ǳ����� ART �ṹ��

https://github.com/libc0607/lede/commit/fd227f53c37740783fbf00f2040b222f496b8b7b