# AdvancedSelectorWithTagAndBuffKey

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _tagExcluded`

- `String _filterTag`

- `Boolean _buffKeyExcluded`

- `String _buffKey`

- `Boolean _checkOrInsteadOfAnd`

- `Boolean _filterBuffSource`

- `Boolean _filterTokenHost`


## Properties

- `Boolean buffsNotEmpty`


## Methods

- `Boolean get_buffsNotEmpty()`

- `Void _CheckBuff(List`1, String)`

- `Void <>xLuaBaseProxy_OnPostFilter(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class AdvancedSelectorWithTagAndBuffKey : AdvancedSelector
{
	private Boolean _tagExcluded; // 0xe8
	private String _filterTag; // 0xf0
	private List`1 _filterTagList; // 0xf8
	private Boolean _buffKeyExcluded; // 0x100
	private String _buffKey; // 0x108
	private List`1 _buffs; // 0x110
	private Boolean _checkOrInsteadOfAnd; // 0x118
	private Boolean _filterBuffSource; // 0x119
	private Boolean _filterTokenHost; // 0x11a
	private static DelegateBridge __Hotfix0_get_buffsNotEmpty; // 0x0
	private static DelegateBridge __Hotfix0_OnPostFilter; // 0x8
	private static DelegateBridge __Hotfix0__CheckBuff; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	private Boolean buffsNotEmpty { get; }

	// RVA: 0x1b9f1c0 VA: 0x75941b71c0
	private Boolean get_buffsNotEmpty() { }
	// RVA: 0x1b9f24c VA: 0x75941b724c
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1b9f6d0 VA: 0x75941b76d0
	private Void _CheckBuff(List`1 candidates, String buffKey) { }
	// RVA: 0x1b9f99c VA: 0x75941b799c
	public Void .ctor() { }
	// RVA: 0x1b9fa60 VA: 0x75941b7a60
	private Void <>xLuaBaseProxy_OnPostFilter(List`1 P0) { }
}
```