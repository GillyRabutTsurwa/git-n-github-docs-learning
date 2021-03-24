[documentation-link]: https://docs.github.com/en/github/building-a-strong-community/creating-a-pull-request-template-for-your-repository
[pull-request-template-eg]: index.html

# What is a pull request template?

Exactly what it sounds like: it is a template used for making more efficient, specialised, and better oriented pull requests. In addition to making pull requests, from scratch, we can create a template (a lot like a form) to fill in the information needed to generate the pull request.

Here is the link to the [documentation][documentation-link] on how to make a pull request template

## How to make a pull request template
- *This is how I know how to make a pull request template as of right now*
- Make a ```.github``` file that will house the markdown file for the pull request template
- This file should be named ```pull_request_template.md```
  - Look at my [pull request template][pull-request-template-eg] for an example of what a template can look like
- Commit this file and push it **to your default branch** -- usually the *master* branch. Pushing the files and folders responsible to a branch that is not your default branch *will not work*.
- To test, switch to another branch and make a change to any file in order to initiate a pull request