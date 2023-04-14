# Networking

## Overview

## Types
### Networked
You can make an attribute networked with `[Net]`
```cs
[Net]
public float Health { get; set; }
```

:::info

To make the `[Net]` Attribute work, your class needs to marked as `partial`.
This is due to the fact, Code-Gen interacts with it.

:::
### Predicted
```cs
[Net, Predicted]
public Rotation EyeLocalRotation { get; set; }
```

### Local
:::info

Networked properties can be set to be `[Local]`, in which case it will only be transmitted to the entity's owner.
This is beneficial if the information is solely relevant to the client in control or if you don't want other players to know how valuable it is for anti-cheat purposes.

:::
```cs
[Net, Local]
public int Money { get; set; }
```
