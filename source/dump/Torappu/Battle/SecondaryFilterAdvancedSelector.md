# SecondaryFilterAdvancedSelector

**Namespace:** `Torappu.Battle`


## Fields

- `SecondaryFilterType _secondaryFilter`

- `String _filterTag`

- `String _buffKey`

- `Boolean _withoutThisBuff`

- `Boolean _filterBuffSource`

- `String _excludeEnemyInRootTileAtFirst`


## Properties

- `Boolean IsFilterTag`

- `Boolean IsFilterBuff`

- `Boolean IsFilterBuffPairOr`


## Methods

- `Boolean get_IsFilterTag()`

- `Boolean get_IsFilterBuff()`

- `Boolean get_IsFilterBuffPairOr()`

- `Boolean _CheckEnemies(DoubleBufferedList`1)`

- `Boolean _CheckSecondFilter(Entity)`

- `Void <>xLuaBaseProxy_OnPostFilter(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class SecondaryFilterAdvancedSelector : AdvancedSelector
{
	private SecondaryFilterType _secondaryFilter; // 0xe8
	private String _filterTag; // 0xf0
	private String _buffKey; // 0xf8
	private Boolean _withoutThisBuff; // 0x100
	private Boolean _filterBuffSource; // 0x101
	private BuffKeyPair[] _buffKeyPairs; // 0x108
	private String _excludeEnemyInRootTileAtFirst; // 0x110
	private static DelegateBridge __Hotfix0_get_IsFilterTag; // 0x0
	private static DelegateBridge __Hotfix0_get_IsFilterBuff; // 0x8
	private static DelegateBridge __Hotfix0_get_IsFilterBuffPairOr; // 0x10
	private static DelegateBridge __Hotfix0_OnPostFilter; // 0x18
	private static DelegateBridge __Hotfix0__CheckEnemies; // 0x20
	private static DelegateBridge __Hotfix0__CheckSecondFilter; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Boolean IsFilterTag { get; }
	private Boolean IsFilterBuff { get; }
	private Boolean IsFilterBuffPairOr { get; }

	// RVA: 0x1bb952c VA: 0x75941d152c
	private Boolean get_IsFilterTag() { }
	// RVA: 0x1bb959c VA: 0x75941d159c
	private Boolean get_IsFilterBuff() { }
	// RVA: 0x1bb960c VA: 0x75941d160c
	private Boolean get_IsFilterBuffPairOr() { }
	// RVA: 0x1bb967c VA: 0x75941d167c
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1bb9a58 VA: 0x75941d1a58
	private Boolean _CheckEnemies(DoubleBufferedList`1 enemies) { }
	// RVA: 0x1bb9de0 VA: 0x75941d1de0
	private Boolean _CheckSecondFilter(Entity entity) { }
	// RVA: 0x1bba0d0 VA: 0x75941d20d0
	public Void .ctor() { }
	// RVA: 0x1bba178 VA: 0x75941d2178
	private Void <>xLuaBaseProxy_OnPostFilter(List`1 P0) { }
}
```