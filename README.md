## A-e70

I build tools that solve problems I actually ran into, and I write up how they work.

Mostly systems and data work on Linux: file formats, encryption at rest, recovery, automation. I like the problems where the answer is buried in a binary layout or an undocumented schema and you have to read the source to find it. I also build web applications when the problem calls for one.

Background in mathematics and physics, which is why I gravitate toward the parts of software that have a correct answer rather than an opinion.

### Work

**[signal-desktop-export](https://github.com/A-e70/signal-desktop-export)** · Python, SQLCipher, AES
Recovers messages and media from Signal Desktop when the app itself will no longer open them. Unwraps the Electron `safeStorage` key from the OS keyring, opens the SQLCipher database, and decrypts each attachment from its per-file key.

The part I care about is the accounting. It separates what was never downloaded, what was referenced but deleted, and what is orphaned on disk with no key, rather than reporting one lost-file count. On the run it was built for, that distinction turned "nine files missing" into "no pictures lost, nine long messages shortened."

**[Chronicled](https://timely-puppy-efee0c.netlify.app/)** · TanStack Start, React 19, Vite, Tailwind
A history site organised around Past, Present and Future rather than a flat archive. Includes an interactive world map for browsing events by place, and a research view that queries several open sources at once instead of a single index.

Written and built from scratch, including the editorial content. Deployed on Netlify.

**Locus** · React 19, TypeScript, KaTeX, Tailwind
A study desk for Edexcel A Level Physics, Mathematics and Further Mathematics. All 205 specification topics, tracked through three states, driving progress views and a resume list. Notes with real rendered equations, photographed working, and a curated set of study links.

Local first by design: everything lives in the browser, so it works offline and no study data leaves the machine. Optional AI tutoring uses the reader's own API key, held in local storage and never sent anywhere else.

### Working with

Python, TypeScript, React, SQL, Linux, shell. Comfortable in a database or a hex dump. Learning Go.

### Elsewhere

Writing about the above, in progress.

Based in Bangladesh, UTC+6. Reachable at adlie72ae@gmail.com.
