# LogCompInfo

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `LogProperty log`


## Methods

- `LogItemModel GetLogItemInfo(String)`

- `Void SetSelectedLogItem(String, Boolean)`

- `Boolean <>xLuaBaseProxy_HasNewItem()`

- `Boolean <>xLuaBaseProxy_IsUnlocked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class LogCompInfo : ActArchiveCompInfo
{
	public LogProperty log; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GetLogItemInfo; // 0x8
	private static DelegateBridge __Hotfix0_SetSelectedLogItem; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0_ApplyDataBundle; // 0x20
	private static DelegateBridge __Hotfix0_IsValid; // 0x28
	private static DelegateBridge __Hotfix0_NotifyUpdate; // 0x30
	private static DelegateBridge __Hotfix0_HasNewItem; // 0x38
	private static DelegateBridge __Hotfix0_IsUnlocked; // 0x40


	// RVA: 0x305c00c VA: 0x759567400c
	public Void .ctor(ActArchiveInfo archiveInfo) { }
	// RVA: 0x305c094 VA: 0x7595674094
	public LogItemModel GetLogItemInfo(String chapterId) { }
	// RVA: 0x305c178 VA: 0x7595674178
	public Void SetSelectedLogItem(String chapterId, Boolean isInit) { }
	// RVA: 0x305c3a0 VA: 0x75956743a0
	public override Void LoadData(String archiveId) { }
	// RVA: 0x305c4dc VA: 0x75956744dc
	public override Void ApplyDataBundle(DataBundle data) { }
	// RVA: 0x305c590 VA: 0x7595674590
	public override Boolean IsValid() { }
	// RVA: 0x305c61c VA: 0x759567461c
	public override Void NotifyUpdate() { }
	// RVA: 0x305c6c4 VA: 0x75956746c4
	public override Boolean HasNewItem() { }
	// RVA: 0x305c8d4 VA: 0x75956748d4
	public override Boolean IsUnlocked() { }
	// RVA: 0x305ca10 VA: 0x7595674a10
	private Boolean <>xLuaBaseProxy_HasNewItem() { }
	// RVA: 0x305ca18 VA: 0x7595674a18
	private Boolean <>xLuaBaseProxy_IsUnlocked() { }
}
```