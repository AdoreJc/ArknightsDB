# ArchiveTrapModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `String selectedTrapId`

- `Int32 selectLineNum`


## Methods

- `String GetDefaultItemId()`

- `Void LoadData(String, RoguelikeArchiveComponentData, ActArchiveInfo)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveTrapModel : IHotfixable
{
	public ListDict`2 trapItems; // 0x10
	public String selectedTrapId; // 0x18
	public Int32 selectLineNum; // 0x20
	private static DelegateBridge __Hotfix0_GetDefaultItemId; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x308fcd0 VA: 0x75956a7cd0
	public String GetDefaultItemId() { }
	// RVA: 0x308fdb8 VA: 0x75956a7db8
	public Void LoadData(String archiveId, RoguelikeArchiveComponentData compData, ActArchiveInfo archiveInfo) { }
	// RVA: 0x3090478 VA: 0x75956a8478
	public Void .ctor() { }
}
```