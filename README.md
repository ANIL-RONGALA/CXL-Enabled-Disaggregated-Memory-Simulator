# CXL-Enabled-Disaggregated-Memory-Simulator
A reproducible simulation framework for Compute Express Link (CXL) performance exploration. Built on gem5 and integrated with cycle-accurate DRAM simulators (Ramulator / DRAMsim3) to model CXL.io and CXL.mem transactions.

CXL-Enabled-Disaggregated-Memory-Simulator/
├── docs/                 # design docs, diagrams, validation notes
├── gem5/                 # patched gem5 source for CXL.io + CXL.mem hooks
├── dramsim3/             # integrated DRAMsim3 (or Ramulator) backend
├── workloads/            # microbenchmarks + traces (STREAM, lmbench, etc.)
├── scripts/              # automation (build, run, plot)
│   ├── setup_env.sh
│   ├── run_benchmarks.py
│   └── parse_results.py
├── dashboard/            # Jupyter notebooks, matplotlib dashboards
├── docker/               # Dockerfile, container configs
├── tests/                # regression tests / CI configs
├── LICENSE
└── README.md
