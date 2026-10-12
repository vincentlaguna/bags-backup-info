# Bags Backup Privacy Policy

Last updated: October 12, 2026

## Purpose
Bags Backup is a private-use backup setup operated by Vincent Laguna.
It uses rclone and restic to store encrypted, versioned backups in
the Google Drive account authorized by the operator.

## Google Drive access
The setup requests access to files it creates or files explicitly
authorized for the application. It uses this access to create,
read, update, and delete backup repository files.

## Data handling
Restic encrypts backup contents and metadata locally before upload.
Google Drive stores the encrypted repository. OAuth credentials
are stored locally by rclone and are not published on this website.

Backup data is not sold, used for advertising, or intentionally
shared with other users.

## Retention and access removal
Backups remain until the operator removes them through the backup
tools or Google Drive. Google account permissions can be revoked
at any time. Revoking access does not delete existing backups.

## This website
This public GitHub Pages website contains documentation only.
It does not contain backup data or credentials. GitHub may collect
technical access information under its own privacy policy.

## Contact
Contact Vincent Laguna through:
https://github.com/vincentlaguna
