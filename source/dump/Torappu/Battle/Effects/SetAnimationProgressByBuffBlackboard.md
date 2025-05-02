# SetAnimationProgressByBuffBlackboard

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `String _animState`

- `Int32 _animLayer`

- `String _blackboardKey`

- `Single _lerpFactor`

- `Single _updateInterval`

- `String _buffKey`

- `Animator m_animator`

- `Boolean m_inited`

- `Single m_updateInterval`

- `Single m_lastValue`


## Properties

- `Animator animator`


## Methods

- `Animator get_animator()`

- `Void _UpdateEffect()`

- `Void Update()`

- `Void SetProgress(Single)`

- `Void <>xLuaBaseProxy_OnPlay()`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class SetAnimationProgressByBuffBlackboard : Behaviour
{
	private String _animState; // 0x20
	private Int32 _animLayer; // 0x28
	private String _blackboardKey; // 0x30
	private Single _lerpFactor; // 0x38
	private Single _updateInterval; // 0x3c
	private String _buffKey; // 0x40
	private Animator m_animator; // 0x48
	private Boolean m_inited; // 0x50
	private Single m_updateInterval; // 0x54
	private Single m_lastValue; // 0x58
	private ObjectPtr`1 m_holdBuff; // 0x60
	private static DelegateBridge __Hotfix0_get_animator; // 0x0
	private static DelegateBridge __Hotfix0_get_holdBuff; // 0x8
	private static DelegateBridge __Hotfix0_OnPlay; // 0x10
	private static DelegateBridge __Hotfix0_OnFinish; // 0x18
	private static DelegateBridge __Hotfix0__UpdateEffect; // 0x20
	private static DelegateBridge __Hotfix0_Update; // 0x28
	private static DelegateBridge __Hotfix0_SetProgress; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private Animator animator { get; }
	private ObjectPtr`1 holdBuff { get; }

	// RVA: 0x1ff7194 VA: 0x759460f194
	private Animator get_animator() { }
	// RVA: 0x1ff726c VA: 0x759460f26c
	private ObjectPtr`1 get_holdBuff() { }
	// RVA: 0x1ff73b4 VA: 0x759460f3b4
	public override Void OnPlay() { }
	// RVA: 0x1ff7610 VA: 0x759460f610
	public override Void OnFinish() { }
	// RVA: 0x1ff7698 VA: 0x759460f698
	private Void _UpdateEffect() { }
	// RVA: 0x1ff7884 VA: 0x759460f884
	private Void Update() { }
	// RVA: 0x1ff798c VA: 0x759460f98c
	private Void SetProgress(Single progress) { }
	// RVA: 0x1ff7a94 VA: 0x759460fa94
	public Void .ctor() { }
	// RVA: 0x1ff7b50 VA: 0x759460fb50
	private Void <>xLuaBaseProxy_OnPlay() { }
	// RVA: 0x1ff7b54 VA: 0x759460fb54
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```