# synctl

Interact with Synadia Control Plane

**Synopsis**

This cli requires the server URL (example: https://cloud.synadia.com) and a token. The token may be generated at <server url>/profile/personal-access-tokens.
All flags may be set in environment variables with SCP\_ prefix.

```
synctl [flags]
```

**Examples**

```

# Set environment variables for server url and authentication:
export SCP_SERVER=https://cloud.synadia.com
export SCP_TOKEN=uat_demo

# List Accounts
synctl account list

# Import all NSC systems along with users and accounts
synctl system import --all --users

```

**Options**

```
  -h, --help            help for synctl
      --server string   Synadia Control Plane Server
      --token string    Synadia Control Plane Auth Token
  -v, --version         version for synctl
```

## See Also

- [synctl account](synctl_account.md)
- [synctl system](synctl_system.md)
