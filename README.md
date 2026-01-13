# Libft - The Foundation of C Programming | 42 Madrid

## 📖 Overview
**Libft** (Library of Functions) is the first project at **42 Madrid**. It consists of creating a personal C library containing my own versions of standard `libc` functions, along with additional utilities for string manipulation, memory management, and data transformation.

> **The 42 Challenge:** In this school, we are not allowed to use standard libraries. We must understand how they work "under the hood" by rebuilding them from scratch.

---

## 🛠️ Technical Implementation
This library is built strictly following the **42 Norm** and high-performance requirements:

* **Manual Memory Management:** Explicit use of `malloc(3)` and `free(3)` to ensure efficiency and zero memory leaks.
* **Compilation Rigor:** All files are compiled with `-Wall -Werror -Wextra` flags.
* **Static Library:** The project generates a `libft.a` file using the `ar` command, managed via a robust **Makefile**.

---

## 🧬 Data Engineering Connection
*Why this project is relevant for my career in Data:*

1.  **Data Cleaning:** Functions like `ft_split` and `ft_strtrim` are the low-level logic behind modern ETL processes.
2.  **Type Conversion:** Implementing `ft_atoi` and `ft_itoa` is fundamental for data ingestion.
3.  **Efficiency:** Rebuilding `memcpy` and `memmove` is crucial for understanding how large datasets move in memory.

---

## 📂 Function Categories

### Part 1: Libc Re-implementation
| Function | Logic | Use Case |
| :--- | :--- | :--- |
| **ft_strlen** | Character counting | Data validation |
| **ft_memset** | Memory initialization | Clearing data buffers |
| **ft_calloc** | Memory allocation | Dynamic data storage |

### Part 2: Additional Utilities
| Function | Logic | Use Case |
| :--- | :--- | :--- |
| **ft_split** | String to Array | **Parsing CSV/TSV files** |
| **ft_strjoin** | String concatenation | Building data paths |

---

## 🚀 Installation & Usage

1. **Compile the library:**
   ```bash
   make
