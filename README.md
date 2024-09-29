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
### Screenshots

![Alt text](/screenshots/bintelpwr.png?raw=true "bintelpwr")
