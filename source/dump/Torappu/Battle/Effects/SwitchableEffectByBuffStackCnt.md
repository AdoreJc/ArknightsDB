# SwitchableEffectByBuffStackCnt

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `String _buffKey`

- `String _effect`

- `Int32 _stackCnt`

- `CompareType _compareType`

- `Single _updateInterval`

- `Boolean _updateOnPlay`

- `Boolean _onlyUpdateOnPlay`

- `Single m_updateInterval`


## Methods

- `Void GatherEffects(List`1)`

- `Void Update()`

- `Void _UpdateEffectWithBuffCnt()`

- `Void _FinishStackEffect()`

- `Void ChangeEffectsExt(String)`

- `Void <>xLuaBaseProxy_OnPlay()`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class SwitchableEffectByBuffStackCnt : Behaviour, IEffectSource, IHookEffectBehaviour
{
	private String _buffKey; // 0x20
	private String _effect; // 0x28
	private Int32 _stackCnt; // 0x30
	private CompareType _compareType; // 0x34
	private Single _updateInterval; // 0x38
	private Boolean _updateOnPlay; // 0x3c
	private Boolean _onlyUpdateOnPlay; // 0x3d
	private Single m_updateInterval; // 0x40
	private ObjectPtr`1 m_stackEffect; // 0x48
	private static DelegateBridge __Hotfix0_OnPlay; // 0x0
	private static DelegateBridge __Hotfix0_GatherEffects; // 0x8
	private static DelegateBridge __Hotfix0_OnFinish; // 0x10
	private static DelegateBridge __Hotfix0_Update; // 0x18
	private static DelegateBridge __Hotfix0__UpdateEffectWithBuffCnt; // 0x20
	private static DelegateBridge __Hotfix0__FinishStackEffect; // 0x28
	private static DelegateBridge __Hotfix0_ChangeEffectsExt; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x200f700 VA: 0x7594627700
	public override Void OnPlay() { }
	// RVA: 0x200fa50 VA: 0x7594627a50
	public Void GatherEffects(List`1 effects) { }
	// RVA: 0x200fb64 VA: 0x7594627b64
	public override Void OnFinish() { }
	// RVA: 0x200fcd0 VA: 0x7594627cd0
	private Void Update() { }
	// RVA: 0x200f798 VA: 0x7594627798
	private Void _UpdateEffectWithBuffCnt() { }
	// RVA: 0x200fbd8 VA: 0x7594627bd8
	private Void _FinishStackEffect() { }
	// RVA: 0x200fd98 VA: 0x7594627d98
	public Void ChangeEffectsExt(String ext) { }
	// RVA: 0x200fe10 VA: 0x7594627e10
	public Void .ctor() { }
	// RVA: 0x200fed4 VA: 0x7594627ed4
	private Void <>xLuaBaseProxy_OnPlay() { }
	// RVA: 0x200fedc VA: 0x7594627edc
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```