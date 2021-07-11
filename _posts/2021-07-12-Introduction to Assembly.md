---
title: Introduction to Assembly - bin0x01
tags: [Assembly Language]
style: 
color: 
description: Assembly Language is something that is required to further get into Reverse Engineering, Binary Exploitation and low level attacks like Buffer Overflow Attacks. So, getting a basic understanding of the basic concepts is always fruitful. In this blog, I will try the basics of how computer programs work and the rise of reverse engineering.
---

Source: [Img Alt](img link)

All these fascinating computers run only on the basis of 0s and 1s.
But, Have you ever wondered how a computer is able to recognize 'xyz' lines of codes programmers write in any programming languages?
This is a simple to say yet very complex to do process which we are going to look into in this article.

## How does a CPU run a parogram written in english or human readable form?
Computers(say Digital Computers) can only understand 0s and 1s or simply binary which we, as humans find difficult to do manually for large computations. So, We cannot just communicate to each other.
Have you even seen a human talking like '01001000011001010110110001101100011011110010000001010011011001010111100001111001'. Of Course Not!
Likewise, humans are french(Assume) and computers the chinese. Both of them donot know each others mother tongue. So, they cannot communicate. The only way of communication is through translation, A person or language 'x' comes in the middle who knows both the languages. It takes the data from one person, translates and provides to the another. Just like a real world human language translators.

So, Programs written in a programming language is actually converted into something the computer can understand 'machine code'.

To be specific, The code you write in human readable language(High Level language) like php, python, etc is first converted into a low level language code or assembly code with the help of translators like compiler of interpreter. Again the assembler converts the assembly code into a object file which contains the source code of the program.
Now, Linker links the object file with the library file present in the system and generates a machine code which is sent to the CPU. CPU again processes the given source code and performs the instruction by using the registers in the processor which are made up of flip flops(made up of logic gates which is the base of digital electronics)

# So, What is Linker and a library file?

