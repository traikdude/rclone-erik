# Privacy notice for rclone-erik

Effective date: October 13, 2026

## Purpose and operator

rclone-erik is Erik's personal Google OAuth configuration for the rclone Desktop application. Contact: **traikdude@gmail.com**. It is intended for the account owner's personal use, not a public hosted file-processing service.

## Google data and permissions

The configuration requests only the Google Drive read-only scope, `https://www.googleapis.com/auth/drive.readonly`. When the owner runs rclone, rclone can retrieve Drive file and folder metadata and download file contents selected by the owner. The scope does not authorize uploading, editing, renaming, or deleting Drive files.

## Processing and storage

rclone communicates with Google's authorization and Drive APIs. Google processes these requests under its own policies. OAuth tokens and client configuration are stored on the owner's computer in the rclone configuration. The client secret is backed up to the owner's local credential vault. Files downloaded by the owner are stored at the local destinations chosen by the owner.

This repository hosts only public app information and this notice. It does not receive or store OAuth tokens or Drive file contents. GitHub may process visits to these public documents under GitHub's own privacy policy.

## Sharing and use

This personal configuration does not provide an advertising, analytics, or data-sale service. No Drive data or authorization tokens are sent to this public repository. The owner is responsible for any later transfer of files they download.

## Retention and revocation

Local downloads remain until the owner deletes them. Local authorization tokens remain until the owner removes the configuration, disconnects the remote, or revokes access. The owner can revoke the app's access through their Google Account's third-party connections settings. Revoking access does not automatically delete files already downloaded.

## Contact and changes

Questions about this personal configuration or requests to change this notice can be sent to **traikdude@gmail.com**. Updates will appear in this public document with a revised effective date.
