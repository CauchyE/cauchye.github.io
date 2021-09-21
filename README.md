# GitHub projects unifying viewer

`https://cauchye.github.io?username=[username]&access_token=[access_token]`

- `username`: Your GitHub ID
- `access_token`: Your GitHub personal access token. The scopes `repo` and `read:org` are needed.

It is recommended to bookmark url which the query parameters are set.

## Managing issues outside CauchyE organization

For the purpose of managing issues outside CauchyE organization like `lcnem`, `cosmos-client` and `OpenSRDK`, use the fork function of GitHub. You can manage issues in forked repository.

You can use the commands below to make the continuing works convenient.

```bash
git clone https://github.com/CauchyE/[repository_name].git
git remote add upstream https://github.com/[source_organization_of_fork]/[repository_name].git
```
