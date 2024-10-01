# How to make a operating system  
## Making a OS
You can make a Operating system in assembly. But first follow these steps. 
- Install NASM 
- Learn Assembly Programming Language 
- Make a bootloader in 16 BIT architecture 
- Create a kernel in Assembly 
- Make the OS interface (GUI, CLI, TUI) 
- Compile the code  
- Make a img file 
To compile the code use 
`nasm yourcode.asm`
To make a img file use 
`dd if=/dev/zero of=floppy.img bs=512 conv=notrunc` 
`dd if=yourcode.bin of=floppy.img conv=notrunc` 
And done! 
*Fun fact: This Markdown file was made with LKT v2.0.0 Download it at LKT repository* 
