# SetEffectAnimatorParameter

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `Animator m_animator`


## Properties

- `Animator animator`


## Methods

- `Animator get_animator()`

- `Void _SetBool(ParamInfo)`

- `Void _SetFloat(ParamInfo)`

- `Void _SetInt(ParamInfo)`

- `Void _SetTrigger(ParamInfo)`

- `Void <>xLuaBaseProxy_OnPlay()`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class SetEffectAnimatorParameter : Behaviour
{
	private ParamInfo[] _paramInfos; // 0x20
	private Animator m_animator; // 0x28
	private static DelegateBridge __Hotfix0_get_animator; // 0x0
	private static DelegateBridge __Hotfix0_OnPlay; // 0x8
	private static DelegateBridge __Hotfix0_OnFinish; // 0x10
	private static DelegateBridge __Hotfix0__SetBool; // 0x18
	private static DelegateBridge __Hotfix0__SetFloat; // 0x20
	private static DelegateBridge __Hotfix0__SetInt; // 0x28
	private static DelegateBridge __Hotfix0__SetTrigger; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private Animator animator { get; }

	// RVA: 0x1ff8830 VA: 0x7594610830
	private Animator get_animator() { }
	// RVA: 0x1ff8908 VA: 0x7594610908
	public override Void OnPlay() { }
	// RVA: 0x1ff8ca4 VA: 0x7594610ca4
	public override Void OnFinish() { }
	// RVA: 0x1ff8b6c VA: 0x7594610b6c
	private Void _SetBool(ParamInfo paramInfo) { }
	// RVA: 0x1ff8ad4 VA: 0x7594610ad4
	private Void _SetFloat(ParamInfo paramInfo) { }
	// RVA: 0x1ff8c0c VA: 0x7594610c0c
	private Void _SetInt(ParamInfo paramInfo) { }
	// RVA: 0x1ff8a44 VA: 0x7594610a44
	private Void _SetTrigger(ParamInfo paramInfo) { }
	// RVA: 0x1ff8dd8 VA: 0x7594610dd8
	public Void .ctor() { }
	// RVA: 0x1ff8e80 VA: 0x7594610e80
	private Void <>xLuaBaseProxy_OnPlay() { }
	// RVA: 0x1ff8e84 VA: 0x7594610e84
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```