---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}


[Here](../files/resume.pdf) is the PDF.

# Education

## University of Electronic Science and Technology of China(UESTC) - Sep.2020 ~ Jul
.2024(expected)
* Major: Computer Science and Technology \| **GPA:3.93/4.00**
* Core course: The C/C++ Programming, Computer Operating System, Programming Languages and Compiling, Software Engineering, Principle and Application of Database, Principles of Computer Organization,  Computer Architecture.

# Working Experience

## [Tencent Technology (Shenzhen) Co.Ltd](https://www.tencent.com/en-us) - Jun. 2022~Sep. 2022


*Intern Security Enginner*
  * Conducted in-depth logical analysis on over ten pieces of malicious software to identify their mechanisms.
  * Formulated comprehensive countermeasure recommendations to mitigate the threats posed by the malicious software.
  * Developed a sample software based on the analyzed malicious software to provide defensive solutions.

# Research Experience

## Host Co-operate SSD filesystem - Dec. 2022 ~ present

*Supervisor: Dr. Li Lin* \
*Designed and implemented a novel cooperative filesystem that optimizes I/O performance by coordinating between the host and emerging computing-capable SSD, especially in the case of disaggregated computing and storage resources.*
* Proposed a collaborative solution that offloads certain filesystem operations from the host to the SSD, such as Path-Lookup and File-Mapping.
* Conducted a comprehensive comparative study on the state-of-the-art filesystems and proposed an innovative space layout management scheme meeting high concurrency requirements.
* Developed a highly adaptive logging system to ensure maximum reliability with minimal overhead for this filesystem.
* Customized and pruned an open-source *SSD* simulator to provide a simulation platform evaluating the performance of the computing-capable *SSD*.
* Conducted rigorous testing and analysis on the prototype demo extensively, demonstrating reduced write amplification and alleviated bus transmission pressure.


# Projects


## Porting and Packing of Thunderbird 102.0 from X86 to Loongarch64 \| *Rust, Shell* - May. 2023 ~ Jul.2023

* Cross-compiled Rustc on LoongArch and established the necessary compilation environment for compiling Thunderbird.
* Adapted the source code to ensure successful compilation and execution on the LoongArch64 platform.
  * Conducted comprehensive testing with a total of 406 tests, achieving a pass rate of 95\% with 387 successful tests.
* Integrated all modifications into a single patch and packaged the source code into an APT package.

## Development of a Bootstrap Lisp-like Functional Language Interpreter \| *Lex, Yacc, C++*  - Apr. 2023 ~ Jun.2023

* Formulated a comprehensive set of syntactic and lexical rules and successfully implemented the parser and lexer.
* Developed robust data structures and algorithms to facilitate semantic analysis.
* Implemented seven basic operators and enabled the definition and invocation of custom functions.
* Constructed a custom function that able to interpreter this language to achieve interpreter bootstrapping.

## Optimization of Sieve of Eratosthenes based on *MPI* \| *MPI, C++* - Mar. 2023 ~ Apr. 2023
* Developed a multithreaded program which leveraged *MPI* to parallelize the Sieve of Eratosthenes algorithm for the calculations of prime numbers up to any given limit.
* Achieved a good performance metric, with calculations for a data size of one billion completed in just 0.52 seconds.



## Development of Storage Engine & Search Engine of Database \| *C++* - Apr. 2022 ~ Jun.2022
* Designed and implemented a cluster storage engine and a *B+ Tree* based search engine of database.
* Conducted and successfully passed more than 500 unit tests, covering basic storage functionalities to large-scale data retrieval scenarios.
* Evaluated by a dataset of 10 million variable-length records, each averaging 8 bytes in size, and demonstrated the following performance metrics: 
  * Average search time per record: *0.04 ms*.
  * Average insertion time per record: *12,931 ms*.

## Heterogeneous filesystem based on non-volatile memory \| *C, C++* - Nov. 2021 ~ Oct. 2022
* *Designed and implemented a filesystem which combines traditional SSD and emerging non-volatile memory (NVM).*
* Proposed an innovative space layout management scheme that stores metadata on high-performance *NVM* and file data on *SSD* separately, reducing random Disk *I/O*.
* Devised a buffer solution that fully utilized *NVM* as write buffer, consolidating multiple write disk requests into a single sequential write request for enhanced write throughput.
* Implemented the prototype filesystem using Filesystem in Userspace *(FUSE)* and leveraged the Storage Performance Development Kit *(SPDK)* to drive the SSD while bypassing the kernel.

## Gobang(five-in-a-row) AI based on Minimax and Alpha-Beta-pruning \| *C* - Apr. 2021 ~ Jun.2021
* Evaluated various algorithms for the Five-in-a-Row board game and ultimately designed an AI agent primarily based on the Minimax algorithm, augmented with alpha-beta pruning and heuristic search for higher computational efficiency.
* Demonstrated the robust performance of the agent, reacting to moves within approximately 4 seconds on average and exhibiting strong strategic gameplay.


# Leadership Experience


## Light Volleyball Team of School of Computer Science and Engineering *(SCSE)*
*Captain*
* Led a team of 8 members in skill development and competition.
* Directed regular team practices and led our team to win the **Champion** of *Cup of UESTC*.


## Light Volleyball Team of University of Electronic Science and Technology of China *(UESTC)*
*Vice Captain*
* Led a team of 10 members in skill development and competition.
* Directed regular team practices and led our team to take part in the Sichuan provincial match, ranking **4th** among numerous university teams.

# Miscellaneous


* Programming language: C/C++, Python, Lisp, Haskell, Rust, Java
* Developer Tools: VS Code, Git, Gdb, Vim, Visual Studio
* Technologies/Frameworks: Linux, MPI, LATEX, Lex&Yacc, CUDA C
* English Proficiency: IELTS 7.0, GRE 322 
