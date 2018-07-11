Tutorial on Embedding Ceedling and CException in STM32 Project
==============================================================

Add Definition
--------------
CException used in this project uses user define Exception object. It is configured in `CExceptionConfig.h`. The `CException` needs to know this. To get that done, go to `property->MCU GCC Compiler->Preprocessor` and add `CEXCEPTION_USE_CONFIG_FILE`. 