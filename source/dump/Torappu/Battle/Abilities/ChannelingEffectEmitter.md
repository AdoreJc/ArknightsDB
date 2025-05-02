# ChannelingEffectEmitter

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Event _playOnEvent`

- `String _effect`

- `Event _stopOnEvent`

- `Boolean _stopOnAttackFinished`

- `String _hitEffect`

- `Boolean m_casted`

- `Boolean m_stopped`

- `FP m_nextEscapeTime`


## Properties

- `FP nextEscapeTime`


## Methods

- `FP get_nextEscapeTime()`

- `Void _StopEffectIfNot()`

- `Void _ClearEffectIfNot()`

- `Void <>xLuaBaseProxy_OnEvent(Event)`

- `Void <>xLuaBaseProxy_OnCastOnTarget(Entity)`

- `Void <>xLuaBaseProxy_OnCastStart()`

- `Void <>xLuaBaseProxy_OnCastFinish(FinishReason)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class ChannelingEffectEmitter : AbstractEffectEmitter
{
	private Event _playOnEvent; // 0x20
	private String _effect; // 0x28
	private Event _stopOnEvent; // 0x30
	private Boolean _stopOnAttackFinished; // 0x34
	private String _hitEffect; // 0x38
	private Boolean m_casted; // 0x40
	private Boolean m_stopped; // 0x41
	private FP m_nextEscapeTime; // 0x48
	private ObjectPtr`1 m_effectHolder; // 0x50
	private static DelegateBridge __Hotfix0_get_nextEscapeTime; // 0x0
	private static DelegateBridge __Hotfix0_OnEvent; // 0x8
	private static DelegateBridge __Hotfix0_OnCastOnTarget; // 0x10
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x18
	private static DelegateBridge __Hotfix0_OnCastFinish; // 0x20
	private static DelegateBridge __Hotfix0_OnTick; // 0x28
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x30
	private static DelegateBridge __Hotfix0_OnAttackFinished; // 0x38
	private static DelegateBridge __Hotfix0__StopEffectIfNot; // 0x40
	private static DelegateBridge __Hotfix0__ClearEffectIfNot; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	protected FP nextEscapeTime { get; }

	// RVA: 0x1ec1628 VA: 0x75944d9628
	protected FP get_nextEscapeTime() { }
	// RVA: 0x1ec1690 VA: 0x75944d9690
	public override Void OnEvent(Event ev) { }
	// RVA: 0x1ec1ba0 VA: 0x75944d9ba0
	public override Void OnCastOnTarget(Entity target) { }
	// RVA: 0x1ec1d18 VA: 0x75944d9d18
	public override Void OnCastStart() { }
	// RVA: 0x1ec1d88 VA: 0x75944d9d88
	public override Void OnCastFinish(FinishReason reason) { }
	// RVA: 0x1ec1e04 VA: 0x75944d9e04
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1ec1f08 VA: 0x75944d9f08
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x1ec201c VA: 0x75944da01c
	protected virtual Void OnAttackFinished(Object arg) { }
	// RVA: 0x1ec1a30 VA: 0x75944d9a30
	private Void _StopEffectIfNot() { }
	// RVA: 0x1ec1938 VA: 0x75944d9938
	private Void _ClearEffectIfNot() { }
	// RVA: 0x1ec20b0 VA: 0x75944da0b0
	public Void .ctor() { }
	// RVA: 0x1ec212c VA: 0x75944da12c
	private Void <>xLuaBaseProxy_OnEvent(Event P0) { }
	// RVA: 0x1ec2134 VA: 0x75944da134
	private Void <>xLuaBaseProxy_OnCastOnTarget(Entity P0) { }
	// RVA: 0x1ec213c VA: 0x75944da13c
	private Void <>xLuaBaseProxy_OnCastStart() { }
	// RVA: 0x1ec2144 VA: 0x75944da144
	private Void <>xLuaBaseProxy_OnCastFinish(FinishReason P0) { }
	// RVA: 0x1ec214c VA: 0x75944da14c
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```