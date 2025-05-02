# RelicProxy

**Namespace:** `Torappu.UI.ActArchive`


## Methods

- `Void _OnRelicItemClicked(ActArchiveType, String)`

- `Void _OnFilterMethodClicked(FilterRule)`

- `Void _OnSwitchDifficultyClicked(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class RelicProxy : ActArchiveCompProxy`1
{
	private static DelegateBridge __Hotfix0_get_compType; // 0x0
	private static DelegateBridge __Hotfix0_GetPrefabPath; // 0x8
	private static DelegateBridge __Hotfix0_InitComp; // 0x10
	private static DelegateBridge __Hotfix0__OnRelicItemClicked; // 0x18
	private static DelegateBridge __Hotfix0__OnFilterMethodClicked; // 0x20
	private static DelegateBridge __Hotfix0__OnSwitchDifficultyClicked; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	protected override String compType { get; }

	// RVA: 0x300baf4 VA: 0x7595623af4
	protected override String get_compType() { }
	// RVA: 0x300bb70 VA: 0x7595623b70
	protected override String GetPrefabPath() { }
	// RVA: 0x300bbf8 VA: 0x7595623bf8
	protected override Void InitComp() { }
	// RVA: 0x300bf70 VA: 0x7595623f70
	private Void _OnRelicItemClicked(ActArchiveType type, String relicID) { }
	// RVA: 0x300c084 VA: 0x7595624084
	private Void _OnFilterMethodClicked(FilterRule rule) { }
	// RVA: 0x300c188 VA: 0x7595624188
	private Void _OnSwitchDifficultyClicked(Int32 toward) { }
	// RVA: 0x300c28c VA: 0x759562428c
	public Void .ctor() { }
}
```