# Findings Report

## Objective

To perform service enumeration on an authorized target using Nmap and identify exposed services and network information.

## Target

* Host: scanme.nmap.org
* IP Address: 45.33.32.156

## Command Used

```bash
nmap -sV scanme.nmap.org
```

## Results

| Port  | State | Service    | Details                    |
| ----- | ----- | ---------- | -------------------------- |
| 22    | Open  | SSH        | OpenSSH 6.6.1p1            |
| 80    | Open  | HTTP       | Apache 2.4.7               |
| 9929  | Open  | Nping Echo | Testing service            |
| 31337 | Open  | tcpwrapped | Service information hidden |

## Observations

* The target host was online and reachable.
* SSH service was exposed on port 22.
* Apache web server was running on port 80.
* Multiple ports were filtered by firewall rules.
* The server revealed limited service information, reducing unnecessary exposure.

## Security Notes

* Open SSH services should be secured with strong authentication.
* Public web services should be regularly updated and monitored.
* Firewall filtering helps reduce the attack surface.

## Conclusion

The Nmap scan successfully identified open ports and running services on the target system. The assessment demonstrated basic network reconnaissance and service enumeration techniques used in cybersecurity.
