# echoserver
## A TCP Echo Server

Please see the related blog post at:

https://jiml.us/blog/posts/goecho/

The only command-line parameter echoserver expects is -p which allows the user to specify the port where the code will listen.

echoserver

    echoserver v 0.95 by Jim Lawless
    Syntax:
            echoserver [flags]
    where flags are:
      -p="": port

echoserver -p 4023

    echoserver v 0.95 by Jim Lawless
    
    Port: 4023
    Listening...

In another console/terminal session, we can telnet to this echo server via localhost.

telnet localhost 4023
    
    Enter the word 'quit' (with no quotes) to exit.

hello

    You said: hello
    Enter the word 'quit' (with no quotes) to exit.

goodbye

    You said: goodbye
    Enter the word 'quit' (with no quotes) to exit.
