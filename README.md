## A-e70

I build tools that solve problems I actually ran into, and I write up what went wrong while building them.

Mostly systems and data work on Linux: file formats, encryption at rest, recovery, automation. I like the problems where the answer is buried in a binary layout or an undocumented schema and you have to read the source to find it. I also build web applications when the problem calls for one.

Background in mathematics and physics, which is why I gravitate toward the parts of software that have a correct answer rather than an opinion.

### Work

**[chatvault](https://github.com/A-e70/chatvault)** · Python, SQLCipher, AES
Gets your own messages and media out of desktop chat apps, including when the app will no longer open them. An adapter answers four questions about one application and the core handles Electron `safeStorage` unwrapping across keyring backends, SQLCipher, and per-file attachment decryption with HMAC verification. Signal and Session adapters, verified against real profiles.

Gaps are reported in four categories rather than one count, because "nine files missing" cannot tell you whether you lost photographs or footnotes.

**[face-grouper](https://github.com/A-e70/face-grouper)** · OpenCV, scikit-learn
Sorts a folder of photos into one folder per person, on CPU, with no GPU and nothing leaving the machine. Deliberately does not classify gender: those models are unreliable and fail hardest on the people most harmed by being sorted wrongly.

The README documents the threshold that nearly broke it. At a sensible looking 0.85 the detector found faces in zero of eighty real phone photos and reported a clean run.

**[Chronicled](https://timely-puppy-efee0c.netlify.app/)** · TanStack Start, React 19, Vite, Tailwind
A history site organised around Past, Present and Future rather than a flat archive. Includes an interactive world map for browsing events by place, and a research view that queries several open sources at once instead of a single index. Written and built from scratch, including the editorial content.

**[Locus](https://a-e70.github.io/alevel-desk/)** · React 19, TypeScript, KaTeX, Tailwind
A study desk for Edexcel A Level Physics, Mathematics and Further Mathematics. All 205 specification topics, tracked through three states, driving progress views and a resume list. Notes with rendered equations and a curated set of study links.

[Source](https://github.com/A-e70/alevel-desk). Local first: everything lives in the browser, so it works offline and no study data leaves the machine. Optional AI tutoring uses the reader's own API key, held locally and sent nowhere else.

### Writing

**[Notes on what went wrong](https://github.com/A-e70/writing)** — recovering data from an app that locked me out, and a detector that found nothing while reporting success.

### Working with

Python, TypeScript, React, SQL, Linux, shell. Comfortable in a database or a hex dump. Learning Go.

Based in Bangladesh, UTC+6. Reachable at adlie72ae@gmail.com.
