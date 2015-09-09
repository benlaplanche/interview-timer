# Ticker example app

This application emits a message to Stdout & Stderr every 1 second. 

# Running

To run this locally, assuming you have golang installed
`go run main.go`

Alternatively you can run the binary relevant to your operating system in the `builds` folder.

OSX `builds/timer-osx`
Ubunutu64 `builds/timer-linux`

To run this on bosh-lite use `builds/timer-linux`

You will see output like this
```
Ticker starting
Hello world from 2015-09-09 10:06:43.002174084 +0100 BST
ERROR at 2015-09-09 10:06:43.002174084 +0100 BST
```