# DragStatus

**Namespace:** ` `


## Fields

- `Boolean isDragging`

- `Boolean isInFocus`

- `Int32 fingerId`

- `Single time`

- `Vector2 lastPos`

- `Vector3 startPos`

- `Vector3 startCamPos`

- `Vector3 targetCamPos`


## Methods

- `Boolean IsValid()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
protected class DragStatus
{
	public Boolean isDragging; // 0x10
	public Boolean isInFocus; // 0x11
	public Int32 fingerId; // 0x14
	public Single time; // 0x18
	public Vector2 lastPos; // 0x1c
	public Vector3 startPos; // 0x24
	public Vector3 startCamPos; // 0x30
	public Vector3 targetCamPos; // 0x3c
	public List`1 movementQueue; // 0x48


	// RVA: 0x3fa39d8 VA: 0x75965bb9d8
	public Boolean IsValid() { }
	// RVA: 0x3fa39b8 VA: 0x75965bb9b8
	public Void .ctor() { }
}
```