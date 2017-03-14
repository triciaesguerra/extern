### BSD Socket
- reuse port vs reuse address

http://stackoverflow.com/questions/14388706/socket-options-so-reuseaddr-and-so-reuseport-how-do-they-differ-do-they-mean-t

- blocking vs unblocking

http://stackoverflow.com/questions/10654286/why-should-i-use-non-blocking-or-blocking-sockets

http://www.beej.us/guide/bgnet/output/html/multipage/advanced.html#blocking

https://www.scottklement.com/rpg/socktut/nonblocking.html

### IPv4 - IPv6 coexistence
http://www.cisco.com/c/en/us/products/collateral/ios-nx-os-software/enterprise-ipv6-solution/white_paper_c11-676278.html

http://www-01.ibm.com/support/docview.wss?uid=swg27035680&aid=1

### BSD vs POSIX
__Berkeley Sockets__ . Sockets uses the BSD interface that was developed by BBN for the TCP/IP protocol suite under DARPA contract on 4.1aBSD and released in 4.2BSD. BSD Sockets provides a set of primary API functions that are typically implemented as system calls. The BSD Sockets interface is non-standard, operated diﬀerently from the POSIX interface in subtle ways, and is now deprecated in favour of the POSIX/SUS standard Sockets interface.

__POSIX Sockets__ . Sockets were standardized by X/Open, later the OpenGroup, and IEEE in the POSIX standardization process. They appear in XNS 5.2 [XNS99], SUSv1 [SUS95], SUSv2 [SUS98] and SUSv3 [SUS03]. POSIX/SUS Sockets is now the common application environment for accessing networking, deprecating the XTI for TCP/IP networking applications.

