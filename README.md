<h1 align="center">acture</h1>

<p align="center">
  <strong>research systems × toolchain work × sharp developer tools</strong>
</p>

<p align="center">
  I build research-oriented systems and evaluation artifacts, then push the same taste for rigor into compiler,
  packaging, and language-tooling work. The public repos are only one slice of the picture; the through-line is
  making difficult software tasks more reliable, inspectable, and operational.
</p>

<p align="center">
  <code>systems research // semantics // toolchains // static analysis // workflow automation</code>
</p>

<p align="center">
  <a href="#research-thread">Research</a> ·
  <a href="#open-source-contributions">Open Source</a> ·
  <a href="#selected-tools">Tools</a>
</p>

## Research Thread

> Some active work stays intentionally abstract here while under review.
> The stable through-line is not a single title, but a recurring set of technical problems.

<table>
  <tr>
    <td width="50%">
      <strong>Agentic Software Engineering</strong><br/>
      orchestrated workflows for program transformation, inspection, and constrained automation
    </td>
    <td width="50%">
      <strong>Benchmark &amp; Artifact Design</strong><br/>
      evaluation setups built for reproducibility, diagnosability, and real execution constraints
    </td>
  </tr>
  <tr>
    <td width="50%">
      <strong>Program Semantics</strong><br/>
      semantics-aware translation, reconstruction, and transformation rather than surface-only rewriting
    </td>
    <td width="50%">
      <strong>Language-Centric Modeling</strong><br/>
      semantic understanding and structured modeling for language-heavy or annotation-heavy tasks
    </td>
  </tr>
</table>

## Open Source Contributions

I contribute upstream when the correct home for the work is the ecosystem itself, not a personal fork.

| Ecosystem | What I shipped | Links |
| --- | --- | --- |
| **Nix / nixpkgs** | Brought `flang` onto the 20.x line, then extended the packaging story with runtime support. | [#428306](https://github.com/NixOS/nixpkgs/pull/428306) · [#452306](https://github.com/NixOS/nixpkgs/pull/452306) |
| **LLVM / MLIR / Flang** | Build-system and packaging fixes aimed at reducing toolchain friction rather than patching around it downstream. | [#154412](https://github.com/llvm/llvm-project/pull/154412) · [#150987](https://github.com/llvm/llvm-project/pull/150987) |

These are the kinds of contributions I like most: infrastructure work that is boring in the right way, but makes real systems build, package, and ship correctly.

## Selected Tools

Public work tends to be small, sharp, and operational: tools with a narrow surface area and a strong opinion about how the workflow should feel.

| Project | Why it matters | Stack |
| --- | --- | --- |
| [`review-loop`](https://github.com/Acture/review-loop) | Durable CLI and daemon for review submission and retrieval, with explicit state, retries, and traceable local artifacts. | Rust, SQLite |
| [`char-cloud`](https://github.com/Acture/char-cloud) | Shape-constrained SVG word cloud generator with multiple layout strategies, reproducible output, and reusable library APIs. | Rust, SVG |
| [`d2typ`](https://github.com/Acture/d2typ) | Data-to-Typst conversion tool for document workflows where structured data needs to become publishable material quickly. | Rust, Typst |
| [`tree-sitter-paradox`](https://github.com/Acture/tree-sitter-paradox) | Tree-sitter grammar and bindings for Paradox scripting languages, aimed at better parsing, highlighting, and tooling. | Tree-sitter, JavaScript, C |
| [`scriptmark`](https://github.com/Acture/scriptmark) | Automated grading tooling for scriptable evaluation workflows, with a bias toward practical classroom and batch use. | Python |
| [`modus-foch`](https://github.com/Acture/modus-foch) | Static analysis tool for Paradox mod playsets, focused on symbol indexing, rule checks, and dependency integrity. | Rust |

## Collaboration

I am especially interested in:

- Research collaboration on systems, tooling, and evaluation.
- Benchmark, artifact, and reproducibility work.
- Developer tooling, language infrastructure, and static analysis.

If that overlaps with your work, reach out on GitHub.
