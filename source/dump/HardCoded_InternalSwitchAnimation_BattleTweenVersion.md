# HardCoded_InternalSwitchAnimation_BattleTweenVersion

**Namespace:** ` `


## Fields

- `State m_state`

- `Transform m_transform`

- `FP m_switchTime`

- `Quaternion m_startQuaternion`

- `Quaternion m_phase0Quaternion`

- `Quaternion m_phase1Quaternion`

- `Quaternion m_endQuaternion`

- `Action m_onPhaseSwitch`

- `Action m_onComplete`

- `Tween m_curTween`


## Methods

- `Boolean IsActive()`

- `HardCoded_InternalSwitchAnimation_BattleTweenVersion Play()`

- `Void Kill(Boolean)`

- `Void _OnComplete()`

- `Void _ConstructTweenChain()`

- `Void <_ConstructTweenChain>b__16_0(FP)`

- `Void <_ConstructTweenChain>b__16_1()`

- `Void <_ConstructTweenChain>b__16_2(FP)`

- `Void <_ConstructTweenChain>b__16_3()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class HardCoded_InternalSwitchAnimation_BattleTweenVersion : ITweenHandler
{
	private State m_state; // 0x10
	private Transform m_transform; // 0x18
	private FP m_switchTime; // 0x20
	private Quaternion m_startQuaternion; // 0x28
	private Quaternion m_phase0Quaternion; // 0x38
	private Quaternion m_phase1Quaternion; // 0x48
	private Quaternion m_endQuaternion; // 0x58
	private Action m_onPhaseSwitch; // 0x68
	private Action m_onComplete; // 0x70
	private Tween m_curTween; // 0x78


	// RVA: 0x3f2ee34 VA: 0x7596546e34
	public Void .ctor(Transform transform, FP switchTime, Vector3 phase0Angles, Vector3 phase1Angles, Vector3 endAngles, Action onPhaseSwitch, Action onComplete) { }
	// RVA: 0x3f2f150 VA: 0x7596547150
	public Boolean IsActive() { }
	// RVA: 0x3f2ef70 VA: 0x7596546f70
	public HardCoded_InternalSwitchAnimation_BattleTweenVersion Play() { }
	// RVA: 0x3f2f160 VA: 0x7596547160
	public Void Kill(Boolean complete) { }
	// RVA: 0x3f2f1cc VA: 0x75965471cc
	private Void _OnComplete() { }
	// RVA: 0x3f2efc8 VA: 0x7596546fc8
	private Void _ConstructTweenChain() { }
	// RVA: 0x3f2f214 VA: 0x7596547214
	private Void <_ConstructTweenChain>b__16_0(FP val) { }
	// RVA: 0x3f2f2f0 VA: 0x75965472f0
	private Void <_ConstructTweenChain>b__16_1() { }
	// RVA: 0x3f2f4d8 VA: 0x75965474d8
	private Void <_ConstructTweenChain>b__16_2(FP val) { }
	// RVA: 0x3f2f5b4 VA: 0x75965475b4
	private Void <_ConstructTweenChain>b__16_3() { }
}
```