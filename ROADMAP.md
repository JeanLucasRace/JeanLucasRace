# Study Roadmap — Chip Engineering & Computer Architecture

Self-directed track, run in parallel with a Computer Science degree, to close the gap between coursework and industry-level chip engineering / hardware verification work. Two tracks: hardware & computer architecture, and the math/physics foundation under it. Checked items are done; the rest is in progress.

## Baseline (before this roadmap)

- [x] Assembly, C, C++98
- [x] Verilog — basic (combinational/sequential circuits, no processor built yet)
- [x] PCB — basic (simple schematics, up to 2-layer routing)

## Track 1 — Hardware & Computer Architecture

- [ ] Modern C++ (*Effective Modern C++*, Meyers) — smart pointers, move semantics, RAII
- [ ] Computer architecture fundamentals — *Computer Organization and Design* (Patterson & Hennessy, RISC-V ed.), *Digital Design and Computer Architecture* (Harris & Harris)
- [ ] Computer architecture, advanced — *Computer Architecture: A Quantitative Approach* (Hennessy & Patterson) — ILP, memory hierarchy, power/performance/area trade-offs
- [ ] SystemVerilog + UVM — *SystemVerilog for Verification* (Spear & Tumbush), *A Practical Guide to UVM* (Rosenberg & Meade)
- [ ] RTL project progression: combinational circuits → sequential circuits/FSMs → ALU + register file → single-cycle datapath → full RISC-V (RV32I) with pipeline, verified in UVM
- [ ] FPGA — open-source flow (Yosys/nextpnr) or Vivado/Quartus; port the RISC-V core to real hardware with working I/O
- [ ] Advanced PCB — multilayer boards (KiCad), signal/power integrity, high-speed routing, RF fundamentals
- [ ] Architecture simulation — gem5 / ChampSim: run and modify existing models
- [ ] AI accelerator architecture — systolic arrays, dataflow, quantization (INT8/FP16/BF16), memory-bandwidth bottlenecks (HBM)
- [ ] Open-source silicon flow — OpenLane/OpenROAD, SKY130 PDK: RTL-to-GDSII on an original design
- [ ] Portfolio target — own RISC-V design carried through to a valid GDSII (clean DRC/LVS)

## Track 2 — Math & Physics

- [ ] Algebra, trigonometry, analytic geometry
- [ ] Calculus I–III, ODEs (Stewart / Spivak)
- [ ] Complex analysis (Brown & Churchill)
- [ ] Linear algebra (Axler / Strang)
- [ ] Classical mechanics, Lagrangian/Hamiltonian formalism (Taylor / Goldstein)
- [ ] Electromagnetism (Griffiths) — direct foundation for signal integrity
- [ ] Fourier & Laplace analysis, signal processing (Oppenheim & Willsky)
- [ ] Group theory (prerequisite for quantum mechanics)
- [ ] Quantum mechanics (Griffiths)
- [ ] Solid-state / semiconductor physics (Ashcroft & Mermin, Neamen) — target: explain physically why a MOSFET switches
- [ ] Discrete math & graph theory (Rosen)
- [ ] Numerical linear algebra (Trefethen & Bau)
- [ ] Partial differential equations (Strauss)
- [ ] Remaining abstract algebra & real analysis (Gallian, Rudin)
- [ ] Advanced electrodynamics / EMC

## Languages

- [ ] English — technical reading and spoken fluency (priority)
- [ ] Mandarin — HSK track (Taiwan/China semiconductor ecosystem)
- [ ] German — after English is solid (European semiconductor hubs)

## Long-term

Contribute to RISC-V open-source projects, read and eventually contribute to computer-architecture research (ISCA/MICRO), pursue graduate study in the field, and complete a real tape-out (e.g. via Efabless/Google Open MPW).
