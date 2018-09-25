# Getting started with the (recent) LLVM C API

See the [accompanying blog post][4]. Props to Paul Smith for the original [blog post][3] and [repo][2]!

Tested with [LLVM 7.0.0][1] on macOS 10.13.6 (High Sierra).

To use, download and install LLVM. On macOS, using brew, simply

`brew install llvm`

on other platforms you may need to build from source.

Once LLVM is installed, clone this repo, cd to it, and run:

    $ make
    $ ./sum 42 99
    141

[1]: http://releases.llvm.org/download.html#7.0.0
[2]: https://github.com/paulsmith/getting-started-llvm-c-api
[3]: https://pauladamsmith.com/blog/2015/01/how-to-get-started-with-llvm-c-api.html
[4]: https://www.owenstephens.co.uk/blog/2018/09/25/getting-started-with-the-newer-llvm-c-api.html
