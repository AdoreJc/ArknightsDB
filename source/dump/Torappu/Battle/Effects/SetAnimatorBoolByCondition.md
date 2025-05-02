# SetAnimatorBoolByCondition

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `String _paramName`

- `AnimatorBoolSource _source`

- `Animator m_animator`

- `Boolean m_cachedValue`

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
public class SetAnimatorBoolByCondition : Behaviour
{
	private String _paramName; // 0x20
	private AnimatorBoolSource _source; // 0x28
	private Animator m_animator; // 0x30
	private Boolean m_cachedValue; // 0x38
	private Boolean m_hasPlayed; // 0x39
	private static DelegateBridge __Hotfix0_get_animator; // 0x0
	private static DelegateBridge __Hotfix0_OnPlay; // 0x8
	private static DelegateBridge __Hotfix0_Update; // 0x10
	private static DelegateBridge __Hotfix0__UpdateAnimator; // 0x18
	private static DelegateBridge __Hotfix0_OnFinish; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Animator animator { get; }

	// RVA: 0x1ff7b58 VA: 0x759460fb58
	private Animator get_animator() { }
	// RVA: 0x1ff7c30 VA: 0x759460fc30
	public override Void OnPlay() { }
	// RVA: 0x1ff7cf0 VA: 0x759460fcf0
	private Void Update() { }
	// RVA: 0x1ff7d58 VA: 0x759460fd58
	private Void _UpdateAnimator() { }
	// RVA: 0x1ff7e24 VA: 0x759460fe24
	public override Void OnFinish() { }
	// RVA: 0x1ff7e94 VA: 0x759460fe94
	public Void .ctor() { }
	// RVA: 0x1ff7f00 VA: 0x759460ff00
	private Void <>xLuaBaseProxy_OnPlay() { }
	// RVA: 0x1ff7f04 VA: 0x759460ff04
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```