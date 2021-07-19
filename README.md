# Pipelined-RISC-Processor
This is a virtual pipelined RISC processor implemented using python. The data hazards(RAW) are addressed by having a flag for each register and control hazards cause stalls in the pipeline. The instruction set and other pertinent details can be found in _PipelinedProcessor.pdf_. The bash script file _compile.sh_ acts as an 'assembler' to produce machine instructions for the assembly code. Our code produces the program-modified _DCache.txt_ and _Output.txt_ which contains various characteristics of the program run(like # of stalls, # of insns of various types, avg CPI, etc). Both these files will be in the output folder. 

###### Test Instance

Here, the assembly code in _program.asm_ has been assembled to give the ICache.txt in _input_ folder. And the files given in the _input_ folder have been fed into the pipeline to produce the outputs in _output_ folder.
