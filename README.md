# Pale Moon web browser

This is the source code for the Pale Moon web browser, an independent browser derived from Firefox/Mozilla community code. The source tree is laid out in a "comm-central" style configuration where only the code specific to Pale Moon is kept in this repository.

As of September 14, 2021, the Pale Moon source code has been converted to a Snapshot release style. Please see http://archive.palemoon.org/source/ for the latest official releases of the source contained in this repository.

The shared Unified XUL Platform source code is referenced here as a git submodule contained in the `platform/` directory and is required to build the application.

## Getting the platform sub-module
`git submodule init && git submodule update`

## Licensing
Most of the source code in this repository is available under the Mozilla Public License 2.0 (MPL). The MPL has a [FAQ](http://www.mozilla.org/MPL/2.0/FAQ.html) to help you understand it. The remainder of the software which is not under the MPL is available under one of a variety of other free and open source licenses.

Please see the file [[UXP]/toolkit/content/license.html](https://github.com/RealityRipple/UXP/blob/master/toolkit/content/license.html) for the copyright licensing conditions attached to this codebase, including copies of the licenses concerned.

You are not granted rights or licenses to the trademarks of Moonchild Productions or any other party, including without limitation the Pale Moon or Basilisk names or logos.

For more information, see [Licensing](https://www.palemoon.org/licensing.shtml) and [Redistribution](https://www.palemoon.org/redist.shtml) on the Pale Moon website.

## Resources

 * [Build Pale Moon for Windows](https://developer.palemoon.org/build/windows/)
 * [Build Pale Moon for Linux](https://developer.palemoon.org/build/linux/)
 * [Pale Moon home page](http://www.palemoon.org/)
 * [Code of Conduct, Contributing, and UXP Coding style](https://repo.palemoon.org/mcp-graveyard/UXP/src/branch/master/docs)
