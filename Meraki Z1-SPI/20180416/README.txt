For Meraki Z1 with spi nor-flash use only.
Move the resistance R699 to R90 , sold a spi nor-flash and pull up CLK with a 10K resistance .

libc0607 replied：
LED 正常，Wi-Fi 正常
首先想办法备份原机 NAND Flash 内的内容，ART 在最后 128k 。
原机 ART 是 128k 的，新建一个 64k 的全是 0xff 的空文件，然后将原机 ART 的 0x1000+0x440 写到新文件的 0x1000 处， 再将原机 ART 的 0x15000+0xeb8 写到新文件的 0x5000 处（其实就是常见的 ART 结构）

https://github.com/libc0607/lede/commit/fd227f53c37740783fbf00f2040b222f496b8b7b