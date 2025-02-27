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
      --context-directory string   Synadia Context Directory (default "/home/seth/.config/synadia/contexts")
      --no-context                 Disable the selected context
      --server string              Synadia Control Plane Server
      --system string              Synadia Control Plane System ID
      --team string                Synadia Control Plane Team ID
      --token string               Synadia Control Plane Auth Token
```

## synctl system export

export system seeds from control plane

```
synctl system export [SYSTEM_ID] [flags]
```

**Options**

```
  -h, --help   help for export
```

**Options inherited from parent commands**

```
      --account string             Synadia Control Plane Account ID
      --context string             Use the Control Plane context
      --context-directory string   Synadia Context Directory (default "/home/seth/.config/synadia/contexts")
      --no-context                 Disable the selected context
      --server string              Synadia Control Plane Server
      --system string              Synadia Control Plane System ID
      --team string                Synadia Control Plane Team ID
      --token string               Synadia Control Plane Auth Token
```

## synctl system import

Import system into Control Plane

```
synctl system import [flags]
```

**Options**

```
      --all                import all accounts from an operator
  -h, --help               help for import
      --js-disabled        disable jetstream for the imported system
      --js-domain string   set jetstream domain for the imported system
  -t, --team string        team id for system
      --users              import users during account import
```

**Options inherited from parent commands**

```
      --account string             Synadia Control Plane Account ID
      --context string             Use the Control Plane context
      --context-directory string   Synadia Context Directory (default "/home/seth/.config/synadia/contexts")
      --no-context                 Disable the selected context
      --server string              Synadia Control Plane Server
      --system string              Synadia Control Plane System ID
      --token string               Synadia Control Plane Auth Token
```

## synctl system import-account

Import account into an existing Control Plane system

```
synctl system import-account [flags]
```

**Options**

```
      --all             import all accounts from an operator
  -h, --help            help for import-account
  -s, --system string   system id
      --users           import users during account import
```

**Options inherited from parent commands**

```
      --account string             Synadia Control Plane Account ID
      --context string             Use the Control Plane context
      --context-directory string   Synadia Context Directory (default "/home/seth/.config/synadia/contexts")
      --no-context                 Disable the selected context
      --server string              Synadia Control Plane Server
      --team string                Synadia Control Plane Team ID
      --token string               Synadia Control Plane Auth Token
```

## synctl system import-user

Import user into an existing Control Plane system and account

```
synctl system import-user [flags]
```

**Options**

```
  -h, --help            help for import-user
  -s, --system string   system id
```

**Options inherited from parent commands**

```
      --account string             Synadia Control Plane Account ID
      --context string             Use the Control Plane context
      --context-directory string   Synadia Context Directory (default "/home/seth/.config/synadia/contexts")
      --no-context                 Disable the selected context
      --server string              Synadia Control Plane Server
      --team string                Synadia Control Plane Team ID
      --token string               Synadia Control Plane Auth Token
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
      --context-directory string   Synadia Context Directory (default "/home/seth/.config/synadia/contexts")
      --no-context                 Disable the selected context
      --server string              Synadia Control Plane Server
      --system string              Synadia Control Plane System ID
      --team string                Synadia Control Plane Team ID
      --token string               Synadia Control Plane Auth Token
```

