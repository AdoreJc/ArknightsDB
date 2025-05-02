# MountPoint

**Namespace:** `Torappu.Battle`


## Fields

- `Transform m_transform`


## Properties

- `Boolean isValid`

- `Entity entity`

- `Transform transform`

- `Vector2 mapPosition`

- `Vector3 mapPositionV3`

- `Vector3 worldPosition`

- `GridPosition gridPosition`

- `Single height`

- `Vector2 faceTo`


## Methods

- `Boolean get_isValid()`

- `Entity get_entity()`

- `Transform get_transform()`

- `Vector2 get_mapPosition()`

- `Vector3 get_mapPositionV3()`

- `Vector3 get_worldPosition()`

- `GridPosition get_gridPosition()`

- `Single get_height()`

- `Vector2 get_faceTo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class MountPoint : ILocatable
{
	public static readonly MountPoint INVALID; // 0x0
	private Transform m_transform; // 0x10
	private ObjectPtr`1 m_entity; // 0x18

	public Boolean isValid { get; }
	public Entity entity { get; }
	public Transform transform { get; }
	public Vector2 mapPosition { get; }
	public Vector3 mapPositionV3 { get; }
	public Vector3 worldPosition { get; }
	public GridPosition gridPosition { get; }
	public Single height { get; }
	public Vector2 faceTo { get; }

	// RVA: 0x40a08e8 VA: 0x75966b88e8
	public Boolean get_isValid() { }
	// RVA: 0x40a0930 VA: 0x75966b8930
	public Entity get_entity() { }
	// RVA: 0x40a0978 VA: 0x75966b8978
	public Transform get_transform() { }
	// RVA: 0x40a0980 VA: 0x75966b8980
	public Vector2 get_mapPosition() { }
	// RVA: 0x40a0a10 VA: 0x75966b8a10
	public Vector3 get_mapPositionV3() { }
	// RVA: 0x40a0aa0 VA: 0x75966b8aa0
	public Vector3 get_worldPosition() { }
	// RVA: 0x40a0abc VA: 0x75966b8abc
	public GridPosition get_gridPosition() { }
	// RVA: 0x40a0b30 VA: 0x75966b8b30
	public Single get_height() { }
	// RVA: 0x40a0b44 VA: 0x75966b8b44
	public Vector2 get_faceTo() { }
	// RVA: 0x40a0bc0 VA: 0x75966b8bc0
	public Void .ctor(Entity entity, Transform transform) { }
	// RVA: 0x40a0c48 VA: 0x75966b8c48
	private static Void .cctor() { }
}
```