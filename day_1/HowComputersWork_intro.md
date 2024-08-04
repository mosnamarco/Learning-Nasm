# How does computers work?

In essence, computers work by executing the command programmers make, these commands come in the form of a computer program. These programs work by giving instructions to the computer via a programming language. There are 3 types of languages;

* Machine language: this is what the computer reads
* Assembly (what we are learning): an abstraction of the machine language making it more human readable. 
* High level languages: an even higher level abstraction of the language, designed to be more like natural languages. This makes creating programs easier.

## What is the kernel? 

The kernel acts as the gate and the fence of the computer

### The gate

Because kernels allow communication of the hardware to the actual application, they act as the gateways of data to flow from one program to another. For example, when typing, the hardware sends data that is then intercepted by the kernel and then sent to the application to be interpreted as a bunch of human readable characters.  

The process goes like this: Hardware -> Kernel -> OS -> Application.

Note that the Kernel is part of the Operating system, it's just the Operating System as a whole provides interaction to the application but the Kernel is the "manager" of hardware inputs that is then sent to the OS for use.

