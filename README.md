Welcome to Foundation Core
=====================

This is fork of zurb/foundation, the original can be found at https://github.com/zurb/foundation. The original license is included and all credit goes to the original authors.

So why the fork? Zurb foundation doesn't provide an easy way to download just the SASS files without using a package manager. When the rails plugin wasn't loading it's assets correctly I was left with two choices. Trace through the code to solve the issue and submit a pull request to get it into the master branch or bring in the assets by hand to known good locations.

While it would have been better for the community as a whole if I had fixed the rails gem, I did need the quick solution. There have also been quite a few times when I was developing a static site that didn't need any the heaviness of a framework (and just for development) I would include a javascript SASS compiler, and a javascript coffee-script compiler.

I will probably be switching over to one of the LESS versions of Foundation later as it is in my humble opinion, far superior than SASS. If you use this repository beware that it will probably not be maintained.

MIT Open Source License
=======================

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
