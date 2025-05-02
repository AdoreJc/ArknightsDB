# BuffToOwnerDuringAbility

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Event _startEvent`

- `Event _endEvent`

- `Boolean _forceFinishBuffOnCastEnd`

- `Boolean m_buffAdded`


## Methods

- `Void GatherEffects(List`1)`

- `Void GatherBuffs(List`1)`

- `Void _AddBuffs()`

- `Void _ClearBuffs()`

- `Void <>xLuaBaseProxy_OnEvent(Event)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class BuffToOwnerDuringAbility : Behaviour, IEffectSource, IBuffSource
{
	private Event _startEvent; // 0x20
	private Event _endEvent; // 0x24
	private BuffData[] _buffs; // 0x28
	private Boolean _forceFinishBuffOnCastEnd; // 0x30
	private List`1 m_buffUid; // 0x38
	private Boolean m_buffAdded; // 0x40
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x0
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x8
	private static DelegateBridge __Hotfix0__AddBuffs; // 0x10
	private static DelegateBridge __Hotfix0__ClearBuffs; // 0x18
	private static DelegateBridge __Hotfix0_OnEvent; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x1ebf0fc VA: 0x75944d70fc
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x1ebf180 VA: 0x75944d7180
	public Void GatherBuffs(List`1 results) { }
	// RVA: 0x1ebf220 VA: 0x75944d7220
	private Void _AddBuffs() { }
	// RVA: 0x1ebf37c VA: 0x75944d737c
	private Void _ClearBuffs() { }
	// RVA: 0x1ebf46c VA: 0x75944d746c
	public override Void OnEvent(Event ev) { }
	// RVA: 0x1ebf570 VA: 0x75944d7570
	public Void .ctor() { }
	// RVA: 0x1ebf670 VA: 0x75944d7670
	private Void <>xLuaBaseProxy_OnEvent(Event P0) { }
}
```