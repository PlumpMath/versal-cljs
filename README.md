# versal-gadget

A working Clojurescript Versal gadget! AND it has React.js/om!

## Installation

`bower install`

(`brew install leiningen` if you don't have it)

`lein cljsbuild once`

`versal preview`

## Usage

All the source code is in `src/versal-gadget/core.cljs`.
Project compilation is performed by `project.clj`.

### Bugs

Versal Player API doesn't include `index.js` in it's bower repo so you must manually add it. Annoying.
