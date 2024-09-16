# Literature-Review
Literature Review for Programming Languages
Teresa Wong

## README: Exploring Compiled and Interpreted Programming Languages with ChatGPT

### Introduction
This README documents my exploration of the differences between compiled and interpreted programming languages using ChatGPT (GPT-4). I leveraged the model to gather insights on these topics, refine the results, and create a structured, engaging narrative. Throughout the process, I sought to balance clarity with technical depth, using concise explanations and helpful references. The goal was to create a document that is not only informative but also easy to follow for anyone new to programming languages.

### Initial Question: Compiled vs. Interpreted Languages
I started by asking ChatGPT, **“What are the key differences between compiled and interpreted programming languages?”**. Below is a short summary of the information gathered from the model:

**Compiled Languages**:
- Translates source code into machine code via a compiler before execution.
- Results in faster performance as the machine code runs directly on the hardware.
- Errors are caught during the compilation process, which can slow down the development cycle.
- Examples: C, C++.

**Interpreted Languages**:
- Source code is translated line-by-line at runtime by an interpreter.
- Slower in execution due to real-time translation.
- Errors are caught at runtime, allowing for more flexible, but potentially error-prone, development.
- Examples: Python, JavaScript.

Afterward, I asked ChatGPT to provide additional differences between compiled and interpreted languages, which resulted in eight more distinctions, some including memory management, portability, debugging considerations, and even included information on a hybrid approach.

### Deep Dive: Hybrid Approaches
Intrigued by the mention of hybrid approaches, I asked ChatGPT to explain how hybrid approaches work and why they matter. It explained that hybrid models combine aspects of both compiled and interpreted languages. For example, Java first compiles source code into bytecode, which can be interpreted or further compiled during runtime. Similarly, Just-In-Time (JIT) compilation is used to speed up interpreted languages like JavaScript.

Hybrid approaches provide a middle ground between speed (compiled) and flexibility (interpreted). Notable examples include:
- **Java Virtual Machine (JVM)**: Used in Java and Kotlin to first compile into bytecode, then interpret or compile just-in-time during runtime.
- **Python’s PyPy**: Implements JIT to boost the performance of Python by compiling hot code paths during execution.

### Historical Context: Evolution of Language Models
Follwing the research, I was curious about how the differences between compiled and interpreted languages have evolved over time. According to ChatGPT, early programming languages like Fortran and COBOL (1950s) were compiled for performance, while interpreted languages like LISP provided more flexibility, albeit with slower execution. Over the decades, hybrid approaches like Java’s JVM emerged, blending the strengths of both models.

### Influence of Compiler Theory and Other Subfields
To futher my understanding, I asked ChatGPT how subfields of programming languages contributed to the investigation of these language types. It explained that:
- **Compiler theory** has advanced techniques for translating high-level languages into machine code.
- **Interpreter design** focuses on runtime code execution without prior compilation.
- **Just-In-Time compilation** bridges the gap between the two, optimizing frequently executed code during runtime.
- **Virtual machines (e.g., JVM)** and **systems programming** contribute to understanding hybrid models, improving language execution efficiency and flexibility.

### Key Contributions and Researchers
Notable figures in the history of programming languages were also discussed. ChatGPT gave me 10 important figures, where 2 of the figures really stood out to me. The first being **John Backus**, the developer of Fortran. He laid the groundwork for compiled languages, while **Grace Hopper**,the second person who stood out to me, was known for creating the first compiler, significantly advancing the field by promoting automatic translation of high-level code into machine code, shaping how modern languages operate.

### Most Influential Resources
Throughout this journey, I asked ChatGPT to reference some key literature and software that have shaped our understanding of programming languages:

- **"Compilers: Principles, Techniques, and Tools" (Dragon Book)** by Aho et al.: A foundational text in compiler theory, providing deep insights into code generation and optimization.
- **LLVM Project**: An open-source compiler framework that supports both AOT and JIT compilation, crucial in modern language development and optimization efforts.

### Conclusion on the Benefits of LLMs in Learning Information
Through the use of Large Language Models (LLMs), they have proven to be incredibly beneficial in enhancing learning and information acquisition. Their ability to process vast amounts of data and generate coherent, contextually relevant responses allows learners to access information quickly and efficiently. By interacting with LLMs, it can asnwer complex questions and give indepth explanations in real time, helping to facilitate a deeper understanding of concepts. LLMs can also be used to help break down complicated topics into simpler components, enabling users to learn at their own pace. 

### Conclusion on Learning About Interpreted vs. Compiled Languages
Through studying interpreted and compiled languages, I learned the fundamental differences in how these two types of languages are executed and their impact on performance and development processes. Compiled languages, like C and C++, convert source code into machine code ahead of execution, leading to faster execution but requiring a build process. In contrast, interpreted languages, like Python and JavaScript, execute code line-by-line at runtime, allowing for more flexibility and quicker debugging but generally slower performance. I also explored how hybrid approaches, such as Just-In-Time (JIT) compilation, aim to bridge the gap between the two, combining the efficiency of compiled languages with the flexibility of interpreted languages. This understanding helps in making informed decisions about which language to use based on the requirements of a project, whether performance or development speed is prioritized.

### ChatGPT References
- Aho, A.V., Lam, M.S., Sethi, R., Ullman, J.D. (2006). **Compilers: Principles, Techniques, and Tools**. Addison-Wesley. [Google Scholar](https://scholar.google.com)
- LLVM Project: [LLVM](https://llvm.org/)
