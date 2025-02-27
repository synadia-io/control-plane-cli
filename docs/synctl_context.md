# synctl context

Manage Control Plane contexts

**Options**

```
  -h, --help   help for context
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

## synctl context add

Add a context

```
synctl context add NAME [flags]
```

**Options**

```
  -a, --account string       Synadia Cloud account ID
  -d, --description string   Context Description
  -h, --help                 help for add
  -s, --system string        Synadia Cloud system ID
  -t, --team string          Synadia Cloud team ID
```

**Options inherited from parent commands**

```
      --context string             Use the Control Plane context
      --context-directory string   Synadia Context Directory (default "/home/seth/.config/synadia/contexts")
      --no-context                 Disable the selected context
      --server string              Synadia Control Plane Server
      --token string               Synadia Control Plane Auth Token
```

## synctl context copy

Copy a context

```
synctl context copy NAME TEMPLATE [flags]
```

**Options**

```
  -a, --account string       Synadia Cloud account ID
  -d, --description string   Context Description
  -h, --help                 help for copy
  -s, --system string        Synadia Cloud system ID
  -t, --team string          Synadia Cloud team ID
```

**Options inherited from parent commands**

```
      --context string             Use the Control Plane context
      --context-directory string   Synadia Context Directory (default "/home/seth/.config/synadia/contexts")
      --no-context                 Disable the selected context
      --server string              Synadia Control Plane Server
      --token string               Synadia Control Plane Auth Token
```

## synctl context edit

Edit a context

```
synctl context edit NAME [flags]
```

**Options**

```
  -d, --description string   Context Description
  -h, --help                 help for edit
  -i, --interactive          Interactively edit in $EDITOR
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

## synctl context info

Show information about a context

```
synctl context info [NAME] [flags]
```

**Options**

```
  -h, --help   help for info
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

## synctl context list

List contexts

```
synctl context list [flags]
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

## synctl context remove

Remove a context

```
synctl context remove NAME [flags]
```

**Options**

```
  -h, --help   help for remove
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

## synctl context select

Select a context

```
synctl context select NAME [flags]
```

**Options**

```
  -h, --help   help for select
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

## synctl context unselect

Unselect current context

```
synctl context unselect [flags]
```

**Options**

```
  -h, --help   help for unselect
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

