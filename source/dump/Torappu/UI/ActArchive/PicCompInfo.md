# PicCompInfo

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `PicProperty pic`


## Methods

- `PicItemModel GetPicItemInfo(String)`

- `Void SetSelectedPicItem(String, Boolean)`

- `Void SetHomeKV()`

- `Void SetPicItemFullscreen(Boolean)`

- `Boolean <>xLuaBaseProxy_HasNewItem()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class PicCompInfo : ActArchiveCompInfo
{
	public PicProperty pic; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GetPicItemInfo; // 0x8
	private static DelegateBridge __Hotfix0_SetSelectedPicItem; // 0x10
	private static DelegateBridge __Hotfix0_SetHomeKV; // 0x18
	private static DelegateBridge __Hotfix0_SetPicItemFullscreen; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x28
	private static DelegateBridge __Hotfix0_ApplyDataBundle; // 0x30
	private static DelegateBridge __Hotfix0_IsValid; // 0x38
	private static DelegateBridge __Hotfix0_NotifyUpdate; // 0x40
	private static DelegateBridge __Hotfix0_HasNewItem; // 0x48


	// RVA: 0x306c3a4 VA: 0x75956843a4
	public Void .ctor(ActArchiveInfo archiveInfo) { }
	// RVA: 0x306c42c VA: 0x759568442c
	public PicItemModel GetPicItemInfo(String picId) { }
	// RVA: 0x306c510 VA: 0x7595684510
	public Void SetSelectedPicItem(String picID, Boolean isInit) { }
	// RVA: 0x306c680 VA: 0x7595684680
	public Void SetHomeKV() { }
	// RVA: 0x306c91c VA: 0x759568491c
	public Void SetPicItemFullscreen(Boolean on) { }
	// RVA: 0x306c9f8 VA: 0x75956849f8
	public override Void LoadData(String archiveId) { }
	// RVA: 0x306cb34 VA: 0x7595684b34
	public override Void ApplyDataBundle(DataBundle data) { }
	// RVA: 0x306cbe8 VA: 0x7595684be8
	public override Boolean IsValid() { }
	// RVA: 0x306cc74 VA: 0x7595684c74
	public override Void NotifyUpdate() { }
	// RVA: 0x306cd1c VA: 0x7595684d1c
	public override Boolean HasNewItem() { }
	// RVA: 0x306ce5c VA: 0x7595684e5c
	private Boolean <>xLuaBaseProxy_HasNewItem() { }
}
```