---
layout: default
title: Privacy policy
---

# Privacy policy: Optiplex Backups

Optiplex Backups is a personal-use utility operated by the owner of the [rej-1 GitHub account](https://github.com/rej-1). It is not offered as a public service.

## Google data access and purpose

The utility requests authorization to create and manage its own backup files in the operator's Google Drive. It uses file contents and metadata needed to upload, list, download, verify, restore, and remove backup versions. It may read storage-quota information to avoid exceeding the operator's storage budget. Google OAuth tokens are stored locally with restricted access for unattended operation. The utility does not request Gmail, contacts, or calendar access.

## Storage and sharing

Backup contents are encrypted locally before upload; decryption keys remain under the operator's control, separate from the Drive repository. Google stores encrypted backup data in the operator's account and processes service information under its own policies. Backup data is not published on this website or GitHub. The utility does not sell data, use it for advertising, or use it to train AI models. Data is not shared with other parties except infrastructure providers needed to operate the backup, or when legally required.

Optiplex Backups' use and transfer of information received from Google APIs adheres to the [Google API Services User Data Policy](https://developers.google.com/terms/api-services-user-data-policy), including the Limited Use requirements.

## Retention, revocation, and deletion

Backup versions remain until removed under the operator's retention settings or explicit deletion. The operator can revoke access in [Google Account connections](https://myaccount.google.com/connections), remove locally stored OAuth tokens, and delete the backup repository from Drive. Revoking access alone does not delete existing backups. Drive trash may retain deleted files until permanently removed. Independent recovery copies are managed separately by the operator.

## This website and contact

This static site has no application login, analytics scripts, or advertising. GitHub Pages may collect technical request information under [GitHub's privacy statement](https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement). Questions or policy updates can be raised through the [project issue tracker](https://github.com/rej-1/optiplex-backups-info/issues). Never post credentials or private backup contents there.

[Back to application homepage](./)
