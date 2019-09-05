# Contributing

# Instructions for Logging Issues

## 1. Read the FAQ

Please [read the FAQ](https://github.com/solana-labs/solana/wiki/FAQ) before logging new issues, even if you think you have found a bug.

Issues that ask questions answered in the FAQ will be closed without elaboration.

## 2. Search for Duplicates

[Search the existing issues](https://github.com/solana-labs/solana/search?type=Issues) before logging a new one.

Some search tips:
 * *Don't* restrict your search to only open issues. An issue with a title similar to yours may have been closed as a duplicate of one with a less-findable title.
 * Check for synonyms. For example, if your bug involves an interface, it likely also occurs with type aliases or classes.
 * Search for the title of the issue you're about to log. This sounds obvious but 80% of the time this is sufficient to find a duplicate when one exists.
 * Read more than the first page of results. Many bugs here use the same words so relevancy sorting is not particularly strong.
 * If you have a crash, search for the first few topmost function names shown in the call stack.

## 3. Do you have a question?

The issue tracker is for **issues**, in other words, bugs and suggestions.
If you have a *question*, please use [Discord](http://solana.com/discord), your favorite search engine, or other resources.

## 4. Did you find a bug?

When logging a bug, please be sure to include the following:
 * What version of Solana you're using
 * If at all possible, an *isolated* way to reproduce the behavior
 * The behavior you expect to see, and the actual behavior

## 5. Do you have a suggestion?

We also accept suggestions in the issue tracker.
Be sure to [check the Solana Book](https://solana-labs.github.io/book/introduction.html) first.

In general, things we find useful when reviewing suggestions are:
* A description of the problem you're trying to solve
* An overview of the suggested solution
* Examples of how the suggestion would work in various places
  * Code examples showing e.g. "this would be an error, this wouldn't"
  * Code examples showing the generated JavaScript (if applicable)
* If relevant, precedent in other languages can be useful for establishing context and expected behavior

# Instructions for Contributing Code

## Tips

## Legal

You will need to complete a Contributor License Agreement (CLA). Briefly, this agreement testifies that you are granting us permission to use the submitted change according to the terms of the project's license, and that the work being submitted is under appropriate copyright.

Please submit a Contributor License Agreement (CLA) before submitting a pull request. You may visit https://cla.solana.com to sign digitally. Alternatively, download the agreement ([Solana Contribution License Agreement.pdf](add pdf), sign, scan, and email it back to <cla@solana.com>. Be sure to include your GitHub user name along with the agreement. Once we have received the signed CLA, we'll review the request.

## Housekeeping

Your pull request should:

* Include a description of what your change intends to do
* Be a child commit of a reasonably recent commit in the **master** branch
    * Requests need not be a single commit, but should be a linear sequence of commits (i.e. no merge commits in your PR)
* It is desirable, but not necessary, for the tests to pass at each commit
* Have clear commit messages
* Include adequate tests
    * At least one test should fail in the absence of your non-test code changes. If your PR does not match this criteria, please specify why
    * Tests should include reasonable permutations of the target fix/change
