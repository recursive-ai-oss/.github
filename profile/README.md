# Recursive AI

An independent lab in Austin, Texas: one person, Kurtis Welch, and a fleet of agents, building open tools for software that agents and people use. Agents designed, wrote and tested each library here; Kurtis decided what to build.

**[recursiveai.org](https://recursiveai.org)** · [All libraries, with docs and cookbooks](https://recursiveai.org/libraries/)

### Documents and data

- **[oneyaml](https://recursiveai.org/oneyaml/)** — YAML 1.2 with typed reads and edits that keep your comments, and the same behavior in every language. [Rust](https://github.com/recursive-ai-oss/oneyaml-rust) ([crates.io](https://crates.io/crates/oneyaml)) · [Go](https://github.com/recursive-ai-oss/oneyaml-go) ([pkg.go.dev](https://pkg.go.dev/oneyaml.dev/go)) · [C#](https://github.com/recursive-ai-oss/oneyaml-csharp) ([NuGet](https://www.nuget.org/packages/OneYaml)) · [Python](https://github.com/recursive-ai-oss/oneyaml-python) (paused) · [conformance kit](https://github.com/recursive-ai-oss/oneyaml-kit)
- **[onepdf](https://recursiveai.org/onepdf/)** — Open and repair real-world PDFs, extract text in reading order, edit, fill forms, sign, and lay out new documents. [Repo](https://github.com/recursive-ai-oss/onepdf-csharp) · [NuGet](https://www.nuget.org/packages/RecursiveAI.OnePdf)
- **[onehtml](https://recursiveai.org/onehtml/)** — Parse HTML the way a browser does, edit it without disturbing the rest, and check pages for accessibility problems. [Repo](https://github.com/recursive-ai-oss/onehtml-csharp) · [NuGet](https://www.nuget.org/packages/RecursiveAI.OneHtml)
- **[onerender](https://recursiveai.org/onerender/)** — An HTML and CSS rendering engine: pixels, a tagged PDF or a display list out, with no browser. [Repo](https://github.com/recursive-ai-oss/onerender-csharp) · [NuGet](https://www.nuget.org/packages/RecursiveAI.OneRender)
- **[onearchive](https://recursiveai.org/onearchive/)** — Compression codecs and archive formats in managed code: Zstandard, LZ4, Deflate, xz, bzip2, Brotli and more; tar, zip, 7z, ISO and compound files, extracted safely by default. [Repo](https://github.com/recursive-ai-oss/onearchive-csharp) · [NuGet](https://www.nuget.org/packages/RecursiveAI.OneArchive) · [OneCompress](https://www.nuget.org/packages/RecursiveAI.OneCompress)

### Scripting

- **[oneecma](https://recursiveai.org/oneecma/)** — An ECMAScript interpreter whose product is its error reports: what went wrong, where the value came from and how to fix it. [Repo](https://github.com/recursive-ai-oss/oneecma-csharp) · [NuGet](https://www.nuget.org/packages/RecursiveAI.OneEcma)

### AI and machine learning

- **[onemodel](https://recursiveai.org/onemodel/)** — A neural-network runtime and trainer in pure C#: ONNX models or its own format on SIMD CPU kernels, with no native binaries, and an exact mode that gives the same bits on every platform. [Repo](https://github.com/recursive-ai-oss/onemodel-csharp) · [NuGet](https://www.nuget.org/packages/RecursiveAI.OneModel) · [Training](https://www.nuget.org/packages/RecursiveAI.OneModel.Training)
- **[oneocr](https://recursiveai.org/oneocr/)** — Local OCR and document understanding in pure C#, with small models of its own: a page model with boxes and calibrated confidences, invoices and receipts as fields, PDF pages, and optional LLM vision checked against the page. [Repo](https://github.com/recursive-ai-oss/oneocr-csharp) · [NuGet](https://www.nuget.org/packages/RecursiveAI.OneOcr)

### Graphics and sound

- **[oneimage](https://recursiveai.org/oneimage/)** — Thumbnails, crops and conversions on a lazy, tiled engine, with add-ons for text, ASP.NET Core, SVG, PDF and PSD. [Repo](https://github.com/recursive-ai-oss/oneimage-csharp) · [NuGet](https://www.nuget.org/packages/RecursiveAI.OneImage)
- **[onefont](https://recursiveai.org/onefont/)** — Load TrueType and OpenType fonts and shape text in complex scripts, with bidi, line breaking and fallback. [Repo](https://github.com/recursive-ai-oss/onefont-csharp) · [NuGet](https://www.nuget.org/packages/RecursiveAI.OneFont)
- **[oneshader](https://recursiveai.org/oneshader/)** — HLSL in; SPIR-V, Metal Shading Language and WGSL out, with reflection, compiled during `dotnet build`. [Repo](https://github.com/recursive-ai-oss/oneshader-csharp) · [NuGet](https://www.nuget.org/packages/RecursiveAI.OneShader)
- **[oneaudio](https://recursiveai.org/oneaudio/)** — Decode, encode, resample, mix and analyze audio, plus playback and recording. Built first for game audio. [Repo](https://github.com/recursive-ai-oss/oneaudio-csharp) · [NuGet](https://www.nuget.org/packages/RecursiveAI.OneAudio)

### Games and simulation

- **[onegame](https://recursiveai.org/onegame/)** — A C#-native game engine with no editor: a game is plain C# plus text assets, built, run, tested and exported from the command line. [Repo](https://github.com/recursive-ai-oss/onegame) · [NuGet](https://www.nuget.org/packages/RecursiveAI.OneGame.Sdk)
- **[onemath](https://recursiveai.org/onemath/)** — Deterministic math: vectors, matrices, correctly rounded functions, exact geometric predicates and a fixed-point bridge, with the same bits on every platform. [Repo](https://github.com/recursive-ai-oss/onemath-csharp) · [NuGet](https://www.nuget.org/packages/RecursiveAI.OneMath)
- **[onepath](https://recursiveai.org/onepath/)** — Pathfinding and navigation: grids, graphs, navigation meshes and crowds, with results that are bit-identical on every platform. [Repo](https://github.com/recursive-ai-oss/onepath-csharp) · [NuGet](https://www.nuget.org/packages/RecursiveAI.OnePath)
- **[onephysics](https://recursiveai.org/onephysics/)** (preview, paused) — Deterministic 2D rigid-body physics, with byte-exact snapshots and per-step world hashes for rollback and lockstep, and 3D in preview. [Repo](https://github.com/recursive-ai-oss/onephysics-csharp) · [NuGet](https://www.nuget.org/packages/RecursiveAI.OnePhysics)

Questions, or sponsoring the work: [partners@recursiveai.org](mailto:partners@recursiveai.org)
