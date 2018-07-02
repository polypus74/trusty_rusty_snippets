# trusty-rusty-snippets

A fairly comprehensive set of snippets for the [Rust](https://www.rust-lang.org/) programming language.

Simple short and effective trigger strings. Attention was paid to putting tab stops in all the right places. For example, fn, struct, and enum snippets have the first tab stop before the keyword just in case you might want to add `pub` (i often forget).

Great care was also taken to ensure that trigger strings do not clash with each other, as to avoid having to choose snippets from a drop down list.

## Snippets

Most rust keywords have simple two letter triggers, i.e. the first two letters of the keyword itself, making them dead easy to recall. Of course these expand to more than just the keyword.

- im => `impl`
- el => `else`
- en => `enum`
- fo => `for`
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
- from => `impl From<...> for ...`
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
- pdb => `println!("... = {:?}", ...);` (print debug)
- pln => `println!(...);`
- un => `unimplemented!() // TODO`
- unr => `unreachable!(...)`
- vec => `vec![...]`
- test => `#[test]` with function def
- testm => `#[cfg(test)]` with module def
- todo => `// TODO: ...`

## Trigger String Choices

Some people find the shortness of these to be offputting, but there is rhyme & reason to these choices.

Aside from avoiding clashing with each other as well as snippets provided by, for example, the RLS extension, they had to be uniform, easy to remember, and preferably require little typing. With these constraints in mind I tried different combinations, with different length strings, and came up with these as best fitting.

If you do find them a bit cryptic for your taste, I recommend giving them a go before dismissing them offhand, however once the snippets stabilize and version 1.0 is released, I plan on releasing a more verbose version as well.

## Feedback

Feedback and suggestions appreciated. Snippets you are missing? I missed a good tab stop? Something is terribly wrong? Or you'd just like to buy me a pizza?

Submit an [issue](https://github.com/polypus74/trusty_rusty_snippets/issues) or a [pull request](https://github.com/polypus74/trusty_rusty_snippets/pulls).
