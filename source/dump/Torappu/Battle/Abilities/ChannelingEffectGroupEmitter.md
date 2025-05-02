# ChannelingEffectGroupEmitter

**Namespace:** `Torappu.Battle.Abilities`


## Methods

- `Void _OnExtraAttackFired(Object)`

- `Void _StopEffectGroupIfNot(EventGroup)`

- `Void _ClearEffectGroupIfNot(EventGroup)`

- `Void _ClearAllEffectGroupIfNot()`

- `Void <>xLuaBaseProxy_OnEvent(Event)`

- `Void <>xLuaBaseProxy_OnCastStart()`

- `Void <>xLuaBaseProxy_OnCastFinish(FinishReason)`

- `Void <>xLuaBaseProxy_OnTick(FP)`

- `Void <>xLuaBaseProxy_GatherEffects(List`1)`

- `Void <>xLuaBaseProxy_OnAttackFinished(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class ChannelingEffectGroupEmitter : ChannelingEffectEmitter
{
	private List`1 _extraEventGroup; // 0x60
	private Dictionary`2 m_effectHolderDict; // 0x68
	private static DelegateBridge __Hotfix0_OnEvent; // 0x0
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x8
	private static DelegateBridge __Hotfix0_OnCastFinish; // 0x10
	private static DelegateBridge __Hotfix0_OnTick; // 0x18
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x20
	private static DelegateBridge __Hotfix0_OnAttackFinished; // 0x28
	private static DelegateBridge __Hotfix0__OnExtraAttackFired; // 0x30
	private static DelegateBridge __Hotfix0__StopEffectGroupIfNot; // 0x38
	private static DelegateBridge __Hotfix0__ClearEffectGroupIfNot; // 0x40
	private static DelegateBridge __Hotfix0__ClearAllEffectGroupIfNot; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x1ec2154 VA: 0x75944da154
	public override Void OnEvent(Event ev) { }
	// RVA: 0x1ec2980 VA: 0x75944da980
	public override Void OnCastStart() { }
	// RVA: 0x1ec2a78 VA: 0x75944daa78
	public override Void OnCastFinish(FinishReason reason) { }
	// RVA: 0x1ec2b00 VA: 0x75944dab00
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1ec2cd8 VA: 0x75944dacd8
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x1ec2e5c VA: 0x75944dae5c
	protected override Void OnAttackFinished(Object arg) { }
	// RVA: 0x1ec2ff4 VA: 0x75944daff4
	private Void _OnExtraAttackFired(Object arg) { }
	// RVA: 0x1ec286c VA: 0x75944da86c
	private Void _StopEffectGroupIfNot(EventGroup eventGroup) { }
	// RVA: 0x1ec270c VA: 0x75944da70c
	private Void _ClearEffectGroupIfNot(EventGroup eventGroup) { }
	// RVA: 0x1ec24c4 VA: 0x75944da4c4
	private Void _ClearAllEffectGroupIfNot() { }
	// RVA: 0x1ec3228 VA: 0x75944db228
	public Void .ctor() { }
	// RVA: 0x1ec32e8 VA: 0x75944db2e8
	private Void <>xLuaBaseProxy_OnEvent(Event P0) { }
	// RVA: 0x1ec32ec VA: 0x75944db2ec
	private Void <>xLuaBaseProxy_OnCastStart() { }
	// RVA: 0x1ec32f0 VA: 0x75944db2f0
	private Void <>xLuaBaseProxy_OnCastFinish(FinishReason P0) { }
	// RVA: 0x1ec32f4 VA: 0x75944db2f4
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
	// RVA: 0x1ec32f8 VA: 0x75944db2f8
	private Void <>xLuaBaseProxy_GatherEffects(List`1 P0) { }
	// RVA: 0x1ec32fc VA: 0x75944db2fc
	private Void <>xLuaBaseProxy_OnAttackFinished(Object P0) { }
}
```