# ArchiveQuestAVGItemModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `SandboxV2ArchiveQuestType questType`

- `String questTypeName`

- `String name`

- `String desc`

- `SandboxV2ArchiveQuestZoneData zoneData`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveQuestAVGItemModel : IHotfixable
{
	public SandboxV2ArchiveQuestType questType; // 0x10
	public String questTypeName; // 0x18
	public String name; // 0x20
	public String desc; // 0x28
	public List`1 avgDataList; // 0x30
	public List`1 npcPicIdList; // 0x38
	public SandboxV2ArchiveQuestZoneData zoneData; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0


	// RVA: 0x3075da4 VA: 0x759568dda4
	public Void .ctor() { }
}
```