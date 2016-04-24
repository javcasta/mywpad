# myWPAD
- Package for autoconfigure wpad in pfSense.
- myWPAD is a tool for Autoconfigure an ngnix instance at LAN interface ip at port tcp80 like WPAD server.
- Tested in pfSense 2.3 amd64 version.
- Service necceseraly up in pfSense:
  - unbound (DNS Resolver)
  - ngnix
  - A proxy working in pfSense, like squid, or in your local network (lan).
