# SwitchableEffectByFaceDirection

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `String _upEffect`

- `String _downEffect`


## Methods

- `Void GatherEffects(List`1)`

- `Void _UpdateFace()`

- `Void <>xLuaBaseProxy_OnPlay()`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class SwitchableEffectByFaceDirection : Behaviour, IEffectSource
{
	private String _upEffect; // 0x20
	private String _downEffect; // 0x28
	private ObjectPtr`1 m_downEffect; // 0x30
	private ObjectPtr`1 m_upEffect; // 0x40
	private static DelegateBridge __Hotfix0_OnPlay; // 0x0
	private static DelegateBridge __Hotfix0_OnFinish; // 0x8
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x10
	private static DelegateBridge __Hotfix0__UpdateFace; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x200fee4 VA: 0x7594627ee4
	public override Void OnPlay() { }
	// RVA: 0x20102f0 VA: 0x75946282f0
	public override Void OnFinish() { }
	// RVA: 0x2010450 VA: 0x7594628450
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x200ff58 VA: 0x7594627f58
	private Void _UpdateFace() { }
	// RVA: 0x20105d4 VA: 0x75946285d4
	public Void .ctor() { }
	// RVA: 0x2010644 VA: 0x7594628644
	private Void <>xLuaBaseProxy_OnPlay() { }
	// RVA: 0x201064c VA: 0x759462864c
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```