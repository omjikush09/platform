# Contributing

We would ❤️ for you to contribute to Platform and help make it better! We want contributing to Platform to be fun, enjoyable, and educational for anyone and everyone. All contributions are welcome, including issues, new docs as well as updates and tweaks, blog posts, workshops, and more.

## How to Start?

If you are worried or don’t know where to start, check out our next section explaining what kind of help we could use and where can you get involved. You can reach out with questions to [Eldad Fux (@eldadfux)](https://twitter.com/eldadfux) or [@appwrite_io](https://twitter.com/appwrite_io) on Twitter, and anyone from the [Appwrite team on Discord](https://discord.gg/GSeTUeA). You can also submit an issue, and a maintainer can guide you!

## Code of Conduct

Help us keep framework open and inclusive. Please read and follow our [Code of Conduct](/CODE_OF_CONDUCT.md).

## Submit a Pull Request 🚀

Branch naming convention is as following

`TYPE-ISSUE_ID-DESCRIPTION`

example:

```
doc-548-submit-a-pull-request-section-to-contribution-guide
```

When `TYPE` can be:

- **feat** - is a new feature
- **doc** - documentation only changes
- **cicd** - changes related to CI/CD system
- **fix** - a bug fix
- **refactor** - code change that neither fixes a bug nor adds a feature

**All PRs must include a commit message with the changes description!**

For the initial start, fork the project and use git clone command to download the repository to your computer. A standard procedure for working on an issue would be to:

1. `git pull`, before creating a new branch, pull the changes from upstream. Your master needs to be up to date.

```
$ git pull
```

2. Create new branch from `master` like: `doc-548-submit-a-pull-request-section-to-contribution-guide`<br/>

```
$ git checkout -b [name_of_your_new_branch]
```

3. Work - commit - repeat ( be sure to be in your branch )

4. Before you push your changes, make sure your code follows the `PSR12` coding standards , which is the standard Appwrite follows currently. You can easily do this by running the formatter.

```bash
composer format <your file path>
```

Now, go a step further by running the linter by the following command to manually fix the issues the formatter wasn't able to fix.

```bash
composer lint <your file path>
```

This will give you a list of errors for you to rectify , if there is an instance you need more information on the errors being displayed you can pass in additional command line arguments. More list of available arguments can be found [here](https://github.com/squizlabs/PHP_CodeSniffer/wiki/Usage). A very useful command line argument is `--report=diff`. This will give you the expected changes by the linter for easy fixing of formatting issues.

```bash
composer lint --report=diff <your file path>
```

5. Push changes to GitHub

```
$ git push origin [name_of_your_new_branch]
```

6. Submit your changes for review
   If you go to your repository on GitHub, you'll see a `Compare & pull request` button. Click on that button.
7. Start a Pull Request
   Now submit the pull request and click on `Create pull request`.
8. Get a code review approval/reject
9. After approval, merge your PR
10. GitHub will automatically delete the branch after the merge is done. (they can still be restored).

## Introducing New Features

We would 💖 you to contribute to Framework, but we would also like to make sure Framework is as great as possible and loyal to its vision and mission statement 🙏.

For us to find the right balance, please open an issue explaining your ideas before introducing a new pull request.

This will allow the Framework community to have sufficient discussion about the new feature value and how it fits in the product roadmap and vision.

This is also important for the Framework lead developers to be able to give technical input and different emphasis regarding the feature design and architecture. Some bigger features might need to go through our [RFC process](https://github.com/appwrite/rfc).

## Other Ways to Help

Pull requests are great, but there are many other areas where you can help Framework

### Blogging & Speaking

Blogging, speaking about, or creating tutorials about one of Framework's many features is great way to contribute and help our project grow.

### Presenting at Meetups

Presenting at meetups and conferences about your Framework projects. Your unique challenges and successes in building things with Framework can provide great speaking material. We’d love to review your talk abstract/CFP, so get in touch with us if you’d like some help!

### Sending Feedbacks & Reporting Bugs

Sending feedback is a great way for us to understand your different use cases of Framework better. If you had any issues, bugs, or want to share about your experience, feel free to do so on our GitHub issues page or at our [Discord channel](https://discord.gg/GSeTUeA).

### Submitting New Ideas

If you think Framework could use a new feature, please open an issue on our GitHub repository, stating as much information as you can think about your new idea and it's implications. We would also use this issue to gather more information, get more feedback from the community, and have a proper discussion about the new feature.

### Improving Documentation

Submitting documentation updates, enhancements, designs, or bug fixes. Spelling or grammar fixes will be very much appreciated.

### Helping Someone

Searching for Framework on Discord, GitHub, or StackOverflow and helping someone else who needs help. You can also help by teaching others how to contribute to Framework's repo!