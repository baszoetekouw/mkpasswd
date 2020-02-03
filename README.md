# mkpasswd
This is a simple command line utility to generate password hashes.  It is similar to the mkpasswd utility that is
distributes with `whois`, except that that old mkpassword utility can only generate hashe that are supported by your
local libc.  This is fien on Linux, but on MacOS, you're pretty screwed, unless you feel inclined to use md5.

Therefore, I created this little utility tht uses the excellent [passlib](https://passlib.readthedocs.io/en/stable/)
library.
