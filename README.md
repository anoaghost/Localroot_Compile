# Localroot Exploit

This repository is a place where [Localroot](./) has been compiled and tested.


***
### Linux Kernel Exploit with Compile
#### #CVE　　#Description　　#Kernels 

- [Linux kernel XFRM Subsystem UAF](./XFM-PoC)  [3.x - 5.x kernels]  (Ubuntu 14.04 / 16.04 Server 4.4 LTS kernels, CentOS 8 4.18 kernels, Red Hat Enterprise Linux 4 4.18 kernels, Ubuntu 18.04 Server LTS 4.15 kernels)

- [CVE-2020-7247](./2020/CVE-2020-7247)  [root66 OpenBSD 6.6 OpenSMTPD 6.6 local root exploit.]  [OpenSMTPD 6.6, as used in OpenBSD 6.6 and other products, allows remote attackers to execute arbitrary commands as root via a crafted MAIL FROM address.]

- [CVE-2019-19726](./2019/CVE-2019-19726)  [OpenBSD-dynamic-loader-chpass OpenBSD local root exploit]  (OpenBSD through 6.6 allows local users to escalate to root because a check for LD_LIBRARY_PATH in setuid programs can be defeated by setting a very small RLIMIT_DATA resource limit. When executing chpass or passwd (which are setuid root), _dl_setup_env in ld.so tries to strip LD_LIBRARY_PATH from the environment, but fails when it cannot allocate memory. Thus, the attacker is able to execute their own library code as root.)

- [CVE-2019-19520](./2019/CVE-2019-19520)  [OpenBSD-authroot OpenBSD local root exploit.]
(xlock in OpenBSD 6.6 allows local users to gain the privileges of the auth group by providing a LIBGL_DRIVERS_PATH environment variable, because xenocara/lib/mesa/src/loader/loader.c mishandles dlopen. OpenBSD 6.6, in a non-default configuration where S/Key or YubiKey authentication is enabled, allows local users to become root by leveraging membership in the auth group. This occurs because root's file can be written to /etc/skey or /var/db/yubikey, and need not be owned by root.)

- [CVE-2019-13272](./2019/CVE-2019/13272)  [Linux 4.10 < 5.1.17 PTRACE_TRACEME]
(Ubuntu 16.04.5, Debian 9.4.0, Parrot OS 4.5.1, ElementaryOS 0.4.1, etc)

- [CVE-2019-12181](./2019/CVE-2019-12181)  [Serv-U FTP Server]
(FTP Server versions prior to 15.1.7)

- [CVE-2019-7304](./2019/CVE-2019-7304)  [Canonical snapd before version 2.37.1 incorrectly performed socket owner validation]
(Ubuntu 14.04, 16.04, 18.04, 18.10)

- [CVE-2018-1000001](./2018/CVE-2018-1000001/)  [glibc]
(glibc <= 2.26)

- [CVE-2018-16323[(./2018/CVE-2018-16323)  [ReadXBMImage in coders/xbm.c in ImageMagick]
(Ubuntu 14.04, 16.04, 18.04)

- [CVE-2018-14665](./2018/CVE-2018-14665)  [xorg-x11-server < 1.20.1]
(RHEL 7.3 && 7.5)

- [CVE-2018-14634](./2018/CVE-2018-14634)  [Integer overflow in Linux's create_elf_tables()]
(Affect kernel versions 2.6.x, 3.10.x and 4.14.x)

- [Windows 10 UAC Bypass](./Windows)  [Windows 10 UAC Bypass by computerDefault]

- [CVE–2018–18955](./2018/)　　[Ubuntu 16.04.4 kernel priv esc]  
(Tested : 4.4.0-116-generic #140-Ubuntu SMP Mon Feb 12 21:23:04 UTC 2018 x86_64) 

- [CVE-2017-1000367](./2017/CVE-2017-1000367)　　[Sudo]
(Sudo 1.8.6p7 - 1.8.20)  

- [CVE-2017-1000112](./2017/CVE-2017-1000112)  [KASLR and SMEP bypass]
( Ubuntu trusty 4.4.0 kernels, Ubuntu xenial 4.4.0 and 4.8.0 kernels, Linux Mint rosa 4.4.0 kernels, Linux Mint sarah 4.8.0 kernels, Zorin OS 12.1 4.4.0-39 kernel)

- [CVE-2017-18344](./2017/CVE-2017-18344)  [KASLR and SMEP bypass]
(Ubuntu xenial 4.4.0-116-generic and 4.13.0-38-generic and on CentOS 7 3.10.0-862.9.1.el7.x86_64)

- [CVE-2017-16995](./2017/CVE-2017-16995)　　[Memory corruption caused by BPF verifier] 
(Linux kernel before 4.14 - 4.4)

- [CVE-2017-11176](./2017/CVE-2017-11176)  [mq_notify: double sock_put()]

- [CVE-2017-7308](./2017/CVE-2017-7308)　　[a signedness issue in AF\_PACKET sockets]  
(Linux kernel through 4.10.6)  

- [CVE-2017-6074](./2017/CVE-2017-6074)　　[a double-free in DCCP protocol]  
(Linux kernel through 4.9.11)  

- [CVE-2016-9793](./2016/CVE-2016-9793)　　[a signedness issue with SO\_SNDBUFFORCE and SO\_RCVBUFFORCE socket options]  
(Linux kernel before 4.8.14)  

- [CVE-2016-8655](./2016/CVE-2016-8655)  [linux AF_PACKET race condition exploit]
(For Ubuntu 14.04 / 16.04 (x86_64) kernels 4.4.0 before 4.4.0-53.74)

- [CVE-2016-5195](./2016/CVE-2016-5195)　　[Dirty cow]  
(Linux kernel>2.6.22 (released in 2007))  

- [CVE-2015-1328](./2015/CVE-2015-1328)　　[overlayfs]  
(3.13, 3.16.0, 3.19.0)  

- [CVE-2014-4699](./2014/CVE-2014-4699/)　　[ptrace]  
(before 3.15.4)  

- [CVE-2014-4014](./2014/CVE-2014-4014/)　　[Local Privilege Escalation]  
(before 3.14.8)  

- [CVE-2014-3153](./2014/CVE-2014-3153/)　　[futex]  
(3.3.5 ,3.3.4 ,3.3.2 ,3.2.13 ,3.2.9 ,3.2.1 ,3.1.8 ,3.0.5 ,3.0.4 ,3.0.2 ,3.0.1 ,2.6.39 ,2.6.38 ,2.6.37 ,2.6.35 ,2.6.34 ,2.6.33 ,2.6.32 ,2.6.9 ,2.6.8 ,2.6.7 ,2.6.6 ,2.6.5 ,2.6.4 ,3.2.2 ,3.0.18 ,3.0 ,2.6.8.1)  

- [CVE-2014-0196](./2014/CVE-2014-0196/)　　[rawmodePTY]  
(2.6.31, 2.6.32, 2.6.33, 2.6.34, 2.6.35, 2.6.36, 2.6.37, 2.6.38, 2.6.39, 3.14, 3.15)  

- [CVE-2014-0038](./2014/CVE-2014-0038/)　　[timeoutpwn]  
(3.4, 3.5, 3.6, 3.7, 3.8, 3.8.9, 3.9, 3.10, 3.11, 3.12, 3.13, 3.4.0, 3.5.0, 3.6.0, 3.7.0, 3.8.0, 3.8.5, 3.8.6, 3.8.9, 3.9.0, 3.9.6, 3.10.0, 3.10.6, 3.11.0, 3.12.0, 3.13.0, 3.13.1)  

- [CVE-2013-2171](./2013/CVE-2013-2171/)  [nmap/ptrace exploit]
(FreeBSD 9.1]

- [CVE-2013-2094](./2013/CVE-2013-2094/)  [perf_swevent_init]
(Ubuntu 12.04.0 > 12.04.2)

- [CVE-2013-1763](./2013/CVE-2013-1763/)  [Array index error in the __sock_diag_rcv_msg function in net/core/sock_diag.c]
(3.3 - 3.7 arch)

- [CVE-2012-0217](./2012/CVE-2012-0217/)  [Intel SYSRET]
(FreeBSD 9.0)

- [CVE-2011-4862](./2011/CVE-2011-4862/)  [Buffer overflow in libtelnet/encrypt.c]
(FreeBSD 7.3 > 9.0)

## Disclaimer
Any actions and or activities related to the material contained within this [tools](./) is solely your responsibility. The misuse of the information in this [tools](./) can result in criminal charges brought against the persons in question.

***

### ***Contact me***
***Website*** : [Valeiriya.osaka](https://github.valeiriya.osaka/)

***Twitter*** : [AnoaGhost](https://twitter.com/AnoaGhost)
###
