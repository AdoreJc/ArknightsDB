# LogProxy

**Namespace:** `Torappu.UI.ActArchive`


## Methods

- `Void _OnLogItemClicked(ActArchiveType, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class LogProxy : ActArchiveCompProxy`1
{
	private static DelegateBridge __Hotfix0_get_compType; // 0x0
	private static DelegateBridge __Hotfix0_GetPrefabPath; // 0x8
	private static DelegateBridge __Hotfix0_InitComp; // 0x10
	private static DelegateBridge __Hotfix0__OnLogItemClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	protected override String compType { get; }

	// RVA: 0x3008784 VA: 0x7595620784
	protected override String get_compType() { }
	// RVA: 0x3008800 VA: 0x7595620800
	protected override String GetPrefabPath() { }
	// RVA: 0x30088f0 VA: 0x75956208f0
	protected override Void InitComp() { }
	// RVA: 0x3008c68 VA: 0x7595620c68
	private Void _OnLogItemClicked(ActArchiveType type, String landmarkID) { }
	// RVA: 0x3008d80 VA: 0x7595620d80
	public Void .ctor() { }
}
```