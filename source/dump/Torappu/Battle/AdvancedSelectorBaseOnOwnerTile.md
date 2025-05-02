# AdvancedSelectorBaseOnOwnerTile

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _filterEnemyMassLevel`

- `CompareType _massLevelCondType`

- `Int32 _massLevelToCompare`


## Properties

- `Boolean filterEnemyMassLevel`


## Methods

- `Boolean get_filterEnemyMassLevel()`

- `Void <>xLuaBaseProxy_OnPostFilter(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class AdvancedSelectorBaseOnOwnerTile : AdvancedSelector
{
	private Boolean _filterEnemyMassLevel; // 0xe8
	private CompareType _massLevelCondType; // 0xec
	private Int32 _massLevelToCompare; // 0xf0
	private static DelegateBridge __Hotfix0_get_filterEnemyMassLevel; // 0x0
	private static DelegateBridge __Hotfix0_OnPostFilter; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	private Boolean filterEnemyMassLevel { get; }

	// RVA: 0x1b991f0 VA: 0x75941b11f0
	private Boolean get_filterEnemyMassLevel() { }
	// RVA: 0x1b99258 VA: 0x75941b1258
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1b995e8 VA: 0x75941b15e8
	public Void .ctor() { }
	// RVA: 0x1b9965c VA: 0x75941b165c
	private Void <>xLuaBaseProxy_OnPostFilter(List`1 P0) { }
}
```