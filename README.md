# product-pages-agent-sync

Deprecated and decommissioned.

This helper repository was previously used to manually mirror commits from
`conholdate/product-pages-agent` to the GitLab Product Pages Agent repository.

It is no longer active because the main `conholdate/product-pages-agent`
repository now owns the GitHub-to-GitLab sync path.

Security cleanup completed:
- `.github/workflows/GitlabSync.yml` was removed.
- Repository Actions secrets were removed.
- This repository should not be used for future sync operations.

Current source of truth:
- GitHub: `conholdate/product-pages-agent`
- GitLab mirror: `gitlab.recruitize.ai/sialkot/lahore-aspose/lahore-product-pages-team/product-pages-agent`
