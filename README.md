# network_config_archive
Ansible playbook for archiving network device configurations to a git project.

Currently supports:

1. Juniper
2. Cisco Nexus
3. Cisco IOS

Collects configuration as well as any extra commands needed.  Supports lists of search-and-replace patterns to obscure sensitive data before committing to the archive repo.

The roles are currently written to support private key authentication to the target git repo, but could be modified easily support username/password.  Either way, the key or password needs to be provided somehow.

