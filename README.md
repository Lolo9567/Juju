# SAT-solver
This project focuses on designing and implementing an FPGA-based SAT solver, aimed at solving Boolean Satisfiability Problems (SAT) expressed in Conjunctive Normal Form (CNF).
The solver is built using VHDL and programmed onto an FPGA board, enabling efficient hardware-based parallelism for solving SAT problems. 
The SAT solver determines whether a given CNF formula is satisfiable, and if so, returns a satisfying assignment of values to the variables.
The core algorithm is based on the DPLL (Davis–Putnam–Logemann–Loveland) algorithm, a complete algorithm that either finds a solution or proves that none exists. 
The FPGA design implements this algorithm, ensuring completeness while optimizing the decision-making process through advanced heuristics like Variable State Independent Decaying Sum (VSIDS) to improve performance by efficiently selecting decision variables.
By utilizing the parallel processing capabilities of FPGA, this implementation aims to outperform traditional CPU-based SAT solvers, especially for large problem instances. 
The combination of the DPLL algorithm with FPGA's hardware optimizations enables faster traversal of the search space, making this solution particularly suitable for high-performance applications in hardware verification, circuit design, and optimization tasks.
