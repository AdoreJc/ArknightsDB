# BRoomLevelAdapter

**Namespace:** `Torappu.Building.BP`


## Fields

- `Int32 m_level`

- `Color mainColor`


## Methods

- `Void SetLevel(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.BP
public class BRoomLevelAdapter : SimpleLayoutAdapter
{
	private Int32 m_level; // 0x20
	public Color mainColor; // 0x24
	private static DelegateBridge __Hotfix0_SetLevel; // 0x0
	private static DelegateBridge __Hotfix0_get_count; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override Int32 count { get; }

	// RVA: 0x3d1ca40 VA: 0x7596334a40
	public Void SetLevel(Int32 level) { }
	// RVA: 0x3d21434 VA: 0x7596339434
	public override Int32 get_count() { }
	// RVA: 0x3d2149c VA: 0x759633949c
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x3d1c734 VA: 0x7596334734
	public Void .ctor() { }
}
```