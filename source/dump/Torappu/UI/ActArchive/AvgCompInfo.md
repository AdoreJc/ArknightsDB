# AvgCompInfo

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `AvgProperty avg`


## Methods

- `AvgItemModel GetAvgItemInfo(String)`

- `Void SetSelectedAvgItem(String, Boolean)`

- `Boolean <>xLuaBaseProxy_HasNewItem()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class AvgCompInfo : ActArchiveCompInfo
{
	public AvgProperty avg; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GetAvgItemInfo; // 0x8
	private static DelegateBridge __Hotfix0_SetSelectedAvgItem; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0_ApplyDataBundle; // 0x20
	private static DelegateBridge __Hotfix0_IsValid; // 0x28
	private static DelegateBridge __Hotfix0_NotifyUpdate; // 0x30
	private static DelegateBridge __Hotfix0_HasNewItem; // 0x38


	// RVA: 0x3037188 VA: 0x759564f188
	public Void .ctor(ActArchiveInfo archiveInfo) { }
	// RVA: 0x3037210 VA: 0x759564f210
	public AvgItemModel GetAvgItemInfo(String avgId) { }
	// RVA: 0x30372f4 VA: 0x759564f2f4
	public Void SetSelectedAvgItem(String avgID, Boolean isInit) { }
	// RVA: 0x3037468 VA: 0x759564f468
	public override Void LoadData(String archiveId) { }
	// RVA: 0x30375a4 VA: 0x759564f5a4
	public override Void ApplyDataBundle(DataBundle data) { }
	// RVA: 0x3037658 VA: 0x759564f658
	public override Boolean IsValid() { }
	// RVA: 0x30376e4 VA: 0x759564f6e4
	public override Void NotifyUpdate() { }
	// RVA: 0x303778c VA: 0x759564f78c
	public override Boolean HasNewItem() { }
	// RVA: 0x30378d0 VA: 0x759564f8d0
	private Boolean <>xLuaBaseProxy_HasNewItem() { }
}
```