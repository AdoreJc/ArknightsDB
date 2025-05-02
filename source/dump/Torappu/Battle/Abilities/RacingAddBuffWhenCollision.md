# RacingAddBuffWhenCollision

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Boolean _onlyAddOnce`

- `String _readyEffect`

- `Boolean m_buffAdded`


## Properties

- `Boolean onlyAddOnce`


## Methods

- `Boolean get_onlyAddOnce()`

- `Void GatherBuffs(List`1)`

- `Void GatherEffects(List`1)`

- `Void _ClearEffect()`

- `Void <>xLuaBaseProxy_OnAttached()`

- `Void <>xLuaBaseProxy_OnDetached()`

- `Void <>xLuaBaseProxy_OnRacingEvent(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class RacingAddBuffWhenCollision : RacingBaseEventListener, IBuffSource, IEffectSource
{
	private BuffData[] _buffs; // 0x30
	private Boolean _onlyAddOnce; // 0x38
	private String _readyEffect; // 0x40
	private Boolean m_buffAdded; // 0x48
	private ObjectPtr`1 m_readyEffect; // 0x50
	private static DelegateBridge __Hotfix0_get_onlyAddOnce; // 0x0
	private static DelegateBridge __Hotfix0_get_racingEvent; // 0x8
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x10
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x18
	private static DelegateBridge __Hotfix0_OnAttached; // 0x20
	private static DelegateBridge __Hotfix0_OnDetached; // 0x28
	private static DelegateBridge __Hotfix0_OnRacingEvent; // 0x30
	private static DelegateBridge __Hotfix0__ClearEffect; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	private Boolean onlyAddOnce { get; }
	protected override RacingEvent racingEvent { get; }

	// RVA: 0x1ed7b00 VA: 0x75944efb00
	private Boolean get_onlyAddOnce() { }
	// RVA: 0x1ed7b68 VA: 0x75944efb68
	protected override RacingEvent get_racingEvent() { }
	// RVA: 0x1ed7bd0 VA: 0x75944efbd0
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1ed7c7c VA: 0x75944efc7c
	public Void GatherEffects(List`1 results) { }
	// RVA: 0x1ed7d90 VA: 0x75944efd90
	protected override Void OnAttached() { }
	// RVA: 0x1ed8010 VA: 0x75944f0010
	protected override Void OnDetached() { }
	// RVA: 0x1ed82d4 VA: 0x75944f02d4
	protected override Void OnRacingEvent(Object arg) { }
	// RVA: 0x1ed81dc VA: 0x75944f01dc
	private Void _ClearEffect() { }
	// RVA: 0x1ed848c VA: 0x75944f048c
	public Void .ctor() { }
	// RVA: 0x1ed85a4 VA: 0x75944f05a4
	private Void <>xLuaBaseProxy_OnAttached() { }
	// RVA: 0x1ed85a8 VA: 0x75944f05a8
	private Void <>xLuaBaseProxy_OnDetached() { }
	// RVA: 0x1ed85ac VA: 0x75944f05ac
	private Void <>xLuaBaseProxy_OnRacingEvent(Object P0) { }
}
```