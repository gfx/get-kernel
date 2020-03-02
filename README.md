# get-kernel

A utility command to download Linux kernel packages.

## Usage

```console
$ mkdir kernel-4.19.106 # working dir
$ cd kernel-4.19.106
$ get-kernel 4.19.106
# download *.deb to the working dir
$ sudo dpkg -i *.deb
$ sudo update-grub && sudo reboot

# after re-login
$ uname --kernel-release
4.19.106-0419106-generic
```

## Supported Distributions

* Ubuntu
    * https://kernel.ubuntu.com/~kernel-ppa/mainline/


## Copyright

Copyright 2020, FUJI Goro.

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.


