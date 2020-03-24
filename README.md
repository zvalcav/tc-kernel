# tc deletion problems repository - 24. 3. 2020
## perf record results
perf.data.enp1s0f0
perf.data.ifb0

## perf trace results - with --syscalls
tc-del-enp1s0f0.txt
tc-del-ifb0.txt

## reproducers
- load with `tc -force -batch file_name.txt`
- tc-enp1s0f0-upload.txt
- tc-enp1s0f1-download.txt - reproducer enp1s0f1 interface
- tc-ifb0-upload.txt - reproducer for ifb0 interface
- tc-ifb1-download.txt - reproducer for ifb1 interface
