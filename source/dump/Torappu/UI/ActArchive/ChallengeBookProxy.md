# ChallengeBookProxy

**Namespace:** `Torappu.UI.ActArchive`


## Methods

- `Void _OnItemClicked(ActArchiveType, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ChallengeBookProxy : ActArchiveCompProxy`1
{
	private static DelegateBridge __Hotfix0_get_compType; // 0x0
	private static DelegateBridge __Hotfix0_GetPrefabPath; // 0x8
	private static DelegateBridge __Hotfix0_InitComp; // 0x10
	private static DelegateBridge __Hotfix0__OnItemClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	protected override String compType { get; }

	// RVA: 0x3010c44 VA: 0x7595628c44
	protected override String get_compType() { }
	// RVA: 0x3010cc0 VA: 0x7595628cc0
	protected override String GetPrefabPath() { }
	// RVA: 0x3010d48 VA: 0x7595628d48
	protected override Void InitComp() { }
	// RVA: 0x3010f20 VA: 0x7595628f20
	private Void _OnItemClicked(ActArchiveType type, String id) { }
	// RVA: 0x301103c VA: 0x759562903c
	public Void .ctor() { }
}
```