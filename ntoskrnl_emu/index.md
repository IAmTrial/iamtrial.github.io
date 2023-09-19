# NTOSKRNL\_Emu Guide
A guide on how to use NTOSKRNL\_Emu project for your own system.

## Background
NTOSKRNL\_Emu is a project that adds missing library functions for ntoskrnl.exe and storport.sys. This enables drivers designed for newer versions of Windows to be backported to as far back as Windows XP. This includes some of the generic drivers written by Microsoft, but can also apply to drivers from computer manufacturers.

The original repository is found here: https://github.com/MovAX0xDEAD/NTOSKRNL_Emu

## Purpose
Aside from what has already been stated, the project is extremely useful for anyone looking to toy with old operating systems far past their expiration date. The original readme was written for the users on [MSFN](https://msfn.org/board/topic/181615-ntoskrnl-emu_extender-for-windows-xp2003), who can be expected to know the tools needed to perform the task. However, the guide is not very beginner-friendly, especially when this context is not explictly written anywhere. These web pages are designed to help beginners, while also providing an explanation for the reason for doing certain things.

## Content
> [!WARNING]
> There is a good chance that you may damage your system or render it unstable by following this guide.
>
> I am not responsible for any damages.

1. [Building and Installing NTOSKRNL\_Emu](01_build_ntoskrnl_emu/index.md)
2. [Using CFF Explorer](02_cff_explorer/index.md)
