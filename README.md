# source_bat

`source_bat.bash` is used to retrieve environmental variable changes from batch files when using Git Bash on windows. This is necessary to use Git Bash with batch files like `vcvarsall.bat` for MSVC and `setup.bat` for ROS.

To install, copy source_bat.bash to a directory contained in $PATH. Optionally a bash alias can be configured.

    alias source_bat="source source_bat.bash"

Example usage in Git Bash to initialize for use with MSVC compilers:

    source source_bat.bash c:/Program\ Files\ \(x86\)/Microsoft\ Visual\ Studio/2019/Community/VC/Auxiliary/Build/vcvars64.bat

