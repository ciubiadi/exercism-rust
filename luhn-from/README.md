# Luhn From

Luhn: Using the From Trait

# Luhn: Using the From Trait

Before doing this exercise you should probably do the original Luhn exercise. If you have not completed Luhn, you can get it by running the command:

> `exercism fetch rust luhn`

In the original Luhn exercise you only validated strings, but the Luhn algorithm can be applied to integers as well.

In this exercise you'll implement the [From trait](https://doc.rust-lang.org/std/convert/trait.From.html) to convert strings, strs and unsigned integers into a Struct that performs the validation.

## Rust Installation

Refer to the [exercism help page][help-page] for Rust installation and learning
resources.

## Writing the Code

Execute the tests with:

```bash
$ cargo test
```

All but the first test have been ignored.  After you get the first test to
pass, remove the ignore flag (`#[ignore]`) from the next test and get the tests
to pass again.  The test file is located in the `tests` directory.   You can
also remove the ignore flag from all the tests to get them to run all at once
if you wish.

Make sure to read the [Crates and Modules](https://doc.rust-lang.org/stable/book/crates-and-modules.html) chapter if you
haven't already, it will help you with organizing your files.

## Feedback, Issues, Pull Requests

The [exercism/xrust](https://github.com/exercism/xrust) repository on GitHub is the home for all of the Rust exercises. If you have feedback about an exercise, or want to help implement new exercises, head over there and create an issue. Members of the [rust track team](https://github.com/orgs/exercism/teams/rust) are happy to help!

If you want to know more about Exercism, take a look at the [contribution guide](https://github.com/exercism/x-common/blob/master/CONTRIBUTING.md).

[help-page]: http://exercism.io/languages/rust
[crates-and-modules]: http://doc.rust-lang.org/stable/book/crates-and-modules.html

## Source

The Rust track maintainers, based on the original Luhn exercise

## Submitting Incomplete Problems
It's possible to submit an incomplete solution so you can see how others have completed the exercise.

