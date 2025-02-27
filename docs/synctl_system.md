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
      --server string   Synadia Control Plane Server
      --token string    Synadia Control Plane Auth Token
```

## synctl system import

import system into control plane

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
      --server string   Synadia Control Plane Server
      --token string    Synadia Control Plane Auth Token
```

## synctl system import-account

import account into an existing control plane system

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
      --server string   Synadia Control Plane Server
      --token string    Synadia Control Plane Auth Token
```

## synctl system import-user

import user into an existing control plane system / account

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
      --server string   Synadia Control Plane Server
      --token string    Synadia Control Plane Auth Token
```

## synctl system list

list configured systems

```
synctl system list [flags]
```

**Options**

```
  -h, --help          help for list
  -t, --team string   team id for system (empty value lists all systems)
```

**Options inherited from parent commands**

```
      --server string   Synadia Control Plane Server
      --token string    Synadia Control Plane Auth Token
```

