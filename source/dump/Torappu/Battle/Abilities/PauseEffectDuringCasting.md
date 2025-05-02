# PauseEffectDuringCasting

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `String _effect`

- `Event _startEv`

- `Event _endEv`


## Methods

- `Void _OnPause()`

- `Void _OnUnpause()`

- `Void <>xLuaBaseProxy_OnEvent(Event)`

- `Void <>xLuaBaseProxy_OnCastFinish(FinishReason)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class PauseEffectDuringCasting : AbstractEffectEmitter
{
	private String _effect; // 0x20
	private Event _startEv; // 0x28
	private Event _endEv; // 0x2c
	private ObjectPtr`1 m_effectHolder; // 0x30
	private static DelegateBridge __Hotfix0_OnEvent; // 0x0
	private static DelegateBridge __Hotfix0_OnCastFinish; // 0x8
	private static DelegateBridge __Hotfix0__OnPause; // 0x10
	private static DelegateBridge __Hotfix0__OnUnpause; // 0x18
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x1ed0b8c VA: 0x75944e8b8c
	public override Void OnEvent(Event ev) { }
	// RVA: 0x1ed0e88 VA: 0x75944e8e88
	public override Void OnCastFinish(FinishReason reason) { }
	// RVA: 0x1ed0c44 VA: 0x75944e8c44
	private Void _OnPause() { }
	// RVA: 0x1ed0d90 VA: 0x75944e8d90
	private Void _OnUnpause() { }
	// RVA: 0x1ed0f04 VA: 0x75944e8f04
	public override Void GatherEffects(List`1 effects) { }
	// RVA: 0x1ed1018 VA: 0x75944e9018
	public Void .ctor() { }
	// RVA: 0x1ed1094 VA: 0x75944e9094
	private Void <>xLuaBaseProxy_OnEvent(Event P0) { }
	// RVA: 0x1ed109c VA: 0x75944e909c
	private Void <>xLuaBaseProxy_OnCastFinish(FinishReason P0) { }
}
```