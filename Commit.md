# git commit

The command`git commit` will take all tracked changes (items added with [git add](./Add.md)) and package them up in what is called a commit.

Commits come with commit messages that are required for each commit. You add a message tot a commit command by using the `-m` flag followed by a message in quotes.

A commit message_can_be anything, but best practice dictates that you should use that message to indicate the changes included in the commit.

for example, if we have an application we're working on where we just boult out the ablitlity to register new accounts, then you might have some variation of the following:

```
git add.
git commit -m "Added register funtionality"
```

Then when viewing the history of a git repository, you can pinpoint where the registration fuctionality was added.

## Resources

- [git Commit Documentation](https://git-scm/docs/git-commit)

---

[Back to home](../README.md)