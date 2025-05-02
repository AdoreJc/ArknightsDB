# VisualObject

**Namespace:** `Torappu.Battle`


## Properties

- `Vector2 mapPosition`

- `Vector3 mapPositionV3`

- `Vector3 worldPosition`

- `Single height`

- `Single x`

- `Single y`

- `Single z`

- `Int32 row`

- `Int32 col`

- `Rect mapRect`

- `Bounds mapBounds`


## Methods

- `Vector2 get_mapPosition()`

- `Vector3 get_mapPositionV3()`

- `Vector3 get_worldPosition()`

- `Single get_height()`

- `Single get_x()`

- `Single get_y()`

- `Single get_z()`

- `Int32 get_row()`

- `Int32 get_col()`

- `Rect get_mapRect()`

- `Bounds get_mapBounds()`

- `Void SetPosition(GridPosition)`

- `Void SetPosition(Vector2)`

- `Void SetPositionV3(Vector3)`

- `Void SetPositionWithHeight(Vector2, Single)`

- `Void TruncateCurrentPos()`

- `Void _AssignLocalPosInternal(Vector3)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class VisualObject : MonoBehaviour, ILocatable
{

	public Vector2 mapPosition { get; }
	public Vector3 mapPositionV3 { get; }
	public Vector3 worldPosition { get; }
	public Single height { get; }
	public virtual Vector2 faceTo { get; }
	public virtual GridPosition gridPosition { get; }
	public Single x { get; }
	public Single y { get; }
	public Single z { get; }
	public Int32 row { get; }
	public Int32 col { get; }
	public Rect mapRect { get; }
	public Bounds mapBounds { get; }

	// RVA: 0x1c3b4e0 VA: 0x75942534e0
	public Vector2 get_mapPosition() { }
	// RVA: 0x1c3b500 VA: 0x7594253500
	public Vector3 get_mapPositionV3() { }
	// RVA: 0x1c3b520 VA: 0x7594253520
	public Vector3 get_worldPosition() { }
	// RVA: 0x1c3b540 VA: 0x7594253540
	public Single get_height() { }
	// RVA: 0x1c3b568 VA: 0x7594253568
	public virtual Vector2 get_faceTo() { }
	// RVA: 0x1c3b588 VA: 0x7594253588
	public virtual GridPosition get_gridPosition() { }
	// RVA: 0x1c3b5fc VA: 0x75942535fc
	public Single get_x() { }
	// RVA: 0x1c3b600 VA: 0x7594253600
	public Single get_y() { }
	// RVA: 0x1c3b614 VA: 0x7594253614
	public Single get_z() { }
	// RVA: 0x1c3b63c VA: 0x759425363c
	public Int32 get_row() { }
	// RVA: 0x1c3b654 VA: 0x7594253654
	public Int32 get_col() { }
	// RVA: 0x1c3b670 VA: 0x7594253670
	public Rect get_mapRect() { }
	// RVA: 0x1c3b6ec VA: 0x75942536ec
	public Bounds get_mapBounds() { }
	// RVA: 0x1c3b71c VA: 0x759425371c
	public Void SetPosition(GridPosition gridPosition) { }
	// RVA: 0x1c3b78c VA: 0x759425378c
	public Void SetPosition(Vector2 pos) { }
	// RVA: 0x1c3b888 VA: 0x7594253888
	public Void SetPositionV3(Vector3 pos) { }
	// RVA: 0x1c3b88c VA: 0x759425388c
	protected Void SetPositionWithHeight(Vector2 pos, Single height) { }
	// RVA: 0x1c3b894 VA: 0x7594253894
	public virtual Void SetHeight(Single height) { }
	// RVA: 0x1c3b8d0 VA: 0x75942538d0
	protected Void TruncateCurrentPos() { }
	// RVA: 0x1c3b7d0 VA: 0x75942537d0
	private Void _AssignLocalPosInternal(Vector3 localPos) { }
	// RVA: 0x1c3b954 VA: 0x7594253954
	public Void .ctor() { }
}
```