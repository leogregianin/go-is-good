# What's this

This repository is a curated list of articles that celebrate Golang’s strengths and why it’s a joy to use.

## Motivation

It feels like praising Go’s brilliance is a trend worth jumping on. Newbies deserve to see why seasoned devs rave about it before diving in, and veterans might just want a little validation. So here’s the good stuff, all in one place.

## What it's for

This repo isn’t here to bash other languages or start pointless debates (we’re above that). It’s all about shining a light on what Golang does right, straight from the minds of those who’ve used it and loved it—no blind hype, just solid, technical praise for educational vibes. Contributors might even disagree on some details, and that’s cool—diversity of thought keeps it real.

Nobody’s saying Go is flawless (what language is?), but when it shines, it shines. Wondering if that feature you love is a stroke of design genius or just a happy accident? This list has your back.

## How to use it

You’re coding away, and suddenly, Go does something so slick you can’t believe it. Or maybe you’re stuck and wondering if it’s got your solution. Pop in here, skim the list, and see why others think it’s great. If it’s a common strength—like concurrency magic or single-binary bliss—it’ll be here. Then you can decide: lean into Go’s strengths, tweak your approach, or just bask in the glow of a well-made tool.


# The List

- [https://blog.golang.org/concurrency-is-not-parallelism](https://blog.golang.org/concurrency-is-not-parallelism) (Rob Pike, 2013)  
  - Goroutines: lightweight threads with ~2KB stack, scaling to millions without breaking a sweat  
  - Channels: CSP-style sync that beats mutex spaghetti for concurrent data flow  
  - Runtime scheduler: multiplexes goroutines onto OS threads like a boss  

- [https://medium.com/@kevalpatel2106/why-should-you-learn-go-f607681fad65](https://medium.com/@kevalpatel2106/why-should-you-learn-go-f607681fad65) (Keval Patel, 2017)  
  - Garbage collector: low-latency, incremental, keeps memory in check without manual fuss  
  - Interface system: implicit satisfaction, no boilerplate `implements` nonsense  
  - `go test`: built-in testing with race detection and benchmarks, no third-party hacks  

- [https://blog.cloudflare.com/what-weve-been-doing-with-go/](https://blog.cloudflare.com/what-weve-been-doing-with-go/) (John Graham-Cumming, 2013)  
  - High Concurrency: Goroutines simplify handling many requests at once (e.g., Railgun).
  - Scalability: Easily adjusts to traffic changes in Cloudflare’s global setup.
  - Simple Distribution: Single executable makes deployment straightforward.
  - Network Performance: Excels in I/O and low-latency network tasks.
  - Productivity: Fast development with simple syntax and tools.

- [https://www.uber.com/en-DO/blog/automating-efficiency-of-go-programs-with-pgo](https://www.uber.com/en-DO/blog/automating-efficiency-of-go-programs-with-pgo/) (Chris Zhang, Yufan Xu, Milind Chabbi, Shauvik Roy Choudhary, 2025)  
  - Performance Boost: PGO uses runtime profiling to optimize hot code paths, improving efficiency (e.g., up to 30% fewer iTLB misses in go-json benchmarks).
  - Resource Savings: Reduces CPU usage across services by refining optimizations like function inlining and register allocation.
  - Scalable Framework: Continuous PGO pipeline (daily profiling, CI testing, deployment) ensures ongoing efficiency at scale.
  - Faster Builds: Profile preprocessing tool cuts compilation time, addressing initial PGO build delays (up to 8x faster).
  - Real-World Impact: Benchmarks and service evaluations show measurable gains in performance and resource use.

- [https://rakyll.org/generics-facilititators/](https://rakyll.org/generics-facilititators/) (Jaana Dogan, 2021)  
  - Generics proposal has some limitations, including the absence of parameterized methods.
  - Facilitators enable developers to write generic query functions against user-provided types.
  - This pattern makes the limitation of not having generic methods less impactful in practice.


# Reverse complaints index

not yet

# Get involved

Feel free to add a PR with a new or old article you found on the internet. The structure is simple, just edit readme.md!
