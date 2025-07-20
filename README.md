Hello, this is the start of the HPC Software Project using RISC-V

# 1. Setup

Ubuntu 20.04 is recommended. Ubuntu 20.04 is currently the latest recommended long-term stable release of Ubuntu. It is also the easiest to install and run the environment in this environment.

Go over to https://github.com/johnwinans/riscv-toolchain-install-guide and follow the given instructions (even better, refer to the attached YouTube video) -

Broadly the required software to be downloaded -

1. GNU RISCV toolchain
2. QEMU for virtualization
3. GDB dashboard

# 2. Running the repo

Run the following commands at the terminal

# 3. Building and usage

- `make`：Compile and build
- `make run`：Start qemu and run
- `make debug`：Start debugging
- `make code`：Disassemble to view binary code
- `make clean`：cleanup

# 4. References

The design of this Software heavily relies on the following, thank you :)

- The Adventures of OS：<https://osblog.stephenmarz.com/index.html>
- RISCV Operating System MOOC ; <https://github.com/plctlab/riscv-operating-system-mooc>