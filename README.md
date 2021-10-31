# C-ideas
Ideas for c++ 
I have made this repository to learn more about GitHub as well as to leand c++
INCLUDE Irvine32.inc
.data
s dword ?
Ideas for c++ 
I have made this repository to learn more about GitHub as well as to leand c++
INCLUDE Irvine32.inc
.data
s dword ?
INCLUDE Irvine32.inc
.data
s dword ?
d dword ?
char byte "c"
INCLUDE Irvine32.inc
.data
s dword ?
INCLUDE Irvine32.inc
.data
s dword ?
d dword ?
char byte "c"
  string BYTE "Enter age",0
  msg byte "eligible",0
  msg2 byte "not eligible",0
  string2 byte "do u have a bsc degree, enter 1 for yes and 0 for no",0
.code
main PROC
  mov edx,offset string 
   call WriteString
   
   s dword ?
d dword ?
char byte "c"
  string BYTE "Enter age",0
  msg byte "eligible",0
  msg2 byte "not eligible",0
  string2 byte "do u have a bsc degree, enter 1 for yes and 0 for no",0
.code
main PROC
  mov edx,offset string 
   call WriteString
   call readint
   mov s,eax
   cmp al,22
   jl L2
   jg L1
L1:
	mov edx, offset msg
	  call writestring  
	   jmp _exit  
L2:
	mov edx, offset string2
	call writestring
	call readint
	mov d,eax
	cmp d,0
	jle L3
	jge L1
	
	L3:
	mov edx, offset msg2
	  call writestring  
	   jmp _exit  

	   _exit: 
	    call readintcall readint
   mov s,eax
   cmp al,22
   jl L2
   jg L1
d dword ?
char byte "c"
  string BYTE "Enter age",0
  msg byte "eligible",0
  msg2 byte "not eligible",0
  string2 byte "do u have a bsc degree, enter 1 for yes and 0 for no",0
.code
main PROC
  mov edx,offset string 
   call WriteString
   call readint
   mov s,eax
   cmp al,22
   jl L2
   jg L1
L1:
	mov edx, offset msg
	  call writestring  
	   jmp _exit  
L2:
	mov edx, offset string2
	call writestring
	call readint
	mov d,eax
	cmp d,0
	jle L3
	jge L1
	
	L3:
	mov edx, offset msg2
	  call writestring  
	   jmp _exit  

	   _exit: 
	    call readint
	    Mov Eax,0h
add Eax,10h
Call DumpRegs
Sub Eax, 10h
Call DumpRegs
Call ReadInt 
  
  ; Stoping Console from disappearning
  exit
 main ENDP
 end main
 INCLUDE Irvine32.inc
.data
s dword ?
d dword ?
char byte "c"
  string BYTE "Enter age",0
  msg byte "eligible",0
  msg2 byte "not eligible",0
  string2 byte "do u have a bsc degree, enter 1 for yes and 0 for no",0
.code
main PROC
  mov edx,offset string 
   call WriteString
   call readint
   mov s,eax
   cmp al,22
   jl L2
   jg L1
L1:
	mov edx, offset msg
	  call writestring  
	   jmp _exit  
L2:
	mov edx, offset string2
	call writestring
	call readint
	mov d,eax
	cmp d,0
	jle L3
	jge L1
	
	L3:
	mov edx, offset msg2
	  call writestring  
	   jmp _exit  

	   _exit: 
	    call readint
	    Mov Eax,0h
add Eax,10h
Call DumpRegs
Sub Eax, 10h
Call DumpRegs
Call ReadInt 
  
  ; Stoping Console from disappearning
  exit
 main ENDP
 end main

