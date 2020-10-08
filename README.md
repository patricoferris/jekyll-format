jekyll-format — Jekyll post parsing library
-------------------------------------------
%%VERSION%%

[Jekyll](https://jekyllrb.com) is a simple, blog-aware static site
generator that takes a template directory of files and turns them into
a website. This library exists to parse those blog posts and make them
easy to manipulate from OCaml code.

jekyll-format is distributed under the ISC license.

Homepage: https://github.com/avsm/jekyll-format  
Contact: Anil Madhavapeddy `<anil@recoil.org>`

## Installation

jekyll-format can be installed with `opam`:

    opam install jekyll-format

If you don't use `opam` consult the [`opam`](opam) file for build
instructions.

If you want the unreleased version you can pin this repository. 

    opam pin add jekyll-format https://github.com/avsm/jekyll-format.git 

## Documentation

The documentation and API reference is automatically generated by
`ocamldoc` from the interfaces. It can be consulted [online][doc]
and there is a generated version in the `doc` directory of the
distribution.

[doc]: http://docs.mirage.io/jekyll-format

## Sample programs

If you installed jekyll-format with `opam` sample programs are located in
the directory `opam config var jekyll-format:doc`.

In the distribution sample programs and tests are located in the
[`test`](test) directory of the distribution. They can be built and run with:

    dune runtest 

The resulting binaries are in `_build/test`.

- `test.native` tests the library, nothing should fail.