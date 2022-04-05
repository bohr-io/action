# bohr.io deploy action

This action build and deploy your repository on [bohr.io](https://bohr.io) each time you push a commit.

# What's new

- Updated to the node16 runtime by default

# Usage

<!-- start usage -->
```yaml
name: bohr.io deploy
on: push
permissions:
  id-token: write
jobs:
  deploy:
    name: Deploy on bohr.io
    runs-on: ubuntu-latest
    steps:
      - uses: actions/checkout@v3
      - uses: bohr-io/action@main
```
<!-- end usage -->

# License

The scripts and documentation in this project are released under the [MIT License](LICENSE)