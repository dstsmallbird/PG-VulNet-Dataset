# PG-VulNet Dataset

PG-VulNet is a cross-architecture vulnerability detection approach.  

This project are the datasets used in our paper published in ESEM'22.  

## Description

### Filenames

`{arch}_{compiler}-{compiler_version}_{optimization}_{function_name}_{vul/fix}_{source_file}`

### Folders

- `pseudo-code`: files extracted from the binaries
- `graph`: graphs extracted from files in `pseudo-code`
- `matrix`: matrixs converted from files in `graph`

