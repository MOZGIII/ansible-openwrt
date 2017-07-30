# OpenWRT/LEDE Router Management using Ansible

Both OpenWRT and LEDE should be supported.

## Usage

### Setup

There are two main options to use this repo:

1. Add it as a git submodule at you playbook repo and symlink roles and libraries to appropriate locations.

   Proc:
   - no copy-pasting
   - updates via upstream with git submodules
  
   Cons:
   - difficulty level: using git submodules and symlinks

2. Just copy and paste files.

   Proc:
   - simplicity
  
   Cons:
   - manual or no updates

### Config

Most of configuration is simply based of variables. Those can be specified in lots of places, see ansible documentation. The author uses `host_vars` files method.
See specific documentation in role files.
