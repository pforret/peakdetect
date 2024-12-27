![bash_unit CI](https://github.com/pforret/peakdetect/workflows/bash_unit%20CI/badge.svg)
![Shellcheck CI](https://github.com/pforret/peakdetect/workflows/Shellcheck%20CI/badge.svg)
![GH Language](https://img.shields.io/github/languages/top/pforret/peakdetect)
![GH stars](https://img.shields.io/github/stars/pforret/peakdetect)
![GH tag](https://img.shields.io/github/v/tag/pforret/peakdetect)
![GH License](https://img.shields.io/github/license/pforret/peakdetect)
[![basher install](https://img.shields.io/badge/basher-install-white?logo=gnu-bash&style=flat)](https://www.basher.it/package/)

# peakdetect

Detect CPU/MEM/DISK peaks on a web server and document what site/page is the cause

## 🔥 Usage

```
Program : peakdetect  by peter@forret.com
Version : v0.0.1 (Apr 22 16:07:13 2023)
Purpose : Detect CPU/MEM/DISK peaks on a web server and document what site/page is the cause
Usage   : peakdetect [-h] [-q] [-v] [-f] [-l <log_dir>] [-t <tmp_dir>] <action>
Flags, options and parameters:
    -h|--help        : [flag] show usage [default: off]
    -q|--quiet       : [flag] no output [default: off]
    -v|--verbose     : [flag] also show debug messages [default: off]
    -f|--force       : [flag] do not ask for confirmation (always yes) [default: off]
    -l|--log_dir <?> : [option] folder for log files   [default: /Users/pforret/log/script]
    -t|--tmp_dir <?> : [option] folder for temp files  [default: /tmp/script]
    <action>         : [choice] action to perform  [options: action1,action2,check,env,update]
                                  
### TIPS & EXAMPLES
* use peakdetect action1 to ...
  peakdetect action1
* use peakdetect action2 to ...
  peakdetect action2
* use peakdetect check to check if this script is ready to execute and what values the options/flags are
  peakdetect check
* use peakdetect env to generate an example .env file
  peakdetect env > .env
* use peakdetect update to update to the latest version
  peakdetect update
* >>> bash script created with pforret/bashew
* >>> for bash development, also check out pforret/setver and pforret/progressbar
```

## ⚡️ Examples

```bash
> peakdetect -h 
# get extended usage info
> peakdetect env > .env
# create a .env file with default values
```

## 🚀 Installation

with [basher](https://github.com/basherpm/basher)

	$ basher install pforret/peakdetect

or with `git`

	$ git clone https://github.com/pforret/peakdetect.git
	$ cd peakdetect

## 📝 Acknowledgements

* script created with [bashew](https://github.com/pforret/bashew)

&copy; 2024 Peter Forret
