Question a :

0000000000601050 B __bss_start
0000000000601050 b completed.6973
U __cxa_atexit@@GLIBC_2.2.5
0000000000601040 D __data_start
0000000000601040 W data_start
0000000000400610 t deregister_tm_clones
0000000000400680 t __do_global_dtors_aux
0000000000600e08 t __do_global_dtors_aux_fini_array_entry
0000000000601048 D __dso_handle
0000000000600e18 d _DYNAMIC
0000000000601050 D _edata
0000000000601058 B _end
0000000000400814 T _fini
00000000004006a0 t frame_dummy
0000000000600df8 t __frame_dummy_init_array_entry
00000000004009f8 r __FRAME_END__
0000000000601000 d _GLOBAL_OFFSET_TABLE_
000000000040077d t _GLOBAL__sub_I__Z7averagePdRd
w __gmon_start__
0000000000400558 T _init
0000000000600e08 t __init_array_end
0000000000600df8 t __init_array_start
0000000000400820 R _IO_stdin_used
w _ITM_deregisterTMCloneTable
w _ITM_registerTMCloneTable
0000000000600e10 d __JCR_END__
0000000000600e10 d __JCR_LIST__
w _Jv_RegisterClasses
0000000000400810 T __libc_csu_fini
00000000004007a0 T __libc_csu_init
U __libc_start_main@@GLIBC_2.2.5
0000000000400735 T main
0000000000400640 t register_tm_clones
00000000004005e0 T _start
0000000000601050 D __TMC_END__
0000000000400740 t _Z41__static_initialization_and_destruction_0ii
000000000040070d T _Z7averageif
00000000004006cd T _Z7averagePdRd
U _ZNSt8ios_base4InitC1Ev@@GLIBCXX_3.4
U _ZNSt8ios_base4InitD1Ev@@GLIBCXX_3.4
0000000000601051 b _ZStL8__ioinit


Question b :

Because the char variable's size is 1 byte; int, float variables are 4 byte;
double variable is 8 byte. However pointer variables' size are according to
the bits of operating system we are working on, because pointer variables
are store in the system's memory. And my opertion system is 64 bits, so 
these pointer variables are in size of 8 byte.
