## Socksify patch

This repo contains a dirty patch on the original Socksify to not interfere with the TCPSocket class. It provides a TCPSOCKSSocket which you can use whenever you need to pass traffic through the SOCKS5 proxy leaving all other traffic unaffected.
