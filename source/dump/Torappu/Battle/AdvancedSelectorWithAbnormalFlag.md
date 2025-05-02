# AdvancedSelectorWithAbnormalFlag

**Namespace:** `Torappu.Battle`


## Fields

- `Boolean _abnormalFlagExcluded`

- `Boolean _filterAbnormalImmune`


## Methods

- `Void <>xLuaBaseProxy_OnPostFilter(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class AdvancedSelectorWithAbnormalFlag : AdvancedSelector
{
	private Boolean _abnormalFlagExcluded; // 0xe8
	private AbnormalFlag[] _abnormalFlags; // 0xf0
	private Boolean _filterAbnormalImmune; // 0xf8
	private static DelegateBridge __Hotfix0_OnPostFilter; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x1b99d84 VA: 0x75941b1d84
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1b99fc0 VA: 0x75941b1fc0
	public Void .ctor() { }
	// RVA: 0x1b9a02c VA: 0x75941b202c
	private Void <>xLuaBaseProxy_OnPostFilter(List`1 P0) { }
}
```