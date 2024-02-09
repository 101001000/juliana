# JULIANA (**J**ulia **U**nification **L**ayer for **I**ntel, **A**MD, **N**vidia and **A**pple)


Only single files and a very limited feature set is supported right now.

Translation from CUDA -> KernelAbstraction is the only translation supported right now.


Usage: 
```console
~$ julia fileinput.jl fileoutput.jl (CUDA|ONEAPI|METAL|CPU|AMD)
```

Working [Julia Rodinia](https://github.com/JuliaParallel/rodinia/tree/master/julia_cuda) benchmarks:
- [ ] backprop -> requires multifile
- [x] bfs
- [ ] hotspot -> requires shared memory
- [ ] leukocyte -> requires multifile
- [ ] lud -> requires multifile
- [x] nn
- [ ] nw -> requires multifile
- [ ] particlefilter_naive
- [ ] particlefilter_double -> requires shared memory
- [ ] pathfinder -> requires shared_memory
- [ ] streamcluster -> requires multifile
