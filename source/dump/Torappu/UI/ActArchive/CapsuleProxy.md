# CapsuleProxy

**Namespace:** `Torappu.UI.ActArchive`


## Methods

- `Void _OnCapsuleItemClicked(ActArchiveType, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class CapsuleProxy : ActArchiveCompProxy`1
{
	private static DelegateBridge __Hotfix0_get_compType; // 0x0
	private static DelegateBridge __Hotfix0_GetPrefabPath; // 0x8
	private static DelegateBridge __Hotfix0_InitComp; // 0x10
	private static DelegateBridge __Hotfix0__OnCapsuleItemClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	protected override String compType { get; }

	// RVA: 0x300b594 VA: 0x7595623594
	protected override String get_compType() { }
	// RVA: 0x300b610 VA: 0x7595623610
	protected override String GetPrefabPath() { }
	// RVA: 0x300b698 VA: 0x7595623698
	protected override Void InitComp() { }
	// RVA: 0x300b950 VA: 0x7595623950
	private Void _OnCapsuleItemClicked(ActArchiveType type, String capsuleId) { }
	// RVA: 0x300ba64 VA: 0x7595623a64
	public Void .ctor() { }
}
```