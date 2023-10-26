# plusstorage: technical documentation repo

[plusstorage][product-page] is an open-source cloud service by [plusserver GmbH][company-website]. The technical documentation is published [here][docs].

## Contributions

Hi, :wave:
we welcome your contributions to our technical documentation! Whether you're fixing a typo, updating existing guides, or creating new ones, your contributions help us improve our documentation for the community.

To contribute, follow these steps:

1. Fork the repository by clicking the `Fork` button on GitHub.

1. Clone the forked repository to your local machine using the following command:

```bash
git clone https://github.com/plusstorage/docs-s3.git
```

1. Create a new branch to work on your changes:

```bash
git checkout -b my-new-branch
```

1. Make your changes to the documentation.

1. Commit your changes with a descriptive `commit` message.

1. Push your changes to your forked repository:

```bash
git push origin my-new-branch
```

1. Open a `pull request (PR)` from your forked repository to the original repository's `main` branch.

1. Wait for the documentation maintainers to review your changes. They may request changes or ask for more information before merging your changes.

### Developer Certificate of Origin (DCO) Sign Off

:warning: Important: All contributions __must__ follow our [Developer Certificate of Origin (DCO)](https://developercertificate.org/) sign off process, which means that you must include a `DCO Sign Off` in every commit message. You can do this by adding the `--signoff` flag to your `git commit` command:

```bash
# Sign off a commit as you're making it
git commit --signoff -m "Update README.md"

# Add a signoff to the last commit you made
git commit --amend --signoff

# Rebase your branch against master and sign off every commit in your branch
git rebase --signoff master
```

Please note that PRs without `DCO Sign Off` will not be accepted.

Thank you  for your contributions to our technical documentation! :rocket:

[docs]:[s3.stor.get-cloud.io]
[product-page]:[https://www.plusserver.com/en/product/s3-storage/]
[company-website]:[https://plusserver.com/en]