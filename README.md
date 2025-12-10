# github-wrapped
Make your own team's year in coding wrapped!

![](/img/1.png)

![](/img/2.png)

## Tools used

Here, I am using standard python library, pandas library to create a dataframe plus a few helper libraries.

```
pip install pandas tqdm notebook
```

## Retrieving the Github API token
In order to use the Github API, you will need a personal access token.
From [Github docs](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens):
> \> \> Personal access tokens are an alternative to using passwords for authentication to GitHub when using the GitHub API or the command line.

Follow this instruction to create a classic Personal Access Token: [https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens#creating-a-personal-access-token-classic](https://docs.github.com/en/authentication/keeping-your-account-and-data-secure/managing-your-personal-access-tokens#creating-a-personal-access-token-classic)

You will need to set the following permissions:
```
read:org, read:project, read:user, repo
```

Once created, store your token token securely. You will need it to access the Github API.

## Running the code
Clone the `github-wrapped.ipynb` notebook and use your org's and teams configuration.
Run or modify the code as needed.

## Example output

Total number of repos worked on this year: 45 ✅

Total PRs open this year: 1678 💪

Most active month - March with 256 PRs open 🎯

2 new repositories created - `my-orgs-new-repo-1` and `yet-another-amazing-repo` 🎉

Top 3 days with most PRs opened: 2025-03-20: 22, 2025-02-18: 16, 2025-01-24: 15 📅

Top 5 PR openers: jane: 244, john: 208, andy: 202, vicky: 169, mike: 135 🚀

Most dynamic repositories: `amazing-repo`: 256 PRs opened, `another-amazing-repo`: 128 PRs opened, `yet-another-amazing-repo`: 64 PRs opened 📈

2940 comments left! Top commenters: jane: 512 comments, john: 256 comments, andy: 128 comments 📢

95 LGTMs given (👍🏻ᴗ _ᴗ)👍🏻

4096 commits created 🔥

Lines of code written: ➕ 2 002 128

Lines of code deleted: ➖ 1 100 001


The possibilities are endless and only limited by your imagination and [Github REST API rate limit](https://docs.github.com/en/rest/using-the-rest-api/rate-limits-for-the-rest-api?apiVersion=2022-11-28) - you can calculate our own stats based on the datasets collected.