# ArchiveQuestItemModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `String id`

- `ArchiveQuestItemType itemType`

- `String name`

- `ArchiveQuestAVGItemModel avgItemModel`

- `ArchiveQuestCGItemModel cgItemModel`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveQuestItemModel : ArchiveItemModel
{
	public String id; // 0x30
	public ArchiveQuestItemType itemType; // 0x38
	public String name; // 0x40
	public ArchiveQuestAVGItemModel avgItemModel; // 0x48
	public ArchiveQuestCGItemModel cgItemModel; // 0x50
	private static DelegateBridge __Hotfix0_GetFuncId; // 0x0
	private static DelegateBridge __Hotfix0_GetDesc; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3075c64 VA: 0x759568dc64
	public override String GetFuncId() { }
	// RVA: 0x3075ccc VA: 0x759568dccc
	public override String GetDesc() { }
	// RVA: 0x3075d34 VA: 0x759568dd34
	public Void .ctor() { }
}
```