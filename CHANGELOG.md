# UD IT-RCI Managed Software, DARWIN

All changes to the software maintained by IT RCI on the darwin.hpc.udel.edu HPC cluster will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.1.0/).  Primary headings are the nominal date of the changes (with optional time) in the format of `YYYY-MM-DD{ HH:MM}`.  Secondary headings are **Added**, **Modified**, or **Removed**.  All top-level list items are either:

- A package id followed by a sub-list keyed on version id(s)
    - Each sub-list item is `«version-id»{ -- «string»}` with an optional sub-list of informational strings
- A versioned package id as `«versioned-pkg-id»{ -- «string»}` with an optional sub-list of informational strings

## 2025-08-18

### Added
- r
    - 4.5.1
        - R blas
        - Atlas
        - MKL, sequential
        - MKL, threaded

## 2025-06-27

### Added
- libfabric
    - 2.1.0
- ucx
    - 1.18.1
    - 1.18.1 → default

## 2025-06-12

### Added
- apptainer
    - 1.4.1
    - 1.4.1 → default

## 2025-03-14

### Added
- go
    - 1.24.1
    - 1.24.1 → default

## 2025-03-09

### Modified
- r-studio-server
    - script fragment added to create database, run, and log directories under temp storage to be mounted in the container for server-generated state files etc.
    - Singularity options in `SINGULARITY_OPTS` augmented with appropriate bind mounts and container environment values

## 2025-03-05

### Added
- miniconda
    - 25.1.1.2 

## 2025-02-01

## Added
- amd-uprof
    - 5.0.1479
    - 5.0.1479 → default

## 2025-01-13

### Added
- julia
    - 1.11.2
    - 1.11.2 → default

## 2024-12-08

### Added
- ucx
    - unreleased-fbf9232
        - commit includes patched MR caching routines and GVA (full memory space registration)
        - added for testing VASP runs failing due to MR cache exhaustion
- openmpi
    - 4.1.5:intel-2020,ucx-gva
        - build using ucx/unreleased-fbf9232
        - added for testing VASP runs failing due to MR cache exhaustion

## 2024-11-04

### Added
- quantum-atk
    - 2023.12
        - Embedded Intel MPI library is used
    - 2023.12:system-mpi
        - User must add an MPI library to the environment

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
