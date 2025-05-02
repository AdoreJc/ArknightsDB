# ToggleButtonGroup

**Namespace:** `Torappu.Building.UI.Meeting`


## Properties

- `Int32 toggleIndex`


## Methods

- `Void add_togglePressed(Action`1)`

- `Void remove_togglePressed(Action`1)`

- `Void _OnTogglePressed(ToggleButton)`

- `Void Awake()`

- `Void SetToggleIndex(Int32)`

- `Int32 get_toggleIndex()`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Meeting
public class ToggleButtonGroup : MonoBehaviour
{
	private ToggleButton[] _toggles; // 0x18
	private Action`1 togglePressed; // 0x20

	public Int32 toggleIndex { get; }

	// RVA: 0x3dfa53c VA: 0x759641253c
	public Void add_togglePressed(Action`1 value) { }
	// RVA: 0x3dfa48c VA: 0x759641248c
	public Void remove_togglePressed(Action`1 value) { }
	// RVA: 0x3e002ac VA: 0x75964182ac
	private Void _OnTogglePressed(ToggleButton button) { }
	// RVA: 0x3e00398 VA: 0x7596418398
	private Void Awake() { }
	// RVA: 0x3dfa5ec VA: 0x75964125ec
	public Void SetToggleIndex(Int32 index) { }
	// RVA: 0x3e004c4 VA: 0x75964184c4
	public Int32 get_toggleIndex() { }
	// RVA: 0x3e00510 VA: 0x7596418510
	private Void OnDestroy() { }
	// RVA: 0x3e005ec VA: 0x75964185ec
	public Void .ctor() { }
}
```