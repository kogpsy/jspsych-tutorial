# Introduction to jsPsych

This is the source code of the short, introductory book to jsPsych called _Introduction to jsPsych_.

## Development

The book is built using [`mdBook`][mdbook-repo], a part of the Rust project which builds books from markdown files. Make sure it is installed on your system, if you want to work on this project or derive from it. The [book on `mdBook`][mdbook-book] explains how to do so, and is a good resource to get to know the software in general.

The (probably) most important commands druing development are

**`mdbook serve`**

which will spin up a development server under http://localhost:3000/ featuring hot-reload, and

**`mdbook build`**

which builds the book for production and puts the resulting files to `/book`.

## License

This work is licensed under the [Creative Commons Attribution 4.0 International License][cc-by].

[![CC-BY](https://i.creativecommons.org/l/by/4.0/88x31.png)][cc-by]

[mdbook-repo]: https://github.com/rust-lang/mdBook
[mdbook-book]: https://rust-lang.github.io/mdBook/index.html
[cc-by]: https://creativecommons.org/licenses/by/4.0/
