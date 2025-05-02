# AchievementProxy

**Namespace:** `Torappu.UI.ActArchive`


## Methods

- `Void _OnGotFilterSelectionChange(GotType)`

- `Void _OnFilterChange(FilterType, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class AchievementProxy : ActArchiveCompProxy`1
{
	private static DelegateBridge __Hotfix0_get_compType; // 0x0
	private static DelegateBridge __Hotfix0_GetPrefabPath; // 0x8
	private static DelegateBridge __Hotfix0_InitComp; // 0x10
	private static DelegateBridge __Hotfix0__OnGotFilterSelectionChange; // 0x18
	private static DelegateBridge __Hotfix0__OnFilterChange; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	protected override String compType { get; }

	// RVA: 0x30110cc VA: 0x75956290cc
	protected override String get_compType() { }
	// RVA: 0x3011148 VA: 0x7595629148
	protected override String GetPrefabPath() { }
	// RVA: 0x30111b8 VA: 0x75956291b8
	protected override Void InitComp() { }
	// RVA: 0x30115ec VA: 0x75956295ec
	private Void _OnGotFilterSelectionChange(GotType type) { }
	// RVA: 0x3011b00 VA: 0x7595629b00
	private Void _OnFilterChange(FilterType filterType, String value) { }
	// RVA: 0x3011ce4 VA: 0x7595629ce4
	public Void .ctor() { }
}
```