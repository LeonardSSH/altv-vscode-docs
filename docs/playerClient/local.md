This is your local player instance. You must use **scriptID** with a native for it to function when it asks for a `ped` or `entity`.

**Example Usage**

```js
if (!alt.Player.local.vehicle) {
    // Local player is not in a vehicle.
}

// Freeze the local player.
native.freezeEntityPosition(alt.Player.local.scriptID, true);
```
