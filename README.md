## A-e70

I build tools that solve problems I actually ran into, and I write up how they work.

Mostly systems and data work on Linux: file formats, encryption at rest, recovery, automation. I like the problems where the answer is buried in a binary layout or an undocumented schema and you have to read the source to find it.

Background in mathematics and physics, which is why I gravitate toward the parts of software that have a correct answer rather than an opinion.

### Work

**[signal-desktop-export](https://github.com/A-e70/signal-desktop-export)**
Recovers messages and media from Signal Desktop when the app itself will no longer open them. Unwraps the Electron `safeStorage` key from the OS keyring, opens the SQLCipher database, and decrypts each attachment from its per-file key.

The part I care about is the accounting. It separates what was never downloaded, what was referenced but deleted, and what is orphaned on disk with no key, instead of reporting one lost-file count. On the run it was built for, that distinction turned "nine files missing" into "no pictures lost, nine long messages shortened."

### Working with

Python, SQL, Linux, shell. Comfortable in a database or a hex dump. Learning Go.

### Elsewhere

Writing about the above, in progress.

Based in Bangladesh, UTC+6. Reachable at adlie72ae@gmail.com.
