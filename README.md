# CL-QRENCODE

QR Code encoder in pure Common Lisp. A somewhat working version for now.

Forked from: https://github.com/jnjcc/cl-qrencode

#### Usage


```lisp

* (cl-qrencode:qrencode "https://github.com/thephoeron/cl-qrencode" :fpng "github-qr.png")
Version reset from 1 to 4

png file `github-qr.png' wrote...

```

#### TO-DO (AFAIK)

* ECI mode, FNC1 mode & Mixing modes
* Structured Append Mode
* create directories for output png automatically
* add more image output formats, starting with SVG

