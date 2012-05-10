# Textmate Bundle for Node.JS

## Common commands and short-cuts

Important: Change your current grammar to "JavaScript Node" (short cut: Shift+Ctrl+Alt+N)

* Cmd+R - run current file within node
* req => var util = require('util');
* exp => exports.func_name = function() {...};
* process snippets
  * .lis - .addListener(...)
  * .cb - .addCallback(...)
  * .errb - .addErrback(...)
  * .canb - .addCancalback(...)
* sys module:
  * puts - sys.puts('string');
  * p - sys.p('string');
  * debug - sys.debug('string');
  * error - sys.error('string');
  * exec - sys.exec('command').addCallback(...);
* posix module:
  * cat, mkdir, readdir, rename, rmdir, stat

Others:

* app => if (module.id == require.main.id) { .. }
* cons => console.log('');
* fun => function function_name(argument) {	// body...}
* set => setTimeout(function, n);

## Installation

    mkdir -p ~/Library/Application\ Support/TextMate/Bundles/
    cd ~/Library/Application\ Support/TextMate/Bundles
    git clone git://github.com/drnic/javascript-node.tmbundle.git "JavaScript Node.tmbundle"
    osascript -e 'tell app "TextMate" to reload bundles'

Alternately, in TextMate, from your drop down menu, select Bundles -> Bundle Editor -> Reload Bundles.

## Credits

The Node.JS TM Bundle is currently authored by Dr Nic Williams. Contributors and co-maintainers are welcome.

* **Dr Nic** - Author/Main contributor
* **Jasper Lievisse Adriaanse** - Contributor

## License

Copyright (c) 2009-2010 Dr Nic Williams, Mocra
Copyright (c) 2012 Jasper Lievisse Adriaanse

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
