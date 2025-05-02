# ArchiveQuestGroupModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `SandboxV2ArchiveQuestType questType`

- `String groupName`


## Properties

- `Boolean hasNewMark`

- `Boolean isLocked`


## Methods

- `Boolean get_hasNewMark()`

- `Boolean get_isLocked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveQuestGroupModel : IHotfixable
{
	public SandboxV2ArchiveQuestType questType; // 0x10
	public String groupName; // 0x18
	public List`1 itemList; // 0x20
	private static DelegateBridge __Hotfix0_get_hasNewMark; // 0x0
	private static DelegateBridge __Hotfix0_get_isLocked; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Boolean hasNewMark { get; }
	public Boolean isLocked { get; }

	// RVA: 0x3075a10 VA: 0x759568da10
	public Boolean get_hasNewMark() { }
	// RVA: 0x3075b04 VA: 0x759568db04
	public Boolean get_isLocked() { }
	// RVA: 0x3075bf4 VA: 0x759568dbf4
	public Void .ctor() { }
}
```