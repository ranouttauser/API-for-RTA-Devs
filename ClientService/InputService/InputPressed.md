# BindInput

Binds an input key to a callback.

### Parameters
- `Input`: [`InputBase`](#/Types/InputBase)  – Required. Key that will trigger event.
- `Cooldown : number?` – Optional. Delay between event being ran.
- `DestroyTime : number?` – Optional. Time until event cannot be ran.

### Returns
- `InputSignal` – whether the bind was successful
- [`InputSignal`](#/Types/InputSignal)

### Example
```lua
InputService.BindInput(Enum.KeyCode.E, function()
    print("E key pressed")
end)
