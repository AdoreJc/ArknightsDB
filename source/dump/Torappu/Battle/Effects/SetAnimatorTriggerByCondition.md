# SetAnimatorTriggerByCondition

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `AnimatorTriggerSource _source`

- `Boolean _autoFindSource`

- `Boolean _isally`

- `Animator m_animator`

- `String m_cachedValue`

- `Boolean m_hasPlayed`

- `Boolean m_cacheBool`

- `AnimatorTriggerSource m_source`


## Properties

- `Animator animator`

- `AnimatorTriggerSource source`


## Methods

- `Animator get_animator()`

- `AnimatorTriggerSource get_source()`

- `Void Update()`

- `Void _UpdateAnimator()`

- `Void <>xLuaBaseProxy_OnPlay()`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class SetAnimatorTriggerByCondition : Behaviour
{
	private AnimatorTriggerSource _source; // 0x20
	private Boolean _autoFindSource; // 0x28
	private Boolean _isally; // 0x29
	private Animator m_animator; // 0x30
	private String m_cachedValue; // 0x38
	private Boolean m_hasPlayed; // 0x40
	private Boolean m_cacheBool; // 0x41
	private AnimatorTriggerSource m_source; // 0x48
	private static DelegateBridge __Hotfix0_get_animator; // 0x0
	private static DelegateBridge __Hotfix0_get_source; // 0x8
	private static DelegateBridge __Hotfix0_OnPlay; // 0x10
	private static DelegateBridge __Hotfix0_Update; // 0x18
	private static DelegateBridge __Hotfix0__UpdateAnimator; // 0x20
	private static DelegateBridge __Hotfix0_OnFinish; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Animator animator { get; }
	private AnimatorTriggerSource source { get; }

	// RVA: 0x1ff8354 VA: 0x7594610354
	private Animator get_animator() { }
	// RVA: 0x1ff842c VA: 0x759461042c
	private AnimatorTriggerSource get_source() { }
	// RVA: 0x1ff8514 VA: 0x7594610514
	public override Void OnPlay() { }
	// RVA: 0x1ff85e0 VA: 0x75946105e0
	private Void Update() { }
	// RVA: 0x1ff865c VA: 0x759461065c
	private Void _UpdateAnimator() { }
	// RVA: 0x1ff874c VA: 0x759461074c
	public override Void OnFinish() { }
	// RVA: 0x1ff87bc VA: 0x75946107bc
	public Void .ctor() { }
	// RVA: 0x1ff8828 VA: 0x7594610828
	private Void <>xLuaBaseProxy_OnPlay() { }
	// RVA: 0x1ff882c VA: 0x759461082c
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```