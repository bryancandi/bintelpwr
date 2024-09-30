# bintelpwr

### bintelpwr:
For INTEL Processors. Display current energy consumption in watts using Intel Running Average Power Limit (RAPL).

---

#### Script `bintelpwr` refreshes every 1 second unless specified with launch option `-t`.<br>
This script requires root privileges to run. `sudo bintelpwr`<br>

Examples:<br>
`bintelpwr` : Run script with default values.<br>
`bintelpwr -t 4` : Run script and refresh every 4 seconds.<br>

<pre>
Options:
  -h, --help    Display this help message
  -t, --time    Specify refresh interval in seconds
  -v, --version Display script version
</pre>

---

### Installation

Normal install will install scripts to `/usr/bin` and requires root.<br>
Local install will install scripts to `~/bin`.<br>

Run `make install` to install `bintelpwr`.<br>
Run `make uninstall` to uninstall `bintelpwr`.<br>

Run `make install-local` to install `bintelpwr` locally for current user.<br>
Run `make uninstall-local` to uninstall `bintelpwr` locally for current user.<br>

---
### Screenshots

![Alt text](/screenshots/bintelpwr.png?raw=true "bintelpwr")
