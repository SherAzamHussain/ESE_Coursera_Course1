/******************************************************************************
 * Copyright (C) 2017 by Alex Fosdick
 *
 * Redistribution, modification or use of this software in source or binary
 * forms is permitted as long as the files maintain this copyright. Users are 
 * permitted to modify this and use it to learn about the field of embedded
 * software. Alex Fosdick and the University of Colorado are not liable for any
 * misuse of this material. 
 *
 *****************************************************************************/
/**
 * @author: Sher Azam
 * @date : 10, july 2018
 * @brief:  a makefile that can natively and cross compile applications.
 *        
 *        Using GNU tools, GCC and GNU Make creat a build system to compile multiple files,
 *        link them togather and creat a final excutable.
 *  
 * 
 * The source files exist inside the /src folder. You can genrate preprocessor, assembly, * 
 * object, dependency, executable, and map output files for the host m achhine and target 
 * embedded system MSP432.    
 *  
 * 
 * 
 * 
 * clean : will remove all generated files , only leave makefile , *.mk , *.c
 * 
 * compile-all : will generate  *.o file for each *.c file
 * 
 * build : will generate *.o file for each *.c file ,c1m2.map , c1m2.out & *.d file for each 
 *         source file , and it will give data about code size and memory allocation 
 * 
 * all the others will generate the required file with its extension from existing source files
 *
 **/
