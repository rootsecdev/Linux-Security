# Linux Security Landing Zone

This is a landing page for linux security.

# Hardening linux Security Guidance

**Ubuntu 18.04 End user Device Guidance**

https://www.ncsc.gov.uk/collection/end-user-device-security/platform-specific-guidance/ubuntu-18-04-lts

**Linux DISA Stigs (Unclassified)**

https://public.cyber.mil/stigs/downloads/?_dl_facet_stigs=operating-systems%2Cunix-linux

**CIS Benchmarks (Registration Required)** PDFs are free to download

https://www.cisecurity.org/cis-benchmarks/

**Ubuntu 18.04 Server Security Guide**

https://help.ubuntu.com/lts/serverguide/security.html

**Raspberry Pi Security**

https://www.raspberrypi.org/documentation/configuration/security.md

**Cent OS Security**

https://wiki.centos.org/HowTos/OS_Protection

**Open Suse Security**

https://doc.opensuse.org/documentation/leap/security/html/book.security/index.html

**Debian Security**

https://www.debian.org/doc/manuals/securing-debian-howto/

**Fedora Security Lab** (This project is useful security auditing, forensics, system rescue and teaching security testing methodologies in universities and other organizations.)

https://labs.fedoraproject.org/en/security/

# Penetration Testing

**Kali Linux**

https://www.kali.org/downloads/

**Parrot Security**

https://www.parrotlinux.org/download-security.php

**Black Arch Linux**

https://blackarch.org/downloads.html

**Network Security Toolkit**

https://sourceforge.net/projects/nst/files/NST/NST%2030-11210/

**BackBox Linux**

https://www.backbox.org/download/



# Privacy Focuses OS's

**Tails**

https://tails.boum.org/install/dvd-download/index.en.html

**Linux Kodachi**

https://www.digi77.com/linux-kodachi/

**WhoNix**

https://www.whonix.org/download/

**Qubes OS** (Requires Dedicated Workstation. Do not run this in a VM)

https://www.qubes-os.org/downloads/

# OS's for sensitive data handling

Very small list of Linux OS's I've used for sensitive data handling. 

**Trusted End Node Security**

This is a DOD MIL distribution. I use this distro to access sensitive intelligence community sites. This DOD site uses its own internal root ca. So you will get errors about the encrypted website being unsecure. Make sure to use the Encrypt DNS application before accessing sensitive material. 

https://www.spi.dod.mil/download.htm

**Discrete Linux**

Use this distro with caution. It has not been updated since 2016. Its meant for airgapped network testing and accessing sensitive data. Its an interesting project but not really maintained. I do find it noteworthy for what it does. 

https://www.privacy-cd.org/index.html

# NSA privacy focuses disclosures

I won't be linking NSA's slide decks of PRISM but you can find it on your own. This is just an interesting website of alternatives to closed source software.

**Prism Break**

https://prism-break.org/en/

# Linux Security Toolkits

**USB Guard**

https://usbguard.github.io/

**USB Keystroke Injection Protection**

https://github.com/google/ukip

# Red Hat 8 Security notes

**Depreciated functionality**

https://access.redhat.com/documentation/en-us/red_hat_enterprise_linux/8/html/8.0_release_notes/rhel-8_0_0_release#deprecated_functionality

Security Notes to depreciated functionality:

- The Digital Signature Algorithm (DSA) is considered deprecated in Red Hat Enterprise Linux 8.
- SSL2 Client Hello has been deprecated in NSS
- TLS 1.0 and TLS 1.1 are deprecated

**Strong crypto defaults in RHEL 8 and deprecation of weak crypto algorithms**

https://access.redhat.com/articles/3642912

| Policy Name   | Description |
| ------------- | ------------- |
| LEGACY | This policy ensures maximum compatibility with legacy systems; it is less secure and it includes support for TLS 1.0, TLS 1.1, and SSH2 protocols or later. The algorithms DSA, 3DES, and RC4 are allowed, while RSA and Diffie-Hellman parameters are accepted if larger than 1023-bits.  |
| FUTURE  | The DEFAULT policy is a reasonable default policy for today's standards, aimed for a balance between usability and security. It allows the TLS 1.2 and 1.3 protocols, as well as IKEv2 and SSH2. The RSA and Diffie-Hellman parameters are accepted if larger than 2047-bits.  |
| FIPS  | Content Cell  |
