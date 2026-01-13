Libft - The Foundation of C Programming | 42 Madrid
📖 Overview
Libft (Library of Functions) is the first project at 42 Madrid. It consists of creating a personal C library containing my own versions of standard libc functions, along with additional utilities for string manipulation, memory management, and data transformation.

In 42, we are not allowed to use standard libraries. We must understand how they work "under the hood" by rebuilding them from scratch. This project demonstrates my deep understanding of memory, pointers, and algorithmic efficiency.
🛠️ Technical Implementation
This library is built strictly following the 42 Norm and high-performance requirements:

Manual Memory Management: Explicit use of malloc(3) and free(3) to ensure efficiency and zero memory leaks.

Compilation Rigor: All files are compiled with -Wall -Werror -Wextra flags.

Static Library: The project generates a libft.a file using the ar command, managed via a robust Makefile.

Zero Global Variables: Ensuring thread safety and modularity.

🧬 Data Engineering Connection
How this project prepared me for a Data Engineering career:

Data Cleaning & Parsing: Functions like ft_split, ft_strtrim, and ft_substr are the low-level logic behind modern ETL (Extract, Transform, Load) processes.

Type Conversion: Implementing ft_atoi and ft_itoa provided a fundamental understanding of how data types are converted during ingestion.

Buffer Management: Rebuilding memcpy and memmove is crucial for understanding how large datasets are moved and processed in memory without corruption.

File Descriptors: Functions like ft_putstr_fd introduced me to handling I/O streams, the basis of log processing.

