# ArchiveCapsuleModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `String selectedCapsuleId`


## Methods

- `String GetDefaultItemId()`

- `Void LoadData(String, RoguelikeArchiveComponentData, ActArchiveInfo)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveCapsuleModel : IHotfixable
{
	public ListDict`2 capsuleItems; // 0x10
	public String selectedCapsuleId; // 0x18
	private static DelegateBridge __Hotfix0_GetDefaultItemId; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x303bf40 VA: 0x7595653f40
	public String GetDefaultItemId() { }
	// RVA: 0x303c028 VA: 0x7595654028
	public Void LoadData(String archiveId, RoguelikeArchiveComponentData compData, ActArchiveInfo archiveInfo) { }
	// RVA: 0x303c6c0 VA: 0x75956546c0
	public Void .ctor() { }
}
```