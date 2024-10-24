# UD IT-RCI Managed Software, DARWIN

All changes to the software maintained by IT RCI on the darwin.hpc.udel.edu HPC cluster will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).  Primary headings are the nominal date of the changes (with optional time) in the format of `YYYY-MM-DD{ HH:MM}`.  Secondary headings are **Added**, **Modified**, or **Removed**.  All top-level list items are either:

- A package id followed by a sub-list keyed on version id(s)
    - Each sub-list item is `«version-id»{ -- «string»}` with an optional sub-list of informational strings
- A versioned package id as `«versioned-pkg-id»{ -- «string»}` with an optional sub-list of informational strings

## 2024-10-24

### Added
- apptainer
    - 1.3.4
- gcc
    - 14.2.0
    - 14.2.0:amd,openacc
        - OpenACC with AMD offload
    - 14.2.0:nvidia,openacc
        - OpenACC with NVIDIA CUDA offload

## 2024-10-03

### Added
- perl
    - 5.38.2
        - GCC 12.2, base features

## 2024-07-18

### Added
- intel-oneapi
    - 2024.2.0.634
        - BaseKit
        - HPCKit
        - intelpython3
    - 2024.2.0.634:no-mpi
        - BaseKit
        - HPCKit (no Intel MPI loaded)
        - intelpython3
    - 2024.2.0.634:aitools
        - BaseKit
        - HPCKit
        - intelpython3
        - AITools
- intel-oneapi-mkl
    - 2024.2.0.634

### Modified
- intel-oneapi
    - 2024 -- alias to 2024.2.0.634
- intel-oneapi-mkl
    - 2024 -- alias to 2024.2.0.634
