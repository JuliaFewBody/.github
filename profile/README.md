## Welcome to JuliaFewBody

This organization revolves around Julia code to solve quantum mechanical few-body problems. This is the hierarchy of packages we plan to publish:

```mermaid
---
config:
  layout: elk
  theme: mc
---
flowchart TD
  A["FewBodyHamiltonians.jl"]
  B["FewBodyECG.jl"]
  C["FewBodyGEM.jl"]
  D["FewBodyDMC.jl"]
  E["FewBodyVMC.jl"]
  F["FewBodyML.jl"]
  Z["FewBody.jl"]
  A --> B & C & D & E
  E --> F
  B & C & D & E & F --> Z
```

Main developers are [Shuhei Ohno](https://github.com/ohno) and [Martin Mikkelsen](https://github.com/MartinMikkelsen). Please reach out if you have any questions, issues or suggestions.
