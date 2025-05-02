# MusicCompInfo

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `MusicProperty music`


## Methods

- `MusicItemModel GetMusicItemInfo(String)`

- `Void SetSelectedMusicItem(String, Boolean)`

- `Void SetHomeTheme()`

- `Boolean <>xLuaBaseProxy_HasNewItem()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class MusicCompInfo : ActArchiveCompInfo
{
	public MusicProperty music; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GetMusicItemInfo; // 0x8
	private static DelegateBridge __Hotfix0_SetSelectedMusicItem; // 0x10
	private static DelegateBridge __Hotfix0_SetHomeTheme; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x20
	private static DelegateBridge __Hotfix0_ApplyDataBundle; // 0x28
	private static DelegateBridge __Hotfix0_IsValid; // 0x30
	private static DelegateBridge __Hotfix0_NotifyUpdate; // 0x38
	private static DelegateBridge __Hotfix0_HasNewItem; // 0x40


	// RVA: 0x3062068 VA: 0x759567a068
	public Void .ctor(ActArchiveInfo archiveInfo) { }
	// RVA: 0x30620f0 VA: 0x759567a0f0
	public MusicItemModel GetMusicItemInfo(String musicId) { }
	// RVA: 0x30621d4 VA: 0x759567a1d4
	public Void SetSelectedMusicItem(String musicID, Boolean isInit) { }
	// RVA: 0x3062344 VA: 0x759567a344
	public Void SetHomeTheme() { }
	// RVA: 0x3062688 VA: 0x759567a688
	public override Void LoadData(String archiveId) { }
	// RVA: 0x30627c4 VA: 0x759567a7c4
	public override Void ApplyDataBundle(DataBundle data) { }
	// RVA: 0x3062878 VA: 0x759567a878
	public override Boolean IsValid() { }
	// RVA: 0x3062904 VA: 0x759567a904
	public override Void NotifyUpdate() { }
	// RVA: 0x30629ac VA: 0x759567a9ac
	public override Boolean HasNewItem() { }
	// RVA: 0x3062aec VA: 0x759567aaec
	private Boolean <>xLuaBaseProxy_HasNewItem() { }
}
```