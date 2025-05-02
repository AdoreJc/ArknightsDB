# SwitchableWhenContainsEquipment

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `Boolean _pauseWhenSwitch`


## Methods

- `Boolean ContainsEquipmentPair(UniqueEquipPair)`

- `Boolean TryGetEquipmentEffectHookSchema(UniqueEquipPair, ref)`

- `Void _TrySpawnHookEffect()`

- `Void _DestroySpawnedHookEffect()`

- `Void GatherEffects(List`1)`

- `Void <>xLuaBaseProxy_OnPlay()`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class SwitchableWhenContainsEquipment : Behaviour, IEffectSource
{
	private Boolean _pauseWhenSwitch; // 0x20
	private List`1 _equipmentEffectHookSchemas; // 0x28
	private ObjectPtr`1 m_spawnedHookEffect; // 0x30
	private static DelegateBridge __Hotfix0_get_equipmentEffectHookSchemas; // 0x0
	private static DelegateBridge __Hotfix0_OnPlay; // 0x8
	private static DelegateBridge __Hotfix0_OnFinish; // 0x10
	private static DelegateBridge __Hotfix0_ContainsEquipmentPair; // 0x18
	private static DelegateBridge __Hotfix0_TryGetEquipmentEffectHookSchema; // 0x20
	private static DelegateBridge __Hotfix0__TrySpawnHookEffect; // 0x28
	private static DelegateBridge __Hotfix0__DestroySpawnedHookEffect; // 0x30
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public List`1 equipmentEffectHookSchemas { get; }

	// RVA: 0x20121b0 VA: 0x759462a1b0
	public List`1 get_equipmentEffectHookSchemas() { }
	// RVA: 0x2012218 VA: 0x759462a218
	public override Void OnPlay() { }
	// RVA: 0x2012698 VA: 0x759462a698
	public override Void OnFinish() { }
	// RVA: 0x2012804 VA: 0x759462a804
	public Boolean ContainsEquipmentPair(UniqueEquipPair uniqueEquipPair) { }
	// RVA: 0x20129cc VA: 0x759462a9cc
	public Boolean TryGetEquipmentEffectHookSchema(UniqueEquipPair uniqueEquipPair, ref EquipmentEffectHookSchema outEquipmentEffectHookSchema) { }
	// RVA: 0x201228c VA: 0x759462a28c
	private Void _TrySpawnHookEffect() { }
	// RVA: 0x201270c VA: 0x759462a70c
	private Void _DestroySpawnedHookEffect() { }
	// RVA: 0x2012bd0 VA: 0x759462abd0
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x2012f54 VA: 0x759462af54
	public Void .ctor() { }
	// RVA: 0x2013018 VA: 0x759462b018
	private Void <>xLuaBaseProxy_OnPlay() { }
	// RVA: 0x2013020 VA: 0x759462b020
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```