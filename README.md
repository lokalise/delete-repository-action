# GitHub Action to delete a Repository

This action can be used to delete a repository from your workflows.

## Usage

```yaml
uses: lokalise/delete-repository-action@v1
with:
  name: 'owner/repository'
  access-token: 'accessTokenWithRepoOrOrgAdminScope'
```
