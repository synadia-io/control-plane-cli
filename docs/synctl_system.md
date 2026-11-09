# synctl system

interact with systems

```
synctl system [flags]
```

**Options**

```
  -h, --help   help for system
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

## synctl system export

export system seeds from control plane

```
synctl system export [SYSTEM_ID] [flags]
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

## synctl system import

Import system into Control Plane

```
synctl system import [flags]
```

**Options**

```
      --all                 import all accounts from an operator
      --all-dirs string     NSC directory for the store, keys, and configuration
      --config-dir string   NSC configuration directory (defaults to NSC_HOME)
      --data-dir string     NSC store directory
      --existing            reuse the existing system if one already exists for this operator
  -h, --help                help for import
      --js-disabled         disable jetstream for the imported system
      --js-domain string    set jetstream domain for the imported system
      --keys-dir string     NSC keys directory (defaults to NKEYS_PATH)
      --name string         name for the imported system (defaults to the operator name)
      --new                 import as a new system even if a system already exists for this operator
  -t, --team string         team id for system
      --users               import users during account import
```

**Options inherited from parent commands**

```
      --account string             Synadia Control Plane Account ID
      --context string             Use the Control Plane context
      --context-directory string   Synadia Context Directory (default "<user-config-dir>/synadia/contexts")
      --no-context                 Disable the selected context
      --server string              Synadia Control Plane Server
      --system string              Synadia Control Plane System ID
      --token string               Synadia Control Plane Auth Token
  -V, --verbose count              Verbose output (-V for request URLs, -VV for full request/response bodies)
```

## synctl system import-account

Import account into an existing Control Plane system

```
synctl system import-account [flags]
```

**Options**

```
      --all                 import all accounts from an operator
      --all-dirs string     NSC directory for the store, keys, and configuration
      --config-dir string   NSC configuration directory (defaults to NSC_HOME)
      --data-dir string     NSC store directory
  -h, --help                help for import-account
      --keys-dir string     NSC keys directory (defaults to NKEYS_PATH)
  -s, --system string       system id
      --users               import users during account import
```

**Options inherited from parent commands**

```
      --account string             Synadia Control Plane Account ID
      --context string             Use the Control Plane context
      --context-directory string   Synadia Context Directory (default "<user-config-dir>/synadia/contexts")
      --no-context                 Disable the selected context
      --server string              Synadia Control Plane Server
      --team string                Synadia Control Plane Team ID
      --token string               Synadia Control Plane Auth Token
  -V, --verbose count              Verbose output (-V for request URLs, -VV for full request/response bodies)
```

## synctl system import-user

Import user into an existing Control Plane system and account

```
synctl system import-user [flags]
```

**Options**

```
      --all-dirs string     NSC directory for the store, keys, and configuration
      --config-dir string   NSC configuration directory (defaults to NSC_HOME)
      --data-dir string     NSC store directory
  -h, --help                help for import-user
      --keys-dir string     NSC keys directory (defaults to NKEYS_PATH)
  -s, --system string       system id
```

**Options inherited from parent commands**

```
      --account string             Synadia Control Plane Account ID
      --context string             Use the Control Plane context
      --context-directory string   Synadia Context Directory (default "<user-config-dir>/synadia/contexts")
      --no-context                 Disable the selected context
      --server string              Synadia Control Plane Server
      --team string                Synadia Control Plane Team ID
      --token string               Synadia Control Plane Auth Token
  -V, --verbose count              Verbose output (-V for request URLs, -VV for full request/response bodies)
```

## synctl system list

List Control Plane systems

```
synctl system list [flags]
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

