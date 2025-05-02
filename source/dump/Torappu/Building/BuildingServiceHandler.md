# BuildingServiceHandler

**Namespace:** `Torappu.Building`


## Fields

- `Action m_internalFinal`

- `Boolean <broadcastChange>k__BackingField`


## Properties

- `Boolean broadcastChange`


## Methods

- `Boolean get_broadcastChange()`

- `Void set_broadcastChange(Boolean)`

- `Void _OnProceed(ResType)`

- `Void _OnFinal()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building
public class BuildingServiceHandler`1 : ResultHandler`1
{
	private Action`1 m_internalProceed; // 0x0
	private Action m_internalFinal; // 0x0
	private Boolean <broadcastChange>k__BackingField; // 0x0

	public override Action`1 onProceed { get; set; }
	public override Action onFinal { get; set; }
	public Boolean broadcastChange { get; set; }

	// RVA: 0x VA: 0x0
	public Void .ctor(Action`1 internalProceed, Action internalFinal) { }
	// RVA: 0x VA: 0x0
	public override Action`1 get_onProceed() { }
	// RVA: 0x VA: 0x0
	public override Void set_onProceed(Action`1 value) { }
	// RVA: 0x VA: 0x0
	public override Action get_onFinal() { }
	// RVA: 0x VA: 0x0
	public override Void set_onFinal(Action value) { }
	// RVA: 0x VA: 0x0
	public Boolean get_broadcastChange() { }
	// RVA: 0x VA: 0x0
	public Void set_broadcastChange(Boolean value) { }
	// RVA: 0x VA: 0x0
	private Void _OnProceed(ResType resType) { }
	// RVA: 0x VA: 0x0
	private Void _OnFinal() { }
}
```