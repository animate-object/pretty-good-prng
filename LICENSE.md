# License and Attribution

This project includes components derived from other sources. Below is a breakdown of their origins, licensing status, and modifications:

## Included Component

1. **KISS07 Algorithm** and Mash component
   - Derived from a repository of JavaScript seeded RNG implementations: [PRNG Repository](https://github.com/dworthen/prng).
   - These implementations were in turn derived from Usenet posts by a Professor Marsaglia. 
     - While no explicit license is provided, one post states: "You are welcome to use one or both of the above."
     - It is assumed that Professor Marsaglia did not intend to restrict their use, but these algorithms are not formally in the public domain. See the linked repositories for more info.
   - Per licensure requirements, a copy of that repository's license is here: [LICENSE.md](https://github.com/dworthen/prng/blob/master/LICENSE.md).
   - **Modification**: In this repository, the algorithm implementations have been lightly modernized, and typescript typings have been provided for modern usage.

## License for TypeScript Implementation

The TypeScript implementation of the above algorithm in this repository is licensed under the MIT License:

---

Copyright (C) [Your Name or Repository Name]

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

## Acknowledgments

Special thanks to the OSS community and the original author of the KISS07 algorithm for making their work available and subsequent individuals who packaged that work for convenience. If you are the original author or have concerns about this usage, please contact alexander.f.prinsen@gmail.com (animate-object@github)