Advisories
==========


* [[RISE-2009003] Linux eCryptfs parse_tag_3_packet Encrypted Key Buffer Overflow Vulnerability](https://github.com/risesecurity/advisories/raw/HEAD/RISE-2009003.txt)  
  Heap-based buffer overflow in the parse_tag_3_packet function in fs/ecryptfs/keystore.c in the eCryptfs subsystem in the Linux kernel before 2.6.30.4 allows local users to cause a denial of service (system crash) or possibly gain privileges via vectors involving a crafted eCryptfs file, related to a large encrypted key size in a Tag 3 packet.

* [[RISE-2009002] Linux eCryptfs parse_tag_11_packet Literal Data Buffer Overflow Vulnerability](https://github.com/risesecurity/advisories/raw/HEAD/RISE-2009002.txt)  
  Stack-based buffer overflow in the parse_tag_11_packet function in fs/ecryptfs/keystore.c in the eCryptfs subsystem in the Linux kernel before 2.6.30.4 allows local users to cause a denial of service (system crash) or possibly gain privileges via vectors involving a crafted eCryptfs file, related to not ensuring that the key signature length in a Tag 11 packet is compatible with the key signature buffer size.

* [[RISE-2009001] ToolTalk rpc.ttdbserverd _tt_internal_realpath Buffer Overflow Vulnerability](https://github.com/risesecurity/advisories/raw/HEAD/RISE-2009001.txt)  
  Stack-based buffer overflow in the _tt_internal_realpath function in the ToolTalk library (libtt.a) in IBM AIX 5.2.0, 5.3.0, 5.3.7 through 5.3.10, and 6.1.0 through 6.1.3, when the rpc.ttdbserver daemon is enabled in /etc/inetd.conf, allows remote attackers to execute arbitrary code via a long XDR-encoded ASCII string to remote procedure 15.

* [[RISE-2008001] Sun Solstice AdminSuite sadmind adm_build_path() Buffer Overflow Vulnerability](https://github.com/risesecurity/advisories/raw/HEAD/RISE-2008001.txt)  
  Stack-based buffer overflow in the adm_build_path function in sadmind in Sun Solstice AdminSuite on Solaris 8 and 9 allows remote attackers to execute arbitrary code via a crafted request.

* [[RISE-2007004] Apple Mac OS X 10.4.x Kernel i386_set_ldt() Integer Overflow Vulnerability](https://github.com/risesecurity/advisories/raw/HEAD/RISE-2007004.txt)  
  Integer overflow in the kernel in Apple Mac OS X 10.4 through 10.4.10 allows local users to execute arbitrary code via a large num_sels argument to the i386_set_ldt system call.

* [[RISE-2007003] Firebird Relational Database Multiple Buffer Overflow Vulnerabilities](https://github.com/risesecurity/advisories/raw/HEAD/RISE-2007003.txt)  
  Multiple stack-based buffer overflows in Firebird LI 1.5.3.4870 and 1.5.4.4910, and WI 1.5.3.4870 and 1.5.4.4910, allow remote attackers to execute arbitrary code via (1) a long service attach request on TCP port 3050 to the SVC_attach function or (2) unspecified vectors involving the INET_connect function. Multiple stack-based buffer overflows in Firebird LI 2.0.0.12748 and 2.0.1.12855, and WI 2.0.0.12748 and 2.0.1.12855, allow remote attackers to execute arbitrary code via (1) a long attach request on TCP port 3050 to the isc_attach_database function or (2) a long create request on TCP port 3050 to the isc_create_database function.

* [[RISE-2007002] Borland InterBase Multiple Buffer Overflow Vulnerabilities](https://github.com/risesecurity/advisories/raw/HEAD/RISE-2007002.txt)  
  Multiple stack-based buffer overflows in Borland InterBase LI 8.0.0.53 through 8.1.0.253, and WI 5.1.1.680 through 8.1.0.257, allow remote attackers to execute arbitrary code via (1) a long service attach request on TCP port 3050 to the (a) SVC_attach or (b) INET_connect function, (2) a long create request on TCP port 3050 to the (c) isc_create_database or (d) jrd8_create_database function, (3) a long attach request on TCP port 3050 to the (e) isc_attach_database or (f) PWD_db_aliased function, or unspecified vectors involving the (4) jrd8_attach_database or (5) expand_filename2 function. Stack-based buffer overflow in Borland InterBase LI 8.0.0.53 through 8.1.0.253 on Linux, and possibly unspecified versions on Solaris, allows remote attackers to execute arbitrary code via a long attach request on TCP port 3050 to the open_marker_file function.

* [[RISE-2007001] Apple Mac OS X 10.4.x Kernel shared_region_map_file_np() Memory Corruption](https://github.com/risesecurity/advisories/raw/HEAD/RISE-2007001.txt)  
  The shared_region_map_file_np function in Apple Mac OS X 10.4.8 and earlier kernel allows local users to cause a denial of service (memory corruption) via a large mappingCount value.

* [[RISE-2006002] FreeBSD 5.x Kernel i386_set_ldt() Integer Overflow Vulnerability](https://github.com/risesecurity/advisories/raw/HEAD/RISE-2006002.txt)  
  Integer overflow vulnerability in the i386_set_ldt call in FreeBSD 5.5, and possibly earlier versions down to 5.2, allows local users to cause a denial of service (crash) and possibly execute arbitrary code via unspecified vectors, a different vulnerability than CVE-2006-4178. Integer signedness error in the i386_set_ldt call in FreeBSD 5.5, and possibly earlier versions down to 5.2, allows local users to cause a denial of service (crash) via unspecified arguments that use negative signed integers to cause the bzero function to be called with a large length parameter, a different vulnerability than CVE-2006-4172.

* [[RISE-2006001] X11R6 XKEYBOARD Extension Strcmp() Buffer Overflow Vulnerability](https://github.com/risesecurity/advisories/raw/HEAD/RISE-2006001.txt)  
  Buffer overflow in the Strcmp function in the XKEYBOARD extension in X Window System X11R6.4 and earlier, as used in SCO UnixWare 7.1.3 and Sun Solaris 8 through 10, allows local users to gain privileges via a long _XKB_CHARSET environment variable value.

