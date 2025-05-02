# ArchivePicModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `String selectedPicId`

- `Boolean isFullscreen`

- `Boolean isInit`

- `String homeKVId`


## Methods

- `Void LoadData(String, ActArchiveComponentData, ActArchiveInfo)`

- `PicArchiveResItemData _getArchivePicResData(String)`

- `String GetDefaultItemID()`

- `Int32 GetSelectedIndex(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchivePicModel : IHotfixable
{
	public ListDict`2 picItems; // 0x10
	public String selectedPicId; // 0x18
	public Boolean isFullscreen; // 0x20
	public Boolean isInit; // 0x21
	public String homeKVId; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__getArchivePicResData; // 0x8
	private static DelegateBridge __Hotfix0_GetDefaultItemID; // 0x10
	private static DelegateBridge __Hotfix0_GetSelectedIndex; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x306b948 VA: 0x7595683948
	public Void LoadData(String archiveId, ActArchiveComponentData compData, ActArchiveInfo archiveInfo) { }
	// RVA: 0x306bec0 VA: 0x7595683ec0
	private PicArchiveResItemData _getArchivePicResData(String picId) { }
	// RVA: 0x306bff0 VA: 0x7595683ff0
	public String GetDefaultItemID() { }
	// RVA: 0x306b6f0 VA: 0x75956836f0
	public Int32 GetSelectedIndex(String selectedItemId) { }
	// RVA: 0x306c1a8 VA: 0x75956841a8
	public Void .ctor() { }
}
```