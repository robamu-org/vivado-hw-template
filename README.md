Vivado Hardware Project Template
=======

Empty template for a Xilinx Vivado project using a fork of the 
[digilent-vivado-scripts](https://github.com/robamu/digilent-vivado-scripts).

# Usage

It is recommended to read the [digilent-vivado-scripts](https://github.com/robamu/digilent-vivado-scripts)
on how to use the respective Python script `git_vivado.py` to use version
control with Vivado projects.

After creating a repository based on this template, you can initialize
the submodule containing the scripts with the following git commands:

```sh
git submodule init
git submodule update
```

If you want to use the primary upstream of the digilent scripts, replace
`https://github.com/robamu/digilent-vivado-scripts.git` in the `.gitmodules`
file with `https://github.com/Digilent/digilent-vivado-scripts.git` before
using those commands.
