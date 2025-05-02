# TrapProxy

**Namespace:** `Torappu.UI.ActArchive`


## Methods

- `Void _OnTrapItemClicked(ActArchiveType, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class TrapProxy : ActArchiveCompProxy`1
{
	public const String TRAP_TRIGGER_TYPE; // 0x0
	private static DelegateBridge __Hotfix0_get_compType; // 0x0
	private static DelegateBridge __Hotfix0_GetPrefabPath; // 0x8
	private static DelegateBridge __Hotfix0_InitComp; // 0x10
	private static DelegateBridge __Hotfix0__OnTrapItemClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	protected override String compType { get; }

	// RVA: 0x300b034 VA: 0x7595623034
	protected override String get_compType() { }
	// RVA: 0x300b0b0 VA: 0x75956230b0
	protected override String GetPrefabPath() { }
	// RVA: 0x300b138 VA: 0x7595623138
	protected override Void InitComp() { }
	// RVA: 0x300b3f0 VA: 0x75956233f0
	private Void _OnTrapItemClicked(ActArchiveType type, String capsuleId) { }
	// RVA: 0x300b504 VA: 0x7595623504
	public Void .ctor() { }
}
```