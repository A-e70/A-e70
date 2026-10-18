## Ilana River

I build tools for problems I actually ran into, and I write up what went wrong while building them.

Most of it is systems and data work on Linux: file formats, encryption at rest, recovery, automation. I like problems where the answer is buried in a binary layout or an undocumented schema and you have to read the source to find it. When a problem needs a web app or a site, I build that too.

My background is maths and physics, so I lean toward the parts of software that have a correct answer. A lot of what I make checks work. It doesn't generate it.

### Work

**[chatvault](https://github.com/A-e70/chatvault)** · Python, SQLCipher, AES
Gets your own messages and media out of desktop chat apps, even when the app won't open them anymore. Each adapter answers four questions about one app. The core does the rest: Electron `safeStorage` unwrapping across keyring backends, SQLCipher, and per-file attachment decryption with HMAC checks. Signal and Session adapters are tested against real profiles.

Missing files are sorted into four categories, because "nine files missing" can't tell you whether you lost photographs or footnotes.

**[starfold](https://github.com/A-e70/starfold)** · JavaScript, no dependencies
Find a planet in real telescope data, in your browser. It runs a Box Least Squares transit search over TESS light curves. I wrote the search myself. There's no server and no library.

**[entolog](https://github.com/A-e70/entolog)** · Python standard library
Turns a folder of insect photos into a species record table, with whatever fields the recorder picks. You can use it in a window, in a terminal, or in your own `$EDITOR` and image viewer. It exports a Darwin Core Archive and needs nothing installed.

**[face-grouper](https://github.com/A-e70/face-grouper)** · OpenCV, scikit-learn
Sorts a folder of photos into one folder per person, on a CPU, and nothing leaves the machine. It doesn't guess gender on purpose. Those models are unreliable, and they fail worst on the people who get hurt most by a wrong label.

The README covers the threshold that nearly broke it. At 0.85, which looks sensible, the detector found faces in zero of eighty real phone photos and still reported a clean run.

**[Locus](https://locus-ae70.pages.dev/)** · React 19, TypeScript, KaTeX, Tailwind
A study app for Edexcel A Level Physics, Maths and Computer Science. The step checker reads your working line by line in exact arithmetic, so it catches a right answer reached the wrong way. Your study data stays in your browser.

**[Chronicled](https://timely-puppy-efee0c.netlify.app/)** · TanStack Start, React 19, Vite, Tailwind
A history site split into Past, Present and Future. There's a world map for browsing events by place and a research view that searches several open sources at once. I wrote the articles and built the site from scratch.

### Writing

[The Assay](https://theassay.pages.dev/) is my own technical publication.

[Notes on what went wrong](https://github.com/A-e70/writing) has two so far: getting my data back from an app that locked me out, and a face detector that found nothing and reported success.

### Studio

[Pellix](https://pellix.pages.dev/) is my web design studio. I build custom sites by hand for architecture and building practices.

### Working with

Python, TypeScript, React, SQL, Linux and shell. I'm comfortable in a database or a hex dump. Learning Go.

Based in Bangladesh, UTC+6. Email me at adlie72ae@gmail.com.
