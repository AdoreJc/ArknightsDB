# UIBuildingLevelPanelAdapter

**Namespace:** `Torappu.Building.UI`


## Fields

- `Int32 level`

- `Int32 maxLevel`

- `Color color`

- `Color emptyColor`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class UIBuildingLevelPanelAdapter : SimpleLayoutAdapter
{
	public Int32 level; // 0x20
	public Int32 maxLevel; // 0x24
	public Color color; // 0x28
	public Color emptyColor; // 0x38
	private static DelegateBridge __Hotfix0_get_count; // 0x0
	private static DelegateBridge __Hotfix0_RenderView; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public override Int32 count { get; }

	// RVA: 0x3d4faf8 VA: 0x7596367af8
	public override Int32 get_count() { }
	// RVA: 0x3d4fb60 VA: 0x7596367b60
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x3d4a65c VA: 0x759636265c
	public Void .ctor() { }
}
```