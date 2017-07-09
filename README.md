# Hackaday_1K
This was a super simple project that I whipped up for a competition on hackaday.com.  The competition was all about getting as much functionality as possible in as small a space as possible, 1K of code was the limit (1024 bytes).  

All my project does is look for a capacitance (as far as I could tell it was hardware capacitive touch so I didn't have to use code space here) then outputs a digital high/low signal to a PIC microcontroller (PIC16F18855) to read.  I also had a 5V relay module that could be used for a variety of things (mostly motors would be the main application I see).  This could be polished into a really cheap capacitive touch switch.</br>

I used inline assembly but I didn't really gain anything because I think the compiler did a very similar thing.  It's pretty challenging to come up with something useful or exciting with a limited code space like that, I'm glad we're not limited to those sizes anymore!</br></br>

![1k_image](https://hackaday.io/project/19253/gallery#92803a7f2141e7b077ec8a4e32351b73)
