# Node Stream Tail

Stream a log file to a web page for easy log viewing. 

Change filename to your log file name in stream.js.

## Requirements

Node.js v0.4.1 or higher.

## Installation

    git clone https://github.com/zpoley/node_stream_tail.git  

## Configuration

    Change logfilename in stream.js to the log you'd like to tail on your machine.

## Run

    node server.js /path/to/file.log PORTNUM

### Example
    
    node server.js /var/log/mail.log 8082
    node server.js /var/log/xapp.log 8083

## To see your log on browser

    visit (http://localhost:8082)

## Thanks

this project respectfully uses code from and thanks the authors of:

* [node](http://github.com/ry/node) 
