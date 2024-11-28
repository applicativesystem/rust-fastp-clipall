# rust-fastp-clipall
 - rust-fastp-clipall dropping all clips
 - in this it drops all the sites with the defined clip value as compared to the previous quality drop where is drops a specific base in the read. 
 - this is the last version of the fastp.
 - general note: Incase of Golang and RUST, please see the last commit message and if it says compiled binary then it is completed or else still in development version.


```
cargo build 

```
- to run 
```
λ gauravsablok rust-fastp-clipall → λ git main → ./target/debug/rust-fastp-clipall -h
Usage: rust-fastp-clipall <READS_1_ARG> <READS_2_ARG> <QUALITY_SCORE>

Arguments:
  <READS_1_ARG>    please provide the reads R1 file path
  <READS_2_ARG>    please provide the reads R2 file path
  <QUALITY_SCORE>  please provide the quality value to be used as a threshold

Options:
  -h, --help     Print help
  -V, --version  Print version
```

Gaurav Sablok
