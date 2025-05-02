# ArchiveLandmarkModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `String selectedLandmarkId`

- `Boolean isInit`


## Methods

- `Void LoadData(String, ActArchiveComponentData, ActArchiveInfo)`

- `LandmarkArchiveResItemData _GetArchiveLandmarkResData(String)`

- `String GetDefaultItemId()`

- `Int32 GetSelectedIndex(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveLandmarkModel : IHotfixable
{
	public ListDict`2 landmarkItems; // 0x10
	public String selectedLandmarkId; // 0x18
	public Boolean isInit; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__GetArchiveLandmarkResData; // 0x8
	private static DelegateBridge __Hotfix0_GetDefaultItemId; // 0x10
	private static DelegateBridge __Hotfix0_GetSelectedIndex; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3057f04 VA: 0x759566ff04
	public Void LoadData(String archiveId, ActArchiveComponentData compData, ActArchiveInfo archiveInfo) { }
	// RVA: 0x305836c VA: 0x759567036c
	private LandmarkArchiveResItemData _GetArchiveLandmarkResData(String landmarkId) { }
	// RVA: 0x305849c VA: 0x759567049c
	public String GetDefaultItemId() { }
	// RVA: 0x3058654 VA: 0x7595670654
	public Int32 GetSelectedIndex(String selectedItemId) { }
	// RVA: 0x30586f4 VA: 0x75956706f4
	public Void .ctor() { }
}
```