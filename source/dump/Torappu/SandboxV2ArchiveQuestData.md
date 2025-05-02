# SandboxV2ArchiveQuestData

**Namespace:** `Torappu`


## Fields

- `String id`

- `Int32 sortId`

- `SandboxV2ArchiveQuestType questType`

- `String name`

- `String desc`

- `SandboxV2ArchiveQuestZoneData zoneData`


## Methods

- `Int32 CompareTo(SandboxV2ArchiveQuestData)`

- `String GetAvgFuncId()`

- `String GetCgFuncId(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class SandboxV2ArchiveQuestData : IComparable`1
{
	private const String FORMAT_AVG_ID; // 0x0
	private const String FORMAT_CG_ID; // 0x0
	public String id; // 0x10
	public Int32 sortId; // 0x18
	public SandboxV2ArchiveQuestType questType; // 0x1c
	public String name; // 0x20
	public String desc; // 0x28
	public List`1 avgDataList; // 0x30
	public List`1 cgDataList; // 0x38
	public List`1 npcPicIdList; // 0x40
	public SandboxV2ArchiveQuestZoneData zoneData; // 0x48


	// RVA: 0x34f23cc VA: 0x7595b0a3cc
	public Int32 CompareTo(SandboxV2ArchiveQuestData other) { }
	// RVA: 0x34f2418 VA: 0x7595b0a418
	public String GetAvgFuncId() { }
	// RVA: 0x34f2464 VA: 0x7595b0a464
	public String GetCgFuncId(String cgId) { }
	// RVA: 0x34f24c0 VA: 0x7595b0a4c0
	public Void .ctor() { }
}
```