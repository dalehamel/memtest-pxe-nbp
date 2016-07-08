Memtest as iPXE NBP

# Arguments

## console=

Set with ```console=<param>```

Set up a serial console for output

Examples of accepted params:
  ttyS0
  ttyS1
  ttyS0,115200
  ttyS0,9600e8

## onefail

Flag to exit immediately on failure

## onepass

Flag to nun one pass and exit if there are no errors

## passes=

Set with ```passes=<number>```

Run a maximum of ```<number>``` passes, then exit

## smp

Flag to allow SMP to be enabled by default

## btrace

Flag to enable boot trace

## maxcpus=

Set with ```maxcpus=<number>```

The maximum number of CPUs to use.

## tstlist=

Setup a list of tests to run

## cpumask=

Set a CPU mask to select CPU's to use for testing
