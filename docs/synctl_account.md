# synctl account

Interact with accounts

```
synctl account [flags]
```

**Options**

```
  -h, --help   help for account
```

**Options inherited from parent commands**

```
      --account string             Synadia Control Plane Account ID
      --context string             Use the Control Plane context
      --context-directory string   Synadia Context Directory (default "<user-config-dir>/synadia/contexts")
      --no-context                 Disable the selected context
      --server string              Synadia Control Plane Server
      --system string              Synadia Control Plane System ID
      --team string                Synadia Control Plane Team ID
      --token string               Synadia Control Plane Auth Token
  -V, --verbose count              Verbose output (-V for request URLs, -VV for full request/response bodies)
```

## synctl account export

Export account seeds from Control Plane

```
synctl account export [ACCOUNT_ID] [flags]
```

**Options**

```
      --all-dirs string     NSC directory for the store, keys, and configuration
      --config-dir string   NSC configuration directory (defaults to NSC_HOME)
      --data-dir string     NSC store directory
  -h, --help                help for export
      --keys-dir string     NSC keys directory (defaults to NKEYS_PATH)
```

**Options inherited from parent commands**

```
      --account string             Synadia Control Plane Account ID
      --context string             Use the Control Plane context
      --context-directory string   Synadia Context Directory (default "<user-config-dir>/synadia/contexts")
      --no-context                 Disable the selected context
      --server string              Synadia Control Plane Server
      --system string              Synadia Control Plane System ID
      --team string                Synadia Control Plane Team ID
      --token string               Synadia Control Plane Auth Token
  -V, --verbose count              Verbose output (-V for request URLs, -VV for full request/response bodies)
```

## synctl account list

List Control Plane accounts

```
synctl account list [flags]
```

**Options**

```
  -h, --help   help for list
```

**Options inherited from parent commands**

```
      --account string             Synadia Control Plane Account ID
      --context string             Use the Control Plane context
      --context-directory string   Synadia Context Directory (default "<user-config-dir>/synadia/contexts")
      --no-context                 Disable the selected context
      --server string              Synadia Control Plane Server
      --system string              Synadia Control Plane System ID
      --team string                Synadia Control Plane Team ID
      --token string               Synadia Control Plane Auth Token
  -V, --verbose count              Verbose output (-V for request URLs, -VV for full request/response bodies)
```

