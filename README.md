# Open Source Tools that we may need access to

## iterm2-minimal-tools.tar.gz

A minimal set of iterm2 utils that can be installed in docker images

This is created by creating an empty directory with the contents required (see existing `tar.gz` archive), and then creating archive with the following command (in the directory):

```bash
tar cvzf ../iterm2-minimal-tools.tar.gz
```