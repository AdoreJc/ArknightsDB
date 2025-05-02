# SetAnimatorFloatByCondition

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `String _paramName`

- `AnimatorFloatSource _source`

- `Boolean _isInt`

- `Animator m_animator`

- `Single m_cachedValue`

- `Boolean m_hasPlayed`


## Properties

- `Animator animator`


## Methods

- `Animator get_animator()`

- `Void Update()`

- `Void _UpdateAnimator()`

- `Void <>xLuaBaseProxy_OnPlay()`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class SetAnimatorFloatByCondition : Behaviour
{
	private String _paramName; // 0x20
	private AnimatorFloatSource _source; // 0x28
	private Boolean _isInt; // 0x30
	private Animator m_animator; // 0x38
	private Single m_cachedValue; // 0x40
	private Boolean m_hasPlayed; // 0x44
	private static DelegateBridge __Hotfix0_get_animator; // 0x0
	private static DelegateBridge __Hotfix0_OnPlay; // 0x8
	private static DelegateBridge __Hotfix0_Update; // 0x10
	private static DelegateBridge __Hotfix0__UpdateAnimator; // 0x18
	private static DelegateBridge __Hotfix0_OnFinish; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Animator animator { get; }

	// RVA: 0x1ff7f08 VA: 0x759460ff08
	private Animator get_animator() { }
	// RVA: 0x1ff7fe0 VA: 0x759460ffe0
	public override Void OnPlay() { }
	// RVA: 0x1ff80cc VA: 0x75946100cc
	private Void Update() { }
	// RVA: 0x1ff8134 VA: 0x7594610134
	private Void _UpdateAnimator() { }
	// RVA: 0x1ff8270 VA: 0x7594610270
	public override Void OnFinish() { }
	// RVA: 0x1ff82e0 VA: 0x75946102e0
	public Void .ctor() { }
	// RVA: 0x1ff834c VA: 0x759461034c
	private Void <>xLuaBaseProxy_OnPlay() { }
	// RVA: 0x1ff8350 VA: 0x7594610350
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```