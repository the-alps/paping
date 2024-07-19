#Command line options

    paping v1.5.5 r1 - Copyright (c) 2024 Mike Lovell
    
    Syntax: paping [options] destination
    
    Options:
     -?, --help     display usage
     -p, --port N   set TCP port N (required)
         --nocolor  Disable color output
     -t, --timeout  timeout in milliseconds (default 1000)
     -c, --count N  set number of checks to N
         --ip-bind  set source ip address
         --break    once connected

#Example usage

    C:\> paping www.google.com -p 80 -c 4
    
    paping v1.5.1 - Copyright (c) 2010 Mike Lovell
    
    Connecting to www.l.google.com [209.85.225.147] on TCP 80:
    
    Connected to 209.85.225.147: time=24.00ms protocol=TCP port=80
    Connected to 209.85.225.147: time=25.00ms protocol=TCP port=80
    Connected to 209.85.225.147: time=24.00ms protocol=TCP port=80
    Connected to 209.85.225.147: time=24.00ms protocol=TCP port=80
    
    Connection statistics:
            Attempted = 4, Connected = 4, Failed = 0 (0.00%)
    Approximate connection times:
            Minimum = 24.00ms, Maximum = 25.00ms, Average = 24.25ms
