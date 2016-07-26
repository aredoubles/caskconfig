caskConfig
==========

Were I ever to receive a fresh new Mac, here's a bulk approach to installing apps using [Homebrew Cask](http://caskroom.io/). 

## Usage
The lore of the land recommends that you clone to your profile root, i.e. ``~/``, but I prefer ``~/Applications/``. Chances are you'll only use this once - when you're setting up your new rig. After that, feel free to delete it. 

Before you get started, make sure you have [Brew](http://brew.sh/) and [Cask](http://caskroom.io/) on your system (in that order). That involves two lines in the Terminal:

```ruby -e "$(curl -fsSL "https://raw.githubusercontent.com/Homebrew/install/master/install)"``` 
for Homebrew, and 

``brew tap caskroom/cask`` for Cask.

Then run
```shell
~/Applications/.caskconfig.sh
```
and grab a coffee. Cask installs all the applications for you. Of course, you'll need an internet connection, but since you're looking at this on Github...

If for some reason the code above doesn't work, it's not your fault - it's just computers being weird. Try this:
```shell
sh ~/Applications/.caskconfig.sh
```
and it should send you on your way.

Do also check out the [Lifehacker write-up](http://lifehacker.com/how-to-make-your-own-bulk-app-installer-for-os-x-1586252163), including the comments(!), which are actually quite helpful(!!).

## Bug Tracking and Feature Requests

Have a bug or a feature request? [Please open a new issue](https://github.com/kenlimmj/caskconfig/issues).

Before opening any issue, please search for existing issues and read the [Issue Guidelines](https://github.com/necolas/issue-guidelines), written by [Nicolas Gallagher](https://github.com/necolas/).

NB: I'll be damned (and crazy ashamed) if there's bugs in code like this.

## Contributing

Please submit all pull requests against *-wip branches. PRs should really be for things that improve functionality in a system agnostic manner. If you'd just like to add programs and applications that work for you, fork away! Of course, if there's something everyone should absolutely use (e.g. a QL plugin which works for everyone), I'd be glad to add it in.

## Author

Thanks to the original author from which I forked most of this:

**Kenneth Lim**
+ http://kenlimmj.com
+ http://twitter.com/kenlimmj
+ http://github.com/kenlimmj

## Copyright and License
_I mean look, all I did was just cobble lines of shell commands together. It's convenient and it works, but that's really all there is to it, so feel free to do whatever you please with it ya?_

This is free and unencumbered software released into the public domain.

Anyone is free to copy, modify, publish, use, compile, sell, or
distribute this software, either in source code form or as a compiled
binary, for any purpose, commercial or non-commercial, and by any
means.

In jurisdictions that recognize copyright laws, the author or authors
of this software dedicate any and all copyright interest in the
software to the public domain. We make this dedication for the benefit
of the public at large and to the detriment of our heirs and
successors. We intend this dedication to be an overt act of
relinquishment in perpetuity of all present and future rights to this
software under copyright law.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT.
IN NO EVENT SHALL THE AUTHORS BE LIABLE FOR ANY CLAIM, DAMAGES OR
OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE,
ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR
OTHER DEALINGS IN THE SOFTWARE.

For more information, please refer to <http://unlicense.org>
