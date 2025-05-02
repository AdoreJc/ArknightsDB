# SetWhenBind

**Namespace:** ` `


## Fields

- `Boolean m_hasBeenSet`

- `TTarget <target>k__BackingField`

- `TValue <value>k__BackingField`


## Properties

- `TTarget target`

- `TValue value`


## Methods

- `TTarget get_target()`

- `Void set_target(TTarget)`

- `TValue get_value()`

- `Void set_value(TValue)`

- `Void Set(TValue)`

- `Void Bind(TTarget)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class SetWhenBind`2
{
	private Boolean m_hasBeenSet; // 0x0
	private Action`2 m_setAction; // 0x0
	private TTarget <target>k__BackingField; // 0x0
	private TValue <value>k__BackingField; // 0x0

	public TTarget target { get; set; }
	public TValue value { get; set; }

	// RVA: 0x VA: 0x0
	public Void .ctor(Action`2 setAction) { }
	// RVA: 0x VA: 0x0
	public TTarget get_target() { }
	// RVA: 0x VA: 0x0
	private Void set_target(TTarget value) { }
	// RVA: 0x VA: 0x0
	public TValue get_value() { }
	// RVA: 0x VA: 0x0
	private Void set_value(TValue value) { }
	// RVA: 0x VA: 0x0
	public Void Set(TValue val) { }
	// RVA: 0x VA: 0x0
	public Void Bind(TTarget tar) { }
}
```