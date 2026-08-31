# About this repository
This repository contains records from the [rfc39](https://github.com/NixOS/rfc39) sync process.

# Requesting a new invitation
To request a new invitation:
1. Find your GitHub user ID, by:
    1. going to `https://api.github.com/users/$YOUR_USERNAME` and getting the value from the "id" field,
    2. using the `gh` CLI (`nix-shell -p gh`), authenticating, then running `gh api /user --jq .id`, or
    3. going to an unofficial site like https://caius.github.io/github_id/.
2. Go to https://github.com/NixOS/rfc39-record/edit/main/invitations, and delete the line containing your ID.
    Make a pull request with your change.
3. The pull request will be merged automatically.
    It may may take an hour or so for your new invitation to be sent to your primary GitHub email address.
    The new invitation will expire in one week.
