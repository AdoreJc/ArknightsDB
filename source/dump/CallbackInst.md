# CallbackInst

**Namespace:** ` `


## Fields

- `Action <listener>k__BackingField`

- `UInt32 <instanceUid>k__BackingField`


## Properties

- `Action listener`

- `UInt32 instanceUid`


## Methods

- `Action get_listener()`

- `Void set_listener(Action)`

- `UInt32 get_instanceUid()`

- `Void set_instanceUid(UInt32)`

- `Void Reset(Action, UInt32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CallbackInst : IPtrObject
{
	private Action <listener>k__BackingField; // 0x10
	private UInt32 <instanceUid>k__BackingField; // 0x18

	public Action listener { get; set; }
	public UInt32 instanceUid { get; set; }

	// RVA: 0x2167ea8 VA: 0x759477fea8
	public Action get_listener() { }
	// RVA: 0x2167eb0 VA: 0x759477feb0
	private Void set_listener(Action value) { }
	// RVA: 0x2167eb8 VA: 0x759477feb8
	public UInt32 get_instanceUid() { }
	// RVA: 0x2167ec0 VA: 0x759477fec0
	private Void set_instanceUid(UInt32 value) { }
	// RVA: 0x2167e9c VA: 0x759477fe9c
	public Void Reset(Action listener, UInt32 id) { }
	// RVA: 0x2167ec8 VA: 0x759477fec8
	public Void .ctor() { }
}
```