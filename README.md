 # zmgo
Pure ZMTP implementation in Go, without idiosyncracies of ZMQ like no thread safety

NOTE:- Pre-Alpha software, do not use. May take months to get a working prototype.

Goals
- ZMTP compatability
- sockets are not thread safe in zmgo *yet*
- send and receive are thread safe on same socket
- shall support both ZMTP 3.0 and ZMTP 2.0 
- buffer reuse using sync Pools and custom cache pools for better performance
- no goroutines are launched in hotpath
- support for ZMQ events shall be added 
- support shall start with ZMTP 3.0

