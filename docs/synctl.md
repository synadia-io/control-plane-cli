# synctl

Interact with Synadia Control Plane

**Synopsis**

Interact with Synadia Control Plane

This CLI requires the server URL and a token.
The token may be generated at https://cloud.synadia.com/profile/personal-access-tokens.

All flags may be set in environment variables with SCP_ prefix.

The default config directory is $XDG_CONFIG_HOME/synadia/synctl.
The full path to the config file can be overridden using the SCP_CONFIG environment variable.

```
synctl [flags]
```

**Examples**

```

  # Set environment variables for server url and authentication:
  export SCP_SERVER=https://cloud.synadia.com
  export SCP_TOKEN=uat_demo

  # Create a context
  synctl context add cloud
  synctl context select cloud

  # List teams, systems, and accounts
  synctl team list
  synctl system list
  synctl account list

  # Import all NSC systems along with users and accounts
  synctl system import --all --users

```

**Options**

```
      --account string             Synadia Control Plane Account ID
      --context string             Use the Control Plane context
      --context-directory string   Synadia Context Directory (default "<user-config-dir>/synadia/contexts")
  -h, --help                       help for synctl
      --no-context                 Disable the selected context
      --server string              Synadia Control Plane Server
      --system string              Synadia Control Plane System ID
      --team string                Synadia Control Plane Team ID
      --token string               Synadia Control Plane Auth Token
  -V, --verbose count              Verbose output (-V for request URLs, -VV for full request/response bodies)
  -v, --version                    version for synctl
```

## See Also

- [synctl account](synctl_account.md)
- [synctl context](synctl_context.md)
- [synctl system](synctl_system.md)
- [synctl team](synctl_team.md)
