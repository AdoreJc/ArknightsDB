# DynamicPicCompInfo

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `PicProperty pic`


## Methods

- `Void SetSelectedPicItem(String, Boolean)`

- `Void SetPicItemFullscreen(Boolean)`

- `Void SetHomeKV()`

- `Boolean <>xLuaBaseProxy_HasNewItem()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class DynamicPicCompInfo : ActArchiveCompInfo
{
	public PicProperty pic; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_SetSelectedPicItem; // 0x8
	private static DelegateBridge __Hotfix0_SetPicItemFullscreen; // 0x10
	private static DelegateBridge __Hotfix0_SetHomeKV; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x20
	private static DelegateBridge __Hotfix0_ApplyDataBundle; // 0x28
	private static DelegateBridge __Hotfix0_IsValid; // 0x30
	private static DelegateBridge __Hotfix0_NotifyUpdate; // 0x38
	private static DelegateBridge __Hotfix0_HasNewItem; // 0x40


	// RVA: 0x306ce64 VA: 0x7595684e64
	public Void .ctor(ActArchiveInfo archiveInfo) { }
	// RVA: 0x306ceec VA: 0x7595684eec
	public Void SetSelectedPicItem(String picID, Boolean isInit) { }
	// RVA: 0x306d05c VA: 0x759568505c
	public Void SetPicItemFullscreen(Boolean on) { }
	// RVA: 0x306d138 VA: 0x7595685138
	public Void SetHomeKV() { }
	// RVA: 0x306d3d4 VA: 0x75956853d4
	public override Void LoadData(String archiveId) { }
	// RVA: 0x306d510 VA: 0x7595685510
	public override Void ApplyDataBundle(DataBundle data) { }
	// RVA: 0x306d5c4 VA: 0x75956855c4
	public override Boolean IsValid() { }
	// RVA: 0x306d650 VA: 0x7595685650
	public override Void NotifyUpdate() { }
	// RVA: 0x306d6f8 VA: 0x75956856f8
	public override Boolean HasNewItem() { }
	// RVA: 0x306d838 VA: 0x7595685838
	private Boolean <>xLuaBaseProxy_HasNewItem() { }
}
```