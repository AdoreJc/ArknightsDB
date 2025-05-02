# ArchiveNewsModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `String selectedNewsId`

- `Boolean isInit`

- `Int32 paramT`


## Methods

- `Void LoadData(String, ActArchiveComponentData, ActArchiveInfo)`

- `NewsArchiveResItemData _getArchiveNewsResData(String)`

- `String GetDefaultItemID()`

- `Int32 GetSelectedIndex(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveNewsModel : IHotfixable
{
	public ListDict`2 newsItems; // 0x10
	public String selectedNewsId; // 0x18
	public Boolean isInit; // 0x20
	public Int32 paramT; // 0x24
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__getArchiveNewsResData; // 0x8
	private static DelegateBridge __Hotfix0_GetDefaultItemID; // 0x10
	private static DelegateBridge __Hotfix0_GetSelectedIndex; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x306687c VA: 0x759567e87c
	public Void LoadData(String archiveId, ActArchiveComponentData compData, ActArchiveInfo archiveInfo) { }
	// RVA: 0x3066d78 VA: 0x759567ed78
	private NewsArchiveResItemData _getArchiveNewsResData(String newsId) { }
	// RVA: 0x3066ea8 VA: 0x759567eea8
	public String GetDefaultItemID() { }
	// RVA: 0x3065af8 VA: 0x759567daf8
	public Int32 GetSelectedIndex(String selectedItemId) { }
	// RVA: 0x3067060 VA: 0x759567f060
	public Void .ctor() { }
}
```