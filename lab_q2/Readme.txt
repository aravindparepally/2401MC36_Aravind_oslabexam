Name:Parepally Aravind
Roll_No:2401MC36
set_No:all have same set number(2-4pmshift)

In kalloc.c i have added and updated kalloc(),kfreefunction and declared variables like cnt ,mem.lock mem.pagecount etc implemented a sys call freepages
in vm .c adeed virtual addr to pysical addr using uva2ka as helper function   and added in defs.h too and updated walkpgdir 
crated a memtest.c decleared intial page cnt and final page cnt and printed them used sbrk(4096* 10) printed V.a and P.A andprocess vms pages page tables 
forked child process tot syspages , free system pages ,process vma pages and page table pages(printed after child exist and reaped too).o

 
