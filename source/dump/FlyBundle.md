# FlyBundle

**Namespace:** ` `


## Fields

- `LoopScrollRect m_scroll`

- `Boolean m_beginFlag`

- `Vector2 m_dragPos`

- `Vector2 m_endPos`

- `Single m_dragTime`

- `Single m_endTime`

- `Boolean m_isDone`

- `Vector2 m_endSpeed`


## Properties

- `Vector2 velocity`

- `Boolean isValid`


## Methods

- `Void BeginDrag(Vector2)`

- `Void EndDrag(Vector2)`

- `Void Reset()`

- `Vector2 get_velocity()`

- `Boolean get_isValid()`

- `Void _ClacEndSpeed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class FlyBundle
{
	private LoopScrollRect m_scroll; // 0x10
	private Boolean m_beginFlag; // 0x18
	private Vector2 m_dragPos; // 0x1c
	private Vector2 m_endPos; // 0x24
	private Single m_dragTime; // 0x2c
	private Single m_endTime; // 0x30
	private Boolean m_isDone; // 0x34
	private Vector2 m_endSpeed; // 0x38

	public Vector2 velocity { get; }
	public Boolean isValid { get; }

	// RVA: 0x2232b6c VA: 0x759484ab6c
	public Void .ctor(LoopScrollRect rect) { }
	// RVA: 0x2232b9c VA: 0x759484ab9c
	public Void BeginDrag(Vector2 localCursor) { }
	// RVA: 0x2232bc8 VA: 0x759484abc8
	public Void EndDrag(Vector2 localCursor) { }
	// RVA: 0x2232c74 VA: 0x759484ac74
	public Void Reset() { }
	// RVA: 0x2232c80 VA: 0x759484ac80
	public Vector2 get_velocity() { }
	// RVA: 0x2232c88 VA: 0x759484ac88
	public Boolean get_isValid() { }
	// RVA: 0x2232c08 VA: 0x759484ac08
	private Void _ClacEndSpeed() { }
}
```