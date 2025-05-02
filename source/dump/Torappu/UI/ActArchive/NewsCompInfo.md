# NewsCompInfo

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `NewsProperty news`


## Methods

- `NewsItemModel GetNewsItemInfo(String)`

- `Void SetSelectedNewsItem(String, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class NewsCompInfo : ActArchiveCompInfo
{
	public NewsProperty news; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_GetNewsItemInfo; // 0x8
	private static DelegateBridge __Hotfix0_SetSelectedNewsItem; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0_ApplyDataBundle; // 0x20
	private static DelegateBridge __Hotfix0_IsValid; // 0x28
	private static DelegateBridge __Hotfix0_NotifyUpdate; // 0x30


	// RVA: 0x306725c VA: 0x759567f25c
	public Void .ctor(ActArchiveInfo archiveInfo) { }
	// RVA: 0x30672e4 VA: 0x759567f2e4
	public NewsItemModel GetNewsItemInfo(String newsId) { }
	// RVA: 0x30673c8 VA: 0x759567f3c8
	public Void SetSelectedNewsItem(String newsID, Boolean isInit) { }
	// RVA: 0x3067538 VA: 0x759567f538
	public override Void LoadData(String archiveId) { }
	// RVA: 0x3067674 VA: 0x759567f674
	public override Void ApplyDataBundle(DataBundle data) { }
	// RVA: 0x3067728 VA: 0x759567f728
	public override Boolean IsValid() { }
	// RVA: 0x30677b4 VA: 0x759567f7b4
	public override Void NotifyUpdate() { }
}
```