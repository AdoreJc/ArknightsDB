# AdvancedSelectorInSandbox

**Namespace:** `Torappu.Battle`


## Fields

- `SandboxFilterType _filter`

- `String _filterTag`

- `Boolean _buffKeyExcluded`


## Properties

- `Enemy ownerE`


## Methods

- `Enemy get_ownerE()`

- `Boolean _Filter_TransferRes(Entity, Entity, out, out)`

- `Void _CheckBuff(IList`1, String)`

- `Void <>xLuaBaseProxy_OnPostFilter(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class AdvancedSelectorInSandbox : AdvancedSelector
{
	private SandboxFilterType _filter; // 0xe8
	private String _filterTag; // 0xf0
	private List`1 _buffs; // 0xf8
	private Boolean _buffKeyExcluded; // 0x100
	private static DelegateBridge __Hotfix0_get_ownerE; // 0x0
	private static DelegateBridge __Hotfix0_OnPostFilter; // 0x8
	private static DelegateBridge __Hotfix0__Filter_TransferRes; // 0x10
	private static DelegateBridge __Hotfix0__CheckBuff; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Enemy ownerE { get; }

	// RVA: 0x1bbbdb4 VA: 0x75941d3db4
	private Enemy get_ownerE() { }
	// RVA: 0x1bbbe6c VA: 0x75941d3e6c
	protected override Void OnPostFilter(List`1 candidates) { }
	// RVA: 0x1bbc908 VA: 0x75941d4908
	private Boolean _Filter_TransferRes(Entity candidate, Entity source, out FP weight, out FP priorWeight) { }
	// RVA: 0x1bbc6e4 VA: 0x75941d46e4
	private Void _CheckBuff(IList`1 candidates, String buffKey) { }
	// RVA: 0x1bbcacc VA: 0x75941d4acc
	public Void .ctor() { }
	// RVA: 0x1bbcb74 VA: 0x75941d4b74
	private Void <>xLuaBaseProxy_OnPostFilter(List`1 P0) { }
}
```