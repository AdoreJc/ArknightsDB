# BuildingMusicPlayerListAdapter

**Namespace:** `Torappu.Building.UI.Meeting`


## Fields

- `GameObject _itemPrefab`


## Methods

- `Void RenderList(BuildingMusicPlayerViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Meeting
public class BuildingMusicPlayerListAdapter : LoopScrollAdapter`2, IHotfixable
{
	private GameObject _itemPrefab; // 0x58
	private static DelegateBridge __Hotfix0_RenderList; // 0x0
	private static DelegateBridge __Hotfix0_CreateView; // 0x8
	private static DelegateBridge __Hotfix0_UpdateView; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3ded60c VA: 0x759640560c
	public Void RenderList(BuildingMusicPlayerViewModel model) { }
	// RVA: 0x3ded6d8 VA: 0x75964056d8
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x3ded798 VA: 0x7596405798
	public override Void UpdateView(Int32 position, GameObject viewObj, ViewHolder holder, BuildingMusicItemViewModel data) { }
	// RVA: 0x3ded8f4 VA: 0x75964058f4
	public Void .ctor() { }
}
```