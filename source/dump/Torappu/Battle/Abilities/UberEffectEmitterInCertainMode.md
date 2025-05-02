# UberEffectEmitterInCertainMode

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Int32 _activeMode`


## Methods

- `Boolean _CheckModeValid()`

- `Void <>xLuaBaseProxy_OnCastStart()`

- `Void <>xLuaBaseProxy_OnCastFinish(FinishReason)`

- `Void <>xLuaBaseProxy_OnCastOnTarget(Entity)`

- `Void <>xLuaBaseProxy_OnEvent(Event)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class UberEffectEmitterInCertainMode : UberEffectEmitter
{
	private Int32 _activeMode; // 0x58
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x0
	private static DelegateBridge __Hotfix0_OnCastFinish; // 0x8
	private static DelegateBridge __Hotfix0_OnCastOnTarget; // 0x10
	private static DelegateBridge __Hotfix0_OnEvent; // 0x18
	private static DelegateBridge __Hotfix0__CheckModeValid; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x1ecd714 VA: 0x75944e5714
	public override Void OnCastStart() { }
	// RVA: 0x1ecd8c0 VA: 0x75944e58c0
	public override Void OnCastFinish(FinishReason reason) { }
	// RVA: 0x1ecd95c VA: 0x75944e595c
	public override Void OnCastOnTarget(Entity target) { }
	// RVA: 0x1ecd9f8 VA: 0x75944e59f8
	public override Void OnEvent(Event ev) { }
	// RVA: 0x1ecd794 VA: 0x75944e5794
	private Boolean _CheckModeValid() { }
	// RVA: 0x1ecda94 VA: 0x75944e5a94
	public Void .ctor() { }
	// RVA: 0x1ecdb00 VA: 0x75944e5b00
	private Void <>xLuaBaseProxy_OnCastStart() { }
	// RVA: 0x1ecdb04 VA: 0x75944e5b04
	private Void <>xLuaBaseProxy_OnCastFinish(FinishReason P0) { }
	// RVA: 0x1ecdb08 VA: 0x75944e5b08
	private Void <>xLuaBaseProxy_OnCastOnTarget(Entity P0) { }
	// RVA: 0x1ecdb0c VA: 0x75944e5b0c
	private Void <>xLuaBaseProxy_OnEvent(Event P0) { }
}
```