# UD IT-RCI Managed Software, Caviness

All changes to the software maintained by IT RCI on the caviness.hpc.udel.edu HPC cluster will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).  Primary headings are the nominal date of the changes (with optional time) in the format of `YYYY-MM-DD{ HH:MM}`.  Secondary headings are **Added**, **Modified**, or **Removed**.  All top-level list items are either:

- A package id followed by a sub-list keyed on version id(s)
    - Each sub-list item is `«version-id»{ -- «string»}` with an optional sub-list of informational strings
- A versioned package id as `«versioned-pkg-id»{ -- «string»}` with an optional sub-list of informational strings

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
- intel-mkl-oneapi
    - 2024.2.0.634

### Modified
- intel-oneapi
    - 2024 -- alias to 2024.2.0.634


## 2024-07-17

### Added
- anaconda/2024.02

