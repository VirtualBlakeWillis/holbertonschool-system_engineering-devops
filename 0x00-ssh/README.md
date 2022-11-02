# Project: 0x00. SSH

## Background Context
Along with this project, you have been attributed an Ubuntu server, living in a datacenter far far away. Like level 2 of the application process, you will connect using ssh. But contrary to level 2, you will not connect using a password but an RSA key. We’ve configured your server with the public key you created in the first task of a previous project shared in your intranet profile.

You can access your server information in the my servers section of the intranet, each line with contains the IP and username you should use to connect via ssh.

Note: Your server is configured with an Ubuntu 20.04 LTS environment.

## Resources
### Read or watch:

[What is a (physical) server - text](https://intranet.hbtn.io/rltoken/VRAE-34h4_XZb_jIr8Nhbg)

[What is a (physical) server - video](https://intranet.hbtn.io/rltoken/IF05wnDnr7x4LEJv-KrA_A)

[SSH essentials](https://intranet.hbtn.io/rltoken/IXczvoV_MkFSOHdl1CTLow)

[SSH Config File](https://intranet.hbtn.io/rltoken/ko-9_nO1k12ZADYoQYVRLQ)

[Public Key Authentication for SSH](https://intranet.hbtn.io/rltoken/GwL7jXYatdNyNQxfA32__w)

[How Secure Shell Works](https://intranet.hbtn.io/rltoken/UDheSgelrwS_QktHtnZLuw)

[SSH Crash Course](https://intranet.hbtn.io/rltoken/xO8ZTeXG7VnB7yiOTYYiWg) (Long, but highly informative. Watch this if configuring SSH is still confusing. It may be helpful to watch at x1.25 speed or above.)

### For reference:

[Understanding the SSH Encryption and Connection Process](https://intranet.hbtn.io/rltoken/mxnZ56_t7Aprkb4yPOUDUA)

[Secure Shell Wiki](https://intranet.hbtn.io/rltoken/zFcyWlCewyuE4NV2jNBX4w)

[IETF RFC 4251 (Description of the SSH Protocol)](https://www.ietf.org/rfc/rfc4251.txt)

[Internet Engineering Task Force](https://intranet.hbtn.io/rltoken/TaNf82vHEKoUYEdv7DnPLw)

[Request for Comments](https://intranet.hbtn.io/rltoken/PfnK5NbZIlm9h9f86mfTkQ)

### man or help:

- ssh
- ssh-keygen
- env

## Learning Objectives
#### At the end of this project, you are expected to be able to explain to anyone, without the help of Google:

### General
- What is a server
- Where servers usually live
- What is SSH
- How to create an SSH RSA key pair
- How to connect to a remote host using an SSH RSA key pair
- The advantage of using #!/usr/bin/env bash instead of /bin/bash
## Requirements
### General
- Allowed editors: vi, vim, emacs
- All your files will be interpreted on Ubuntu 20.04 LTS
- All your files should end with a new line
- A README.md file, at the root of the folder of the project, is mandatory
- All your Bash script files must be executable
- The first line of all your Bash scripts should be exactly #!/usr/bin/env bash
- The second line of all your Bash scripts should be a comment explaining what is the script doing