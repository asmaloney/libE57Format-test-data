# libE57Format Test Data

This repository contains test files for libE57Format.

Because the number of files and size of the data can grow quickly, the test data is kept here instead of in the main repository. If ends up being too big for a git repo we might have to switch and make it available as a zip download somewhere.

For details on how to use this, please see the [README](https://github.com/asmaloney/libE57Format/blob/master/test/README.md) in the test directory of the libE57Format repository.

## Files

### 3rdParty

These E57 files were generated by other tools and are used for testing reading.

### images

These are images used to test writing E57 files containing Image2D.

### self

These E57 files were generated by libE57Format itself and are used for testing reading.

### reference

These E57 files come from the [E57 Example/Test Data](http://www.libe57.org/data.html) site.

## Licensing

The files in the **reference** directory don't require any special license handling since they are in binary form, however here is the license (which is a slightly modified [MIT](https://opensource.org/licenses/MIT) license to apply to data) from the site:

```
Test Data License
Permission is hereby granted, free of charge, to any person or organization obtaining a copy of the test data (the "Test Data") to use, reproduce, display, distribute, publish, and transmit the Test Data, and to copy and reformat this Test Data, and to permit third-parties to whom the Test Data is furnished to do so, all subject to the following:

The copyright notices of the Test Data must be included in all copies of the Test Data, unless such copies are solely in the binary file form.

THE TEST DATA IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE, TITLE AND NON-INFRINGEMENT. IN NO EVENT SHALL THE COPYRIGHT HOLDERS OR ANYONE DISTRIBUTING THE TEST DATA BE LIABLE FOR ANY DAMAGES OR OTHER LIABILITY, WHETHER IN CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE TEST DATA OR THE USE OR OTHER DEALINGS IN THE TEST DATA.
```

All other files are licensed under the [CC0 1.0 Universal Public Domain Dedication](https://creativecommons.org/publicdomain/zero/1.0/).
