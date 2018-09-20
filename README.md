# TripleNestedLoopDemo.jl
Simple triple-nested-loop GEMM implementations in Julia and C compared.
Written in collaboration with [@xorJane](https://github.com/xorJane).

![performance comparison image](https://github.com/Sacha0/TripleNestedLoopDemo.jl/blob/master/perfvis.png)

Performance comparison of simple triple-nested-loop dgemm implementations (specifically `C = AB + C`, no `α` or `β`) in Julia and C, for all loop orderings. The horizontal axis provides matrix size/shape; all matrices are square and of the same size. The vertical axis provides average GFLOPS achieved over the operation.

Find the demo in [src.ipynb (via nbviewer.jupyter.org)](https://nbviewer.jupyter.org/github/Sacha0/TripleNestedLoopDemo.jl/blob/master/src.ipynb). (GitHub-rendered version [here](https://github.com/Sacha0/TripleNestedLoopDemo.jl/blob/master/src.ipynb).)