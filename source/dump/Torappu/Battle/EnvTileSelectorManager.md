# EnvTileSelectorManager

**Namespace:** `Torappu.Battle`


## Fields

- `String _bornEvent`

- `FilterType _tileFilterType`


## Methods

- `Void _OnUnitBorn(Object)`

- `Void <>xLuaBaseProxy_UpdateCandidates()`

- `Void <>xLuaBaseProxy_FilterTargets()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class EnvTileSelectorManager : PeriodicTriggerManager
{
	private String _bornEvent; // 0xa8
	private List`1 _entityIdList; // 0xb0
	private FilterType _tileFilterType; // 0xb8
	private static DelegateBridge __Hotfix0_get_eventGroups; // 0x0
	private static DelegateBridge __Hotfix0__OnUnitBorn; // 0x8
	private static DelegateBridge __Hotfix0_UpdateCandidates; // 0x10
	private static DelegateBridge __Hotfix0_FilterTargets; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public override IEnumerable`1 eventGroups { get; }

	// RVA: 0x404b360 VA: 0x7596663360
	public override IEnumerable`1 get_eventGroups() { }
	// RVA: 0x404b4cc VA: 0x75966634cc
	private Void _OnUnitBorn(Object arg) { }
	// RVA: 0x404b664 VA: 0x7596663664
	public override Void UpdateCandidates() { }
	// RVA: 0x404bab8 VA: 0x7596663ab8
	public override Void FilterTargets() { }
	// RVA: 0x404bb58 VA: 0x7596663b58
	public Void .ctor() { }
	// RVA: 0x404bbc8 VA: 0x7596663bc8
	private IEnumerable`1 <>xLuaBaseProxy_get_eventGroups() { }
	// RVA: 0x404bbd0 VA: 0x7596663bd0
	private Void <>xLuaBaseProxy_UpdateCandidates() { }
	// RVA: 0x404bbd8 VA: 0x7596663bd8
	private Void <>xLuaBaseProxy_FilterTargets() { }
}
```