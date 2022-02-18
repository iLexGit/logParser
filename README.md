# Attack log parser

## How to run
`python attack_interpreter [JSON_ATTACKS_LOG]`

## Menu functions
	1. Show Attackers
	2. Show Attack from IP
	e. Exit

| **OPTION** | **ACTION** |
| :--- | ---: |
| *Show Attackers* | lists attacks source IP with the amount of attacks each one performed |
| *Show Attack from IP* | asks for IP and lists all attacks performed with logs, timestamps and severity levels |

## TODO
- [ ] Consider migrating to *Golang* (defo faster)
- [x] Beautify log output
- [ ] Sort attackers array (make sure its fastest)
- [ ] Add functionality to read and parse regular (non-attack) logs
- [ ] Allow RegEx testing
- [ ] Ask if output to file rather than work on CLI
- [ ] Add more stats
- [ ] Replace menu with flag options and implement *-h*
