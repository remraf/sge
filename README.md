# sge-wrappers
SGE wrapper scripts

## Description
A collection of wrappers scripts, customized for specific applications, to submit jobs to an SGE scheduler.

Some features of these scripts:

  - simplifies job submission allowing researchers to focus on their domain instead of technology
  - employs fast local scratch storage
  - easily modified for new applications
  - behavior is customizable
  
## Usage
The general syntax is:

```
qsub -pe <parallel_environment> <slots> -N <program_file> <wrapper>
```


