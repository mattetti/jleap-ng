jleap-ng
========

A JRuby library for working with the Leap Motion.

You can learn about the Leap Motion at [www.leapmotion.com](https://www.leapmotion.com/).

This code is a work-in-progress, evolving as needed.

Details about this and other Leap Motion hacking efforts will be documented at [Leap Hacking](http://leaphacking.com)


Getting Started
=====

1. Set/export the `LEAP_SDK_HOME` environment variable to point to the
   place where you have the leap SDK.

On Linux/OS X: 
```
$ export LEAP_SDK_HOME='/opt/Leap_SDK'
```

2. Install [JRuby](http://jruby.org/) and add its bin folder to your
   path.

On Linux/OS X:
```
$ export PATH=$PATH:/opt/jruby/bin:
```

3. Execute the demo using JRuby and adding the Leap SDK to Java's path:

On Linux/OS X:
```
$ jruby -J-Djava.library.path=$LEAP_SDK_HOME/lib jruby-example.rb
```

Windows users might want to wrap the secret sauce in a `.bat` file:

```
jruby -J-Djava.library.path=%LEAP_SDK_HOME%\lib\x64 %1
```

And use the wrapper to start the example file:

```
_runJrubyDemo.bat jruby-example.rb
```


Author
------

James Britt <james@neurogami.com>


License
-------

The MIT License


Copyright (c) 2013 James Britt / Neurogami

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
'Software'), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED 'AS IS', WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY
CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT,
TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE
SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.

Feed your head

Hack your world

Live curious

