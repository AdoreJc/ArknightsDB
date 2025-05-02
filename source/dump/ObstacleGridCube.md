# ObstacleGridCube

**Namespace:** ` `


## Fields

- `Int32 <x>k__BackingField`

- `Int32 <y>k__BackingField`

- `Int32 <z>k__BackingField`

- `Int32 <w>k__BackingField`

- `Int32 <h>k__BackingField`

- `Int32 <d>k__BackingField`

- `Single m_gridSizeX`

- `Single m_gridSizeY`

- `Single m_gridSizeZ`

- `Transform m_parent`

- `DIYRoomIndicator m_indicator`

- `GridLocator m_gridLocator`


## Properties

- `Int32 x`

- `Int32 y`

- `Int32 z`

- `Int32 w`

- `Int32 h`

- `Int32 d`

- `Int32 pos0`

- `Int32 pos1`

- `Int32 dir`

- `Bounds bounds`


## Methods

- `Int32 get_x()`

- `Void set_x(Int32)`

- `Int32 get_y()`

- `Void set_y(Int32)`

- `Int32 get_z()`

- `Void set_z(Int32)`

- `Int32 get_w()`

- `Void set_w(Int32)`

- `Int32 get_h()`

- `Void set_h(Int32)`

- `Int32 get_d()`

- `Void set_d(Int32)`

- `Int32 get_pos0()`

- `Int32 get_pos1()`

- `Int32 get_dir()`

- `Bounds get_bounds()`

- `Void SetIndicator(DIYRoomIndicator)`

- `Void SetIndicatorVisible(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class ObstacleGridCube : IGridCube, ISpaceOccupation
{
	private Int32 <x>k__BackingField; // 0x10
	private Int32 <y>k__BackingField; // 0x14
	private Int32 <z>k__BackingField; // 0x18
	private Int32 <w>k__BackingField; // 0x1c
	private Int32 <h>k__BackingField; // 0x20
	private Int32 <d>k__BackingField; // 0x24
	private Single m_gridSizeX; // 0x28
	private Single m_gridSizeY; // 0x2c
	private Single m_gridSizeZ; // 0x30
	private Transform m_parent; // 0x38
	private DIYRoomIndicator m_indicator; // 0x40
	private GridLocator m_gridLocator; // 0x48

	public Int32 x { get; set; }
	public Int32 y { get; set; }
	public Int32 z { get; set; }
	public Int32 w { get; set; }
	public Int32 h { get; set; }
	public Int32 d { get; set; }
	public Int32 pos0 { get; }
	public Int32 pos1 { get; }
	public Int32 dir { get; }
	public Bounds bounds { get; }

	// RVA: 0x37c3020 VA: 0x7595ddb020
	public Int32 get_x() { }
	// RVA: 0x37c3028 VA: 0x7595ddb028
	private Void set_x(Int32 value) { }
	// RVA: 0x37c3030 VA: 0x7595ddb030
	public Int32 get_y() { }
	// RVA: 0x37c3038 VA: 0x7595ddb038
	private Void set_y(Int32 value) { }
	// RVA: 0x37c3040 VA: 0x7595ddb040
	public Int32 get_z() { }
	// RVA: 0x37c3048 VA: 0x7595ddb048
	private Void set_z(Int32 value) { }
	// RVA: 0x37c3050 VA: 0x7595ddb050
	public Int32 get_w() { }
	// RVA: 0x37c3058 VA: 0x7595ddb058
	private Void set_w(Int32 value) { }
	// RVA: 0x37c3060 VA: 0x7595ddb060
	public Int32 get_h() { }
	// RVA: 0x37c3068 VA: 0x7595ddb068
	private Void set_h(Int32 value) { }
	// RVA: 0x37c3070 VA: 0x7595ddb070
	public Int32 get_d() { }
	// RVA: 0x37c3078 VA: 0x7595ddb078
	private Void set_d(Int32 value) { }
	// RVA: 0x37c3080 VA: 0x7595ddb080
	public Int32 get_pos0() { }
	// RVA: 0x37c3088 VA: 0x7595ddb088
	public Int32 get_pos1() { }
	// RVA: 0x37c3090 VA: 0x7595ddb090
	public Int32 get_dir() { }
	// RVA: 0x37c3140 VA: 0x7595ddb140
	public Bounds get_bounds() { }
	// RVA: 0x37c3250 VA: 0x7595ddb250
	public Void SetIndicator(DIYRoomIndicator indicator) { }
	// RVA: 0x37c3258 VA: 0x7595ddb258
	public Void .ctor(Int32 x, Int32 y, Int32 z, Int32 w, Int32 h, Int32 d, Single gridSizeX, Single gridSizeY, Single gridSizeZ, GridLocator gridLocator, Transform parent) { }
	// RVA: 0x37bca28 VA: 0x7595dd4a28
	public Void SetIndicatorVisible(Boolean visible) { }
}
```