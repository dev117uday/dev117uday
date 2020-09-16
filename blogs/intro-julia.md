<link rel="stylesheet" type="text/css" href="../style.css">

[<button class="mh-button mh-b3">Go Back</button>](../index.md)

Follow me on

[GitHub](https://github.com/dev117uday) || [LinkedIn](https://www.linkedin.com/in/uday-yadav-4995a818a/)

If you want to know more about julia, pelase to go the **Julia section on my notes page [here](https://dev117uday.github.io/notes-md/)**

# Julia: A fresh approach to technical computing

Also an amazing programming language for mathematical modeling data science, statistics, and machine learning.

![Julia intro image](./images/julia.jpeg)

For those of you who don’t know what Julia is, here is a quick and short intro :

- Julia is a high-level, high-performance, dynamic programming language, designed and developed by Jeff Bezanson, Alan Edelman, Stefan Karpinski, Viral B. Shah
- While it is a general-purpose language and can be used to write any application, many of its features are well-suited for numerical analysis and computational science.
- Julia proves to be faster than Python as it keeps reaching the speed of C, puts up a pretty impressive performance against python.
- Julia is simpler than python, yet as fast even faster than C.

### Why Julia
In the world where Python has become the to-go language to Data Science and ML, what brings us to Julia? Well consider this :

![Julia Benchmark](./images/julia_benchmark.png)

[https://julialang.org/benchmarks/](https://julialang.org/benchmarks/)

**A language as simple as python running as fast C, can you believe it.**

Julia is a `JIT(Just In Time)` compiled language, it is fundamentally different from other compiled language ex: Rust and C++. 

But JIT-compiled language must be slower, right? Well technically it should be, but the way Julia’s core is implemented makes it faster than what is expected. You can read more about it here :

**[Why Julia is so fast](https://ucidatascienceinitiative.github.io/IntroToJulia/Html/WhyJulia#:~:text=The%20core%20design%20decision%2C%20type,some%20very%20clear%20performance%20gains)**

### Why I love Julia
- Performance: If you have any doubts related to Julia’s performance compared to Python, please throw them aside immediately. Julia is fast, if you want to compare it to c++ or rust, then it is on-par with them, in some cases even faster. It’s blazing fast out of the box, no package/optimization needed.
- Syntax: Julia’s syntax is quite similar to python, but it’s simply simple JavaScript. It follows the same indentation rules as that of python. Here is a code snippet :

```
function g(x,y)     
    return x * y
end
```

- Functionality: It is designed to keep technical computing in focus, it excels at numerical computing with a syntax that is great for math, with support for many numeric data types, and providing parallelism out of the box.

- Parallel computing and GPU programming: Julia was designed to take advantage of parallel computing and leveraging the power of GPU’s in mind.

**Julia was designed for parallelism from the ground-up, and provides built-in primitives for parallel computing at every level: instruction level parallelism, multi-threading, and distributed computing. The Celeste.jl project achieved 1.5 PetaFLOP/s on the Cori supercomputer at NERSC using 650,000 cores.**

**[https://juliacomputing.com/case-studies/celeste.html](https://juliacomputing.com/case-studies/celeste.html)**


Well, the conclusion to draw here is Julia is freaking fast in all ways, but the more important one is Julia is much easier to code in. Earlier these research’s used tools and frameworks that had limitations even it comes to usability. 

Julia is helping researches around the world to do things they are good at, crunching new ideas and methods, and not hindering their ability to experiment.

If you want to get started with Julia on Colab, please refer to one of my previous articles :

**[How to run Julia on Colab](https://medium.com/@dev117uday/how-to-run-julia-on-google-colab-dd631e6e7e43)**

- Amazing Package manager: Just like any other modern programming language, Julia also has a package manager.

Things to know about julia :

- In Julia, Arrays start with index 1 not 0, like Fortran.
- It also has an excellent programming interface with other programming languages like c/c++.

#### Julia Vs Python: From Data science and machine learning perspective.

Julia was designed from the start for scientific and numerical computation, hence it has a lot of advantages over Python.

- Julia is faster than python (we discussed it)
Designed with maths first approach in computing, it has more in-built mathematical functions and support for more operations.

- Example: Let’s say you have a Julia function to square the element passed as arguments and then returns it, now if you pass in a number, you get back it’s square, if you pass in a matrix, you get back the matrix squared (m*m), and if you pass in the matrix with . (dot) operator, then it will return every element of that matrix squared!

- Julia is developing its own native machine learning libraries. Flux is a machine learning library for Julia that has many existing model patterns for common use cases. Since it’s written entirely in Julia, it can be modified as needed by the user, and it uses Julia’s native just-in-time compilation to optimize projects from inside out.

- Python may have more packages: Yes, the package ecosystem of python is bigger, but Julia lacks no support when it comes to toolkit you need to perform any data science or ml task. Plus as stated above, all packages in Julia are written natively.

- Julia also provides an excellent language for those who want to write their own machine learning algorithms, from scratch, or want to experiment with them or make their own. Plus I strongly believe that 98% of people doing data science and machine learning out in the world hardly know anything that’s happening in underneath those algorithms and mathematical function that they call from Keras and NumPy

As of June 2020, Julia is a relatively new programming language. More and more researchers around the world are considering Julia. In my opinion, anyone aspiring in the field of data science and machine learning should definitely learn about Julia, because it’s an amazing programming language they capabilities like no others.

I hope you like this article !