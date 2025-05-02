# ThreePartChannelingAnimation

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `AnimationBundle _default`

- `Boolean _overrideDownAnimation`

- `AnimationBundle _down`

- `Boolean _overrideUpAnimation`

- `AnimationBundle _up`

- `Boolean _faceToFront`

- `Boolean _faceToDefault`

- `Boolean _waitForAttachFinishEvent`

- `Boolean _earlyFinishEndIdleAnimation`

- `Boolean _fireAttackFinishEvent`

- `Boolean _delayToFireAttackSkillEvent`

- `Single _delaySecond`

- `Boolean _fireAnimEndEvent`

- `Boolean _dontPlayBeginAnimFromInterrupted`

- `Boolean _onlyPlayBeginAnimWhenFirstAttack`

- `Boolean _delayToAnimateEndAnimation`

- `Single _delayToAnimateEndAnimationTime`

- `Single m_beginAndEndAnimScale`

- `Single m_loopTime`

- `FP m_earlyFinishLoopTime`

- `Boolean m_hasBeginAnim`

- `Boolean m_hasEndAnim`

- `Boolean m_receivedAttackFinishEvent`

- `Boolean m_recoverFromInterrupted`

- `CoroutineId m_coroutine`


## Properties

- `Boolean waitForAttackFinishEvent`

- `Boolean fireAttackFinishEvent`

- `Boolean delayToFireAttackSkillEvent`

- `Boolean delayToAnimateEndAnimation`


## Methods

- `Boolean get_waitForAttackFinishEvent()`

- `Boolean get_fireAttackFinishEvent()`

- `Boolean get_delayToFireAttackSkillEvent()`

- `Boolean get_delayToAnimateEndAnimation()`

- `Void _OnStunned(Object)`

- `Void _OnFrozen(Object)`

- `Void _OnLevitate(Object)`

- `IEnumerator DoPlayAnimation(AnimationBundle)`

- `AnimationBundle _GetAnimBundle()`

- `Void _OnReceiveAttackFinishEvent(Object)`

- `Void _ClearCoroutine()`

- `Boolean <DoPlayAnimation>b__42_0()`

- `Void <>xLuaBaseProxy_OnEvent(Event)`

- `Void <>xLuaBaseProxy_OnCastStart()`

- `Void <>xLuaBaseProxy_OnCastFinish(FinishReason)`

- `Boolean <>xLuaBaseProxy_UpdatePlaybackSpeed(UpdatePlaybackSpeedTiming, out)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class ThreePartChannelingAnimation : Behaviour
{
	private const Single MAX_CHANNELING_TIME; // 0x0
	private AnimationBundle _default; // 0x20
	private Boolean _overrideDownAnimation; // 0x38
	private AnimationBundle _down; // 0x40
	private Boolean _overrideUpAnimation; // 0x58
	private AnimationBundle _up; // 0x60
	private Boolean _faceToFront; // 0x78
	private Boolean _faceToDefault; // 0x79
	private Boolean _waitForAttachFinishEvent; // 0x7a
	private Boolean _earlyFinishEndIdleAnimation; // 0x7b
	private Boolean _fireAttackFinishEvent; // 0x7c
	private Boolean _delayToFireAttackSkillEvent; // 0x7d
	private Single _delaySecond; // 0x80
	private Boolean _fireAnimEndEvent; // 0x84
	private Boolean _dontPlayBeginAnimFromInterrupted; // 0x85
	private Boolean _onlyPlayBeginAnimWhenFirstAttack; // 0x86
	private Boolean _delayToAnimateEndAnimation; // 0x87
	private Single _delayToAnimateEndAnimationTime; // 0x88
	private Single m_beginAndEndAnimScale; // 0x8c
	private Single m_loopTime; // 0x90
	private FP m_earlyFinishLoopTime; // 0x98
	private Boolean m_hasBeginAnim; // 0xa0
	private Boolean m_hasEndAnim; // 0xa1
	private Boolean m_receivedAttackFinishEvent; // 0xa2
	private Boolean m_recoverFromInterrupted; // 0xa3
	private CoroutineId m_coroutine; // 0xa8
	private static DelegateBridge __Hotfix0_get_waitForAttackFinishEvent; // 0x0
	private static DelegateBridge __Hotfix0_get_fireAttackFinishEvent; // 0x8
	private static DelegateBridge __Hotfix0_get_delayToFireAttackSkillEvent; // 0x10
	private static DelegateBridge __Hotfix0_get_delayToAnimateEndAnimation; // 0x18
	private static DelegateBridge __Hotfix0_OnEvent; // 0x20
	private static DelegateBridge __Hotfix0_OnCastStart; // 0x28
	private static DelegateBridge __Hotfix0__OnStunned; // 0x30
	private static DelegateBridge __Hotfix0__OnFrozen; // 0x38
	private static DelegateBridge __Hotfix0__OnLevitate; // 0x40
	private static DelegateBridge __Hotfix0_OnCastFinish; // 0x48
	private static DelegateBridge __Hotfix0_UpdatePlaybackSpeed; // 0x50
	private static DelegateBridge __Hotfix0_DoPlayAnimation; // 0x58
	private static DelegateBridge __Hotfix0__GetAnimBundle; // 0x60
	private static DelegateBridge __Hotfix0__OnReceiveAttackFinishEvent; // 0x68
	private static DelegateBridge __Hotfix0__ClearCoroutine; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	private Boolean waitForAttackFinishEvent { get; }
	protected Boolean fireAttackFinishEvent { get; }
	protected Boolean delayToFireAttackSkillEvent { get; }
	protected Boolean delayToAnimateEndAnimation { get; }

	// RVA: 0x1eb9a4c VA: 0x75944d1a4c
	private Boolean get_waitForAttackFinishEvent() { }
	// RVA: 0x1eb9ab4 VA: 0x75944d1ab4
	protected Boolean get_fireAttackFinishEvent() { }
	// RVA: 0x1eb9b1c VA: 0x75944d1b1c
	protected Boolean get_delayToFireAttackSkillEvent() { }
	// RVA: 0x1eb9b84 VA: 0x75944d1b84
	protected Boolean get_delayToAnimateEndAnimation() { }
	// RVA: 0x1eb9bec VA: 0x75944d1bec
	public override Void OnEvent(Event ev) { }
	// RVA: 0x1eb9d9c VA: 0x75944d1d9c
	public override Void OnCastStart() { }
	// RVA: 0x1eba26c VA: 0x75944d226c
	private Void _OnStunned(Object arg) { }
	// RVA: 0x1eba3bc VA: 0x75944d23bc
	private Void _OnFrozen(Object arg) { }
	// RVA: 0x1eba50c VA: 0x75944d250c
	private Void _OnLevitate(Object arg) { }
	// RVA: 0x1eba65c VA: 0x75944d265c
	public override Void OnCastFinish(FinishReason reason) { }
	// RVA: 0x1eba858 VA: 0x75944d2858
	public override Boolean UpdatePlaybackSpeed(UpdatePlaybackSpeedTiming timing, out Single playbackSpeed) { }
	// RVA: 0x1eba178 VA: 0x75944d2178
	protected IEnumerator DoPlayAnimation(AnimationBundle bundle) { }
	// RVA: 0x1eba080 VA: 0x75944d2080
	private AnimationBundle _GetAnimBundle() { }
	// RVA: 0x1ebaa7c VA: 0x75944d2a7c
	private Void _OnReceiveAttackFinishEvent(Object arg) { }
	// RVA: 0x1eb9c90 VA: 0x75944d1c90
	private Void _ClearCoroutine() { }
	// RVA: 0x1ebaafc VA: 0x75944d2afc
	public Void .ctor() { }
	// RVA: 0x1ebaba0 VA: 0x75944d2ba0
	private Boolean <DoPlayAnimation>b__42_0() { }
	// RVA: 0x1ebabb0 VA: 0x75944d2bb0
	private Void <>xLuaBaseProxy_OnEvent(Event P0) { }
	// RVA: 0x1ebabb8 VA: 0x75944d2bb8
	private Void <>xLuaBaseProxy_OnCastStart() { }
	// RVA: 0x1ebabc0 VA: 0x75944d2bc0
	private Void <>xLuaBaseProxy_OnCastFinish(FinishReason P0) { }
	// RVA: 0x1ebabc8 VA: 0x75944d2bc8
	private Boolean <>xLuaBaseProxy_UpdatePlaybackSpeed(UpdatePlaybackSpeedTiming P0, out Single P1) { }
}
```