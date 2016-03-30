# mywpad
- Package for configure wpad in pfSense.
- Tested in pfSense 2.2.6 amd64 version.
- Service necceseraly up in pfSense:
  - unbound (DNS Resolver)
  - lighttpd or vhosts running for http in tcp80 port.
  - A proxy working in pfSense, like squid, or in your local network (lan).
