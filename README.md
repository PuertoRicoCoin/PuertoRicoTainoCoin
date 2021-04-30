# PuertoRicoTainoCoin Core integration/staging tree
https://puertoricotainocoin.com

<h2>What is PuertoRicoTainoCoin?</h2>

<p>PuertoRicoTainoCoin is an experimental digital currency that enables instant payments to anyone, anywhere in the world. PuertoRicoTainoCoin uses peer-to-peer technology to operate with no central authority: managing transactions and issuing money are carried out collectively by the network. PuertoRicoTainoCoin Core is the name of open source software which enables the use of this currency.</p>

For more information, as well as an immediately useable, binary version of the PuertoRicoTainoCoin Core software, see https://puertoricotainocoin.com


<h2>License</h2>
<p>Litecoin Core is released under the terms of the MIT license. See <a href="LICENSE">COPYING</a> for more information or see https://opensource.org/licenses/MIT. </p>

<h2>Development Process</h2>
<p>The <code>master</code> branch is regularly built and tested. Development is normally done in separate branches. Tags are created to indicate new official, stable release versions of PuertoRicoTainoCoin Core.
The contribution workflow is described in CONTRIBUTING.md.</p>

<h2>Testing</h2>
<p>Testing and code review is the bottleneck for development; we get more pull requests than we can review and test on short notice. Please be patient and help out by testing other people's pull requests, and remember this is a security-critical project where any mistake might cost people lots of money.</p>

<h2>Automated Testing</h2>
<p>Developers are strongly encouraged to write <a href="/src/test/README.md">unit tests</a> for new code, and to submit new unit tests for old code. Unit tests can be compiled and run (assuming they weren't disabled in configure) with: <code>make check</code>. Further details on running and extending unit tests can be found in <a href="/src/test/README.md">/src/test/README.md</a>.

There are also <a href="/src/test">regression and integration tests</a>, written in Python, that are run automatically on the build server. These tests can be run (if the <a href="/src/test">test dependencies</a> are installed) with: <code>test/functional/test_runner.py</code>

The Travis CI system makes sure that every pull request is built for Windows, Linux, and macOS, and that unit/sanity tests are run automatically.</p>

<h2>Manual Quality Assurance (QA) Testing</h2>
<p>Changes should be tested by somebody other than the developer who wrote the code. This is especially important for large or high-risk changes. It is useful to add a test plan to the pull request description if testing the changes is not straightforward.</p>

<h2>Translations</h2>
<p>We only accept translation fixes that are submitted through <a href="https://www.transifex.com/projects/p/bitcoin/">Bitcoin Core's Transifex page</a>. Translations are converted to Litecoin periodically.

Translations are periodically pulled from Transifex and merged into the git repository. See the <a href="doc/translation_process.md">translation process</a> for details on how this works.

Important: We do not accept translation changes as GitHub pull requests because the next pull from Transifex would automatically overwrite them again.</p>

 
