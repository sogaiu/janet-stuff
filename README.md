# janet-stuff

Reminders of some Janet notes and code

* [Notes](#notes)
* [Code](#code)
  * [Code Samples and Demos](#code-samples-and-demos)
  * [Editor Trial Kits](#editor-trial-kits)
  * [Emacs](#emacs)
  * [Filesystem and Terminal](#filesystem-and-terminal)
  * [Janet Itself](#janet-itself)
  * [PEG](#peg)
  * [Protocols and Standards](#protocols-and-standards)
  * [Source Analysis, Generation, and Manipulation](#source-analysis-generation-and-manipulation)
  * [Testing](#testing)
  * [Tree-sitter](#tree-sitter)

## Notes

* [janet-editor-and-tooling-info](https://github.com/sogaiu/janet-editor-and-tooling-info) -
  mostly a collection of editor and tooling info for use with the
  Janet programming language

* [janet-examples](https://github.com/sogaiu/janet-examples)

* [janet-features-demos](https://github.com/sogaiu/janet-features-demos) -
  some demos of Janet features listed at the main page, in order, on a
  Linux box

* [janet-fiber-and-event-loop-notes](https://github.com/sogaiu/janet-fiber-and-event-loop-notes)

* [janet-subprocess-notes](https://github.com/sogaiu/janet-subprocess-notes/)

## Code

### Code Samples and Demos

* [git-some-janets](https://github.com/sogaiu/git-some-janets) - tool
  to retrieve various Janet repositories

* [janet-ref](https://github.com/sogaiu/janet-ref) - doc and source
  lookups of Janet itself, core lib samples and quizzes, and then
  some... (can be used with shell completion for identifiers)

* [jaylib-netrepl-demo](https://github.com/sogaiu/jaylib-netrepl-demo) -
  demo of using Jaylib with `spork/netrepl`

* [jaylib-tetris](https://github.com/sogaiu/jaylib-tetris) - jaylib
  port of raysan5's classics tetris code

* [jaylib-wasm-demo](https://github.com/sogaiu/jaylib-wasm-demo) -
  demo of using Jaylib in a web browser via WASM

* [spork-http-sample](https://github.com/sogaiu/spork-http-sample) -
  simple Janet `spork/http` samples

### Editor Trial Kits

* [janet-emacs-trial-kit](https://github.com/sogaiu/janet-emacs-trial-kit) -
  try Janet support in Emacs with relatively minimal fuss

* [janet-neovim-trial-kit](https://github.com/sogaiu/janet-neovim-trial-kit) -
  try Janet support in Neovim with relatively minimal fuss

### Emacs

* [a-janet-spork-client](https://github.com/sogaiu/a-janet-spork-client) -
  Emacs Lisp implementation of a subset of the client end of
  `spork/netrepl`

* [ajrepl](https://github.com/sogaiu/ajrepl) - interacting with a
  Janet REPL via Emacs

* [flycheck-janet](https://github.com/sogaiu/flycheck-janet/) - Emacs
  flycheck support for Janet

* [janet-ts-mode](https://github.com/sogaiu/janet-ts-mode) -
  tree-sitter-based Emacs major mode for Janet

* [snr](https://github.com/sogaiu/snr) - a `spork/netrepl` client for
  Emacs via "proxying"

### Filesystem and Terminal

* [janet-tempdir](https://github.com/sogaiu/janet-tempdir) - temporary
  directory creation

* [janet-termsize](https://github.com/sogaiu/janet-termsize) - a Janet
  (not C) implementation of determining a terminal's size (rows and
  columns)

* [janet-walk-dir](https://github.com/sogaiu/janet-walk-dir) - file
  and directory traversal

### Janet Itself

* [index-janet](https://github.com/sogaiu/index-janet) - generate tags
  / TAGS files for Janet's source code using universal ctags (used by
  editors for features like "jump to definition")

* [index-janet-source](https://github.com/sogaiu/index-janet-source) -
  generate tags / TAGS files for Janet's source code using PEGs (used
  by editors for features like "jump to definition")

* [jdoc](https://github.com/sogaiu/jdoc) - use janet's `doc` from the
  command line (can be used with shell completion for identifiers)

* [look-up-janet-def](https://github.com/sogaiu/look-up-janet-def) -
  look up a definition for a Janet identifier via a command line
  program and display the results in an editor (can be used with shell
  completion for identifiers)

### PEG

* [janet-pegdoc](https://github.com/sogaiu/janet-pegdoc) - doc,
  examples, and quizzes for Janet's PEGs (can be used with shell
  completion for identifiers)

* [margaret](https://github.com/sogaiu/margaret) - `peg/match`
  implemented in Janet (along with PEG examples and tutorial material)

* [small-peg-tracer](https://github.com/sogaiu/small-peg-tracer) -
  trace and view simulated execution of Janet's `peg/match`

### Protocols and Standards

* [janet-bencode](https://github.com/sogaiu/janet-bencode) - a Janet
  bencode library

* [janet-checksums](https://github.com/sogaiu/janet-checksums) - MD5,
  SHA-1, and SHA-2 in pure Janet

* [janet-jsonish](https://github.com/sogaiu/janet-jsonish) - JSON <->
  JDN conversion in pure Janet

* [janet-punyishcode](https://github.com/sogaiu/janet-punyishcode) -
  Punycode decoding / encoding in Janet

* [janet-totp](https://github.com/sogaiu/janet-totp) - some HOTP /
  TOTP support for Janet

* [janet-xmlish](https://github.com/sogaiu/janet-xmlish) - parse
  XML-ish strings as Janet data

### Source Analysis, Generation, and Manipulation

* [clojure-peg](https://github.com/sogaiu/clojure-peg) - parsing and
  generating Clojure via Janet's PEGs

* [jandent](https://github.com/sogaiu/jandent) - alternate indenter
  for Janet

* [janet-bounds](https://github.com/sogaiu/janet-bounds) - determining
  bounds of things in strings of Janet source code

* [janet-delims](https://github.com/sogaiu/janet-delims) - some
  functions for working with delimiters in fragments of Janet source
  code

* [janet-indent](https://github.com/sogaiu/janet-indent) - indenting a
  line or region of Janet source code

* [janet-last-expression](https://github.com/sogaiu/janet-last-expression) -
  determining the last expression in a fragment of Janet source code

* [janet-location-zipper](https://github.com/sogaiu/janet-location-zipper) - zipper for Janet source

* [janet-peg](https://github.com/sogaiu/janet-peg) - parsing and
  generating Janet via PEGs

* [janet-syntax-highlighting](https://github.com/sogaiu/janet-syntax-highlighting) -
  maintenance tool for updating syntax highlighting info for various
  editors and tools

* [janet-unwrap](https://github.com/sogaiu/janet-unwrap) - determining
  bounds for unwrapping forms in strings of Janet source code

* [review-janet](https://github.com/sogaiu/review-janet) - review
  (linting) tool for `.janet` code

### Testing

* [janet-ex-as-tests](https://github.com/sogaiu/janet-ex-as-tests) -
  expressing examples or usages and reusing as tests

* [janet-minipbt-translation](https://github.com/sogaiu/janet-minipbt-translation) -
  a translation into Janet of parts of MiniPBT (a series of articles
  about property-based-testing)

### Tree-sitter

* [janet-tree-sitter](https://github.com/sogaiu/janet-tree-sitter) -
  experimental bindings for tree-sitter using Janet

* [tree-sitter-janet-simple](https://github.com/sogaiu/tree-sitter-janet-simple) -
  simple Janet grammar for tree-sitter (usable in Emacs, Helix, Neovim)

* [ts-questions](https://github.com/sogaiu/ts-questions) -
  tree-sitter-related questions, discussions, and `.janet` scripts for
  fetching and analyzing grammar repositories

