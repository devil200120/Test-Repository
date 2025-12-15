# Git and GitHub Setup Notes

## GitHub Account
- Created GitHub account with professional username
- Added profile description

## SSH Key Setup
- Generated SSH keypair using ed25519 algorithm
- Added public key to GitHub account
- Verified connection with `ssh -T git@github.com`

## Git Configuration
- Set global username and email
- Configured default branch to main
- Verified installation with `git --version`

## Why Not Commit Binary Files
- **Large media files**: Bloat repository size, slow clones
- **Data dumps**: Better stored in databases or cloud storage
- **Zip/tar archives**: Can be regenerated from source
- **Compiled binaries**: Should be built from source code

Git uses delta compression optimized for text files. Binary files don't compress well and create large diffs even for small changes.

## Key Learnings
- Always check `git status` before committing
- Write clear, descriptive commit messages
- Use branches for new features
- Keep commits atomic and focused
