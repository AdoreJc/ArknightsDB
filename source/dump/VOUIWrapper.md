# VOUIWrapper

**Namespace:** ` `


## Fields

- `VUISystem m_closure`

- `Object m_objInst`

- `VOUIPanel m_panel`

- `Int32 m_objId`


## Properties

- `Object roomObject`

- `Int32 roomObjectId`

- `VOUIPanel panel`

- `Boolean isValid`


## Methods

- `Object get_roomObject()`

- `Int32 get_roomObjectId()`

- `VOUIPanel get_panel()`

- `Boolean get_isValid()`

- `Void Update()`

- `Boolean MatchObject(BuildingEvent, Object)`

- `Void Clear()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class VOUIWrapper
{
	private VUISystem m_closure; // 0x10
	private Object m_objInst; // 0x18
	private VOUIPanel m_panel; // 0x20
	private Int32 m_objId; // 0x28

	public Object roomObject { get; }
	public Int32 roomObjectId { get; }
	public VOUIPanel panel { get; }
	public Boolean isValid { get; }

	// RVA: 0x3d0d214 VA: 0x7596325214
	public Object get_roomObject() { }
	// RVA: 0x3d0d21c VA: 0x759632521c
	public Int32 get_roomObjectId() { }
	// RVA: 0x3d0d224 VA: 0x7596325224
	public VOUIPanel get_panel() { }
	// RVA: 0x3d0c95c VA: 0x759632495c
	public Boolean get_isValid() { }
	// RVA: 0x3d0cda0 VA: 0x7596324da0
	public Void .ctor(VOUIPanel panelUI, Object roomObject, VUISystem closure) { }
	// RVA: 0x3d0ca0c VA: 0x7596324a0c
	public Void Update() { }
	// RVA: 0x3d0d22c VA: 0x759632522c
	public Boolean MatchObject(BuildingEvent evt, Object roomObject) { }
	// RVA: 0x3d0c730 VA: 0x7596324730
	public Void Clear() { }
}
```