Bitcoin Silver Core integration/staging tree
=====================================

[![Build Status](https://travis-ci.org/bitcoinsilver/bitcoinsilver.svg?branch=master)](https://travis-ci.org/bitcoinsilver/bitcoinsilver)

https://bitcoinsilvercore.org

What is Bitcoin Silver?
------------------------

Bitcoin Silver is an experimental digital currency that enables instant payments to
anyone, anywhere in the world. Bitcoin Silver uses peer-to-peer technology to operate
with no central authority: managing transactions and issuing money are carried
out collectively by the network. Bitcoin Silver Core is the name of open source
software which enables the use of this currency.

For more information, as well as an immediately useable, binary version of
the Bitcoin Silver Core software, see https://bitcoinsilvercore.org/en/download/, or read the
[original whitepaper](https://bitcoinsilvercore.org/bitcoinsilver.pdf).

License
-------

Bitcoin Silver Core is released under the terms of the MIT license. See [COPYING](COPYING) for more
information or see https://opensource.org/licenses/MIT.

Development Process
-------------------

The `master` branch is regularly built and tested, but is not guaranteed to be
completely stable. [Tags](https://github.com/bitcoin/bitcoin/tags) are created
regularly to indicate new official, stable release versions of Bitcoin Core.

The contribution workflow is described in [CONTRIBUTING.md](CONTRIBUTING.md)
and useful hints for developers can be found in [doc/developer-notes.md](doc/developer-notes.md).

Testing
------------

Testing and code review is the bottleneck for development; we get more pull
requests than we can review and test on short notice. Please be patient and help out by testing
other people's pull requests, and remember this is a security-critical project where any mistake might cost people
lots of money.

### Automated Testing

Developers are strongly encouraged to write [unit tests](src/test/README.md) for new code, and to
submit new unit tests for old code. Unit tests can be compiled and run
(assuming they weren't disabled in configure) with: `make check`. Further details on running
and extending unit tests can be found in [/src/test/README.md](/src/test/README.md).

There are also [regression and integration tests](/test), written
in Python, that are run automatically on the build server.
These tests can be run (if the [test dependencies](/test) are installed) with: `test/functional/test_runner.py`

The Travis CI system makes sure that every pull request is built for Windows, Linux, and macOS, and that unit/sanity tests are run automatically.

### Manual Quality Assurance (QA) Testing

Changes should be tested by somebody other than the developer who wrote the
code. This is especially important for large or high-risk changes. It is useful
to add a test plan to the pull request description if testing the changes is
not straightforward.


Supporting
-----------
Supporting the bitcoinsilver is a 100% community-sponsored endeavor. If you want to join our efforts, the easiest thing you can do is support the project financially. Bitcoin, BitcoinCash, Ethereum, Litecoin, Dash, Zcash, Dogecoin donations you can send BTC, BCH, ETH, LTC, DASH, ZEC, DOGE address.

The Bitcoin donation address is: 1Pxws5NZd91f11PqFAZQBvG719M3gYLpLT

The Bitcoin Cash donation address is: 14hZhfqTJkBkCctRL4kC9sj2fMyDMtE8Uw

The Ethereum donation address is: 0x95076ae250a591dfb9f42787ae80700d659a2102

The Litecoin donation address is: LSzAmTH68tfcuPwnr6h9biY8wrMgATmZMg

The Dash donation address is: Xk2KHfXqmCkBQ6JJa4xN55QrApa5DcAZVX

The Zcash donation address is : t1fpb9TiXUEfX8WAiqeo6fXcjTasPi5atEp

The Dogecoin donation address is : DL4a1Koxr76E6r6FoPboMgaRvpQTrEHG5y
