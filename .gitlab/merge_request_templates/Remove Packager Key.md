<!--
This template is used when an existing packager PGP public key needs to be removed from the distribution's keyring.
It is used by users with a valid main key or a valid packager key after all steps in an accompanying issue (opened with the template "Remove Packager Key") have been fulfilled.
-->

/label ~"remove packager key"
/title Remove packager key of <!-- MODIFY: Add the packager's username -->

<!-- Please do not remove the above quick actions, which automatically label the issue and assign relevant users as reviewers. -->

# Remove a packager key

## Details

- Username: <!-- MODIFY: Add the @-prefixed username -->
- PGP key ID: <!-- MODIFY: Add the "long format" key ID of the PGP public key here -->

Related issue: <!-- MODIFY: Add #-prefixed issue number -->

## Checks

### Keyring maintainer

- [ ] There are no packages left in any of the official repositories, that are signed by the key which is about to be removed.
