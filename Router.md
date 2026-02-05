# Threat: Router

| **Primary threat vector** | **Zero Trust Policy** | **Mitigations to be applied a smart home owner** |
| :---                      | :---:                 |  :---:                                           |
|                           |                       |                                                  |
| Unauthorised connections to open ports | Least privilege | Close unwanted ports on the router such as 21, 22, 25 |
|                           |
| Unauthorised connections to open ports | Authenticaiton before authorisation | Close port 7547  |
|                           |                            |
| Exfiltration of data on common ports such as 443  | context-aware connections | Monitor and close any connections to known malicious clouds via port 443 |
|                           |                              |
| Exploitation via existing vulnerabilities     | Comprehensive visiblity   | Apply vendor supplied patches to router | 
|                           |                               |
