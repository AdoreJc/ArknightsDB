# RangeEffectEmitter

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Event _playCastEffectOnEvent`

- `Event _stopCastEffectOnEvent`

- `Boolean _onlyCastOnce`

- `Boolean _oneShot`

- `Boolean _holdByOwner`

- `Boolean m_casted`


## Methods

- `Void _ClearEffects()`

- `Void <OnEvent>b__8_0(Tile)`

- `Void <>xLuaBaseProxy_OnEvent(Event)`

- `Void <>xLuaBaseProxy_OnCastStart()`

- `Void <>xLuaBaseProxy_OnCastFinish(FinishReason)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class RangeEffectEmitter : AbstractEffectEmitter
{
	private Event _playCastEffectOnEvent; // 0x20
	private String[] _castEffects; // 0x28
	private Event _stopCastEffectOnEvent; // 0x30
	private Boolean _onlyCastOnce; // 0x34
	private Boolean _oneShot; // 0x35
	private Boolean _holdByOwner; // 0x36
	private Boolean m_casted; // 0x37
	private List`1 m_effects; // 0x38
	private static DelegateBridge __Hotfix0_OnEvent; // 0x0
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x8
	private static DelegateBridge __Hotfix0_OnCastFinish; // 0x10
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x18
	private static DelegateBridge __Hotfix0__ClearEffects; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x1ec8c70 VA: 0x75944e0c70
	public override Void OnEvent(Event ev) { }
	// RVA: 0x1ec8ff4 VA: 0x75944e0ff4
	public override Void OnCastStart() { }
	// RVA: 0x1ec9070 VA: 0x75944e1070
	public override Void OnCastFinish(FinishReason reason) { }
	// RVA: 0x1ec90fc VA: 0x75944e10fc
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x1ec8e84 VA: 0x75944e0e84
	private Void _ClearEffects() { }
	// RVA: 0x1ec91b0 VA: 0x75944e11b0
	public Void .ctor() { }
	// RVA: 0x1ec9284 VA: 0x75944e1284
	private Void <OnEvent>b__8_0(Tile tile) { }
	// RVA: 0x1ec9434 VA: 0x75944e1434
	private Void <>xLuaBaseProxy_OnEvent(Event P0) { }
	// RVA: 0x1ec943c VA: 0x75944e143c
	private Void <>xLuaBaseProxy_OnCastStart() { }
	// RVA: 0x1ec9444 VA: 0x75944e1444
	private Void <>xLuaBaseProxy_OnCastFinish(FinishReason P0) { }
}
```