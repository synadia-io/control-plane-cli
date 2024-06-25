# syn-cp

Interact with the Synadia Control Plane

**Synopsis**

Interact with the Synadia Control Plane

This cli requires the server URL (example: https://cloud.synadia.com) and a token. The token may be generated at <server url>/profile/personal-access-tokens.
All flags may be set in environment variables with SCP_ prefix.

```
syn-cp [flags]
```

**Examples**

```

# Set environment variables for server url and authentication:
export SCP_SERVER=https://cloud.synadia.com
export SCP_TOKEN=uat_demo

# List Accounts
syn-cp account list

# Import all NSC systems along with users and accounts
syn-cp system import --all --users

```

**Options**

```
  -h, --help            help for syn-cp
      --server string   Synadia Control Plane Server
      --token string    Synadia Control Plane Auth Token
  -v, --version         version for syn-cp
```

## See Also

- [syn-cp account](syn-cp_account.md)
- [syn-cp system](syn-cp_system.md)
