# Create Gist

Submitted by: [@jordanmerrick](https://twitter.com/jordanmerrick)

This action extension workflow accepts files of any type (though they must be text-based) and creates a [gist](https://gist.github.com/jordanmerrick/9f619c0aaffffd5bb46fad71e73e1477) using the [GitHub API](https://developer.github.com/v3/gists/).

You need to create a GitHub [personal access token](https://github.com/settings/tokens) before you can use this workflow. GitHub allows you to create multiple access tokens with different permissions. For the purpose of this workflow, I recommend creating a token that can only be used to work with gists. 

# Create GitHub Issue

Submitted by: [@jordanmerrick](https://twitter.com/jordanmerrick)

Using this workflow and [IFTTT recipe](https://ifttt.com/recipes/479154-create-github-issue-using-workflow), you can create an issue within the GitHub repository you specify. There's also provides an option to include a photo or screenshot when creating the issue. To accommodate this, the workflow uploads it to Dropbox and gets a direct link to use within the issue description.