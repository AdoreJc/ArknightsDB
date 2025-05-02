# ArchiveAvgModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `String selectedAvgId`

- `Boolean isInit`


## Methods

- `Void LoadData(String, ActArchiveComponentData, ActArchiveInfo)`

- `AvgArchiveResItemData _getArchiveAvgResData(String)`

- `String GetDefaultItemID()`

- `Int32 GetSelectedIndex(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveAvgModel : IHotfixable
{
	public ListDict`2 avgItems; // 0x10
	public String selectedAvgId; // 0x18
	public Boolean isInit; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__getArchiveAvgResData; // 0x8
	private static DelegateBridge __Hotfix0_GetDefaultItemID; // 0x10
	private static DelegateBridge __Hotfix0_GetSelectedIndex; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x3036a40 VA: 0x759564ea40
	public Void LoadData(String archiveId, ActArchiveComponentData compData, ActArchiveInfo archiveInfo) { }
	// RVA: 0x3036e5c VA: 0x759564ee5c
	private AvgArchiveResItemData _getArchiveAvgResData(String avgId) { }
	// RVA: 0x3035c38 VA: 0x759564dc38
	public String GetDefaultItemID() { }
	// RVA: 0x30367e4 VA: 0x759564e7e4
	public Int32 GetSelectedIndex(String selectedItemId) { }
	// RVA: 0x3036f8c VA: 0x759564ef8c
	public Void .ctor() { }
}
```