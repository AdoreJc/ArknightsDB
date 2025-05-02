# ArchiveBuffModel

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `String selectedBuffId`


## Methods

- `String GetDefaultItemId()`

- `Void LoadData(String, RoguelikeArchiveComponentData, ActArchiveInfo)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveBuffModel : IHotfixable
{
	public ListDict`2 buffItems; // 0x10
	public String selectedBuffId; // 0x18
	public List`1 buffGroups; // 0x20
	private static DelegateBridge __Hotfix0_GetDefaultItemId; // 0x0
	private static DelegateBridge __Hotfix0_LoadData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x30381b4 VA: 0x75956501b4
	public String GetDefaultItemId() { }
	// RVA: 0x303968c VA: 0x759565168c
	public Void LoadData(String archiveId, RoguelikeArchiveComponentData compData, ActArchiveInfo archiveInfo) { }
	// RVA: 0x3039dc0 VA: 0x7595651dc0
	public Void .ctor() { }
}
```