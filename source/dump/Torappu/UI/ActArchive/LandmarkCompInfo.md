# LandmarkCompInfo

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `LandmarkProperty landmark`


## Methods

- `LandmarkItemModel GetLandmarkItemInfo(String)`

- `Void SetSelectedLandmarkItem(String, Boolean)`

- `Boolean <>xLuaBaseProxy_HasNewItem()`

- `Boolean <>xLuaBaseProxy_IsUnlocked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class LandmarkCompInfo : ActArchiveCompInfo
{
	public LandmarkProperty landmark; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GetLandmarkItemInfo; // 0x8
	private static DelegateBridge __Hotfix0_SetSelectedLandmarkItem; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0_ApplyDataBundle; // 0x20
	private static DelegateBridge __Hotfix0_IsValid; // 0x28
	private static DelegateBridge __Hotfix0_NotifyUpdate; // 0x30
	private static DelegateBridge __Hotfix0_HasNewItem; // 0x38
	private static DelegateBridge __Hotfix0_IsUnlocked; // 0x40


	// RVA: 0x30588f0 VA: 0x75956708f0
	public Void .ctor(ActArchiveInfo archiveInfo) { }
	// RVA: 0x3058978 VA: 0x7595670978
	public LandmarkItemModel GetLandmarkItemInfo(String landmarkId) { }
	// RVA: 0x3058a5c VA: 0x7595670a5c
	public Void SetSelectedLandmarkItem(String landmarkId, Boolean isInit) { }
	// RVA: 0x3058bd0 VA: 0x7595670bd0
	public override Void LoadData(String archiveId) { }
	// RVA: 0x3058d0c VA: 0x7595670d0c
	public override Void ApplyDataBundle(DataBundle data) { }
	// RVA: 0x3058dc0 VA: 0x7595670dc0
	public override Boolean IsValid() { }
	// RVA: 0x3058e4c VA: 0x7595670e4c
	public override Void NotifyUpdate() { }
	// RVA: 0x3058ef4 VA: 0x7595670ef4
	public override Boolean HasNewItem() { }
	// RVA: 0x3059038 VA: 0x7595671038
	public override Boolean IsUnlocked() { }
	// RVA: 0x3059174 VA: 0x7595671174
	private Boolean <>xLuaBaseProxy_HasNewItem() { }
	// RVA: 0x305917c VA: 0x759567117c
	private Boolean <>xLuaBaseProxy_IsUnlocked() { }
}
```