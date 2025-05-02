# ArchiveStoryModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `String selectedStoryId`

- `Boolean isInit`


## Methods

- `Void LoadData(String, ActArchiveComponentData, ActArchiveInfo)`

- `StoryArchiveResItemData _getArchiveStoryResData(String)`

- `String GetDefaultItemID()`

- `Int32 GetSelectedIndex(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveStoryModel : IHotfixable
{
	public ListDict`2 storyItems; // 0x10
	public String selectedStoryId; // 0x18
	public Boolean isInit; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__getArchiveStoryResData; // 0x8
	private static DelegateBridge __Hotfix0_GetDefaultItemID; // 0x10
	private static DelegateBridge __Hotfix0_GetSelectedIndex; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x30812b0 VA: 0x75956992b0
	public Void LoadData(String archiveId, ActArchiveComponentData compData, ActArchiveInfo archiveInfo) { }
	// RVA: 0x30816cc VA: 0x75956996cc
	private StoryArchiveResItemData _getArchiveStoryResData(String storyId) { }
	// RVA: 0x30817fc VA: 0x75956997fc
	public String GetDefaultItemID() { }
	// RVA: 0x307f7d8 VA: 0x75956977d8
	public Int32 GetSelectedIndex(String selectedItemId) { }
	// RVA: 0x30819b4 VA: 0x75956999b4
	public Void .ctor() { }
}
```