# Bettercap_error


#(root㉿futzjger)-[~]
#└─# bettercap         
#bettercap v2.32.0 (built for linux amd64 with go1.21.0) [type 'help' for a list of commands]

#panic: runtime error: index out of range [0] with length 0
 #       panic: runtime error: invalid memory address or nil pointer dereference
#[signal SIGSEGV: segmentation violation code=0x1 addr=0x30 pc=0xd4d846]

#goroutine 1 [running]:
#github.com/bettercap/bettercap/session.(*Session).Close(0xc000130a80)
#        /build/bettercap-StA1LY/bettercap-2.32.0+git20230725/session/session.go:190 +0x126
#panic({0x1190380?, 0xc00063cae0?})
#        /usr/lib/go-1.21/src/runtime/panic.go:914 +0x21f
#github.com/bettercap/bettercap/routing.update()
 #       /build/bettercap-StA1LY/bettercap-2.32.0+git20230725/routing/update_linux.go:40 +0x606
#github.com/bettercap/bettercap/routing.Update()
 #       /build/bettercap-StA1LY/bettercap-2.32.0+git20230725/routing/tables.go:19 +0x71
#github.com/bettercap/bettercap/routing.Gateway({0x11f732c, 0x4}, {0xc000724ee2, 0x5})
 #       /build/bettercap-StA1LY/bettercap-2.32.0+git20230725/routing/tables.go:23 +0x5a
#github.com/bettercap/bettercap/network.FindGateway(0xc000628f00)
#        /build/bettercap-StA1LY/bettercap-2.32.0+git20230725/network/net_gateway.go:10 +0x36
#github.com/bettercap/bettercap/session.(*Session).Start(0xc000130a80)
 #       /build/bettercap-StA1LY/bettercap-2.32.0+git20230725/session/session.go:254 +0x2b4
#main.main()
 #       /build/bettercap-StA1LY/bettercap-2.32.0+git20230725/main.go:49 +0x43f
                                                                             
