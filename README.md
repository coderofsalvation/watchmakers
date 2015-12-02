![Build Status](https://travis-ci.org/coderofsalvation/watchmakers.svg?branch=master)

## Usage



    $ watchmakers '/foo/bar/src:make' '/foo/bar/node_modules/flop:npm run-script compile'

                    _/_    /                /            
         , , , __.  /  _. /_  ______  __.  /_  _  __  _  
        (_(_/_(_/|_<__(__/ /_/ / / <_(_/|_/ <_</_/ (_/_)_
                                                         
        -> Press Ctrl+\\ to force build, Ctrl+C to exit.
        -> watching ""
    
    
        watching '/foo/bar/src'
        watching '/foo/bar/node_modules/flop'

        ʕ • x • ʔ
        change detected!
    + cd /foo/bar/node_modules/flop
    + npm run-script compile

        ʕ • x • ʔ

## Features

In contrast to most 'watch' utilities, this bashscript allows:

* watching multiple dirs 
* directory related build command 
* adorable animation
