# DynamicMusicCompInfo

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `MusicProperty music`


## Methods

- `Void SetSelectedMusicItem(String, Boolean)`

- `Void SetHomeTheme()`

- `MusicItemModel GetHomeMusicItem()`

- `Boolean <>xLuaBaseProxy_HasNewItem()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class DynamicMusicCompInfo : ActArchiveCompInfo
{
	public MusicProperty music; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_SetSelectedMusicItem; // 0x8
	private static DelegateBridge __Hotfix0_SetHomeTheme; // 0x10
	private static DelegateBridge __Hotfix0_GetHomeMusicItem; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x20
	private static DelegateBridge __Hotfix0_ApplyDataBundle; // 0x28
	private static DelegateBridge __Hotfix0_IsValid; // 0x30
	private static DelegateBridge __Hotfix0_NotifyUpdate; // 0x38
	private static DelegateBridge __Hotfix0_HasNewItem; // 0x40


	// RVA: 0x3062af4 VA: 0x759567aaf4
	public Void .ctor(ActArchiveInfo archiveInfo) { }
	// RVA: 0x3062b7c VA: 0x759567ab7c
	public Void SetSelectedMusicItem(String musicID, Boolean isInit) { }
	// RVA: 0x3062cec VA: 0x759567acec
	public Void SetHomeTheme() { }
	// RVA: 0x3063030 VA: 0x759567b030
	public MusicItemModel GetHomeMusicItem() { }
	// RVA: 0x3063110 VA: 0x759567b110
	public override Void LoadData(String archiveId) { }
	// RVA: 0x306324c VA: 0x759567b24c
	public override Void ApplyDataBundle(DataBundle data) { }
	// RVA: 0x3063300 VA: 0x759567b300
	public override Boolean IsValid() { }
	// RVA: 0x306338c VA: 0x759567b38c
	public override Void NotifyUpdate() { }
	// RVA: 0x3063434 VA: 0x759567b434
	public override Boolean HasNewItem() { }
	// RVA: 0x3063574 VA: 0x759567b574
	private Boolean <>xLuaBaseProxy_HasNewItem() { }
}
```