# syn-cp system

interact with systems

```
syn-cp system [flags]
```

**Options**

```
  -h, --help            help for system
  -s, --system string   system id
```

**Options inherited from parent commands**

```
      --server string   Synadia Control Plane Server
      --token string    Synadia Control Plane Auth Token
```

## syn-cp system import-account

import account into system

```
syn-cp system import-account [flags]
```

**Options**

```
      --all     import all accounts from an operator
  -h, --help    help for import-account
      --users   import users during account import
```

**Options inherited from parent commands**

```
      --server string   Synadia Control Plane Server
  -s, --system string   system id
      --token string    Synadia Control Plane Auth Token
```

## syn-cp system import-user

import user into system / account

```
syn-cp system import-user [flags]
```

**Options**

```
  -h, --help   help for import-user
```

**Options inherited from parent commands**

```
      --server string   Synadia Control Plane Server
  -s, --system string   system id
      --token string    Synadia Control Plane Auth Token
```

## syn-cp system list

list configured systems

```
syn-cp system list [flags]
```

**Options**

```
  -h, --help   help for list
```

**Options inherited from parent commands**

```
      --server string   Synadia Control Plane Server
  -s, --system string   system id
      --token string    Synadia Control Plane Auth Token
```

