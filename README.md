# trusty-rusty-snippets

A fairly comprehensive set of snippets for the [Rust](https://www.rust-lang.org/) programming language.

Simple short and effective trigger strings. Attention was paid to putting tab stops in all the right places. For example, fn, struct, and enum snippets have the first tab stop before the keyword just in case you might want to add `pub` (i often forget).

## Features

Most rust keywords have simple two letter triggers, i.e. the first two letters of the keyword itself, making them dead easy to recall. (Of course these expand to more than just the keyword).

- im => `impl`
- el => `else`
- en => `enum`
- fn => `fn`
- if => `if`
- le => `let`
- ma => `match`
- mo => `mod`
- st => `struct`
- tr => `trait`
- ty => `type`
- us => `use`

In addition, some of the triggers above have modifier letters postfixed for more elaborate expansions.

- eni => enum with `impl`
- eng => generic `enum`
- enig => generic `enum` with `impl`
- ife => `if` with `else`
- ifl => `if let`
- imf => `impl T for Q`
- img => generic `impl`
- lem => `let mut`
- ler => `let ref`
- lerm => `let ref mut`
- mob => `mod name {...}` (b for brackets)
- sti => `struct` with `impl`
- stg => generic `struct`
- stig => generic `struct` with `impl`
- trg => generic `trait`
- tyg => generic `type`
- usa => `use` `as`
- usb => `use module::{...}` (b for brackets)
- us\* => `use module::*`

There are also a few other helpers and odds and ends.

- ec => `extern crate`
- eca => `extern crate as`
- opt => `Option<...>`
- res => `Result<...>`
- | => multiline lambda
- main => `main` function def
- new => `new` constructor def
- \# => `#[...(...)]`
- cfg => `#[cfg(...)]`
- cff => `#[cfg(feature="...")]`
- drv => `#[derive(...))]`
- drv\* => derive common attrs
- ass => `assert!(...)` (pardon my french)
- asse => `assert_eq!(...)`
- mr => `macro_rules!`
- pdb => `println!("{:?}", ...)` (print debug)
- un => `unimplemented!() // TODO`
- vec => `vec![...]`
- test => `#[test]` with function def
- testm => `#[cfg(test)]` with module def
- todo => `// TODO: ...`

## Feedback

Feedback and suggestions appreciated. Snippets you are missing? I missed a good tab stop? Something is terribly wrong? Or you'd just like to buy me a pizza?

[Contact](mailto:polypus74@gmail.com) me or submit [pull requests](https://github.com/polypus74/trusty_rusty_snippets/pulls).

## Release Notes

### 0.1.0

Initial release.
