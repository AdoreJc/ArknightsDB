# EnemyDuelEntryTimeLineView

**Namespace:** `Torappu.UI.EnemyDuel`


## Fields

- `Int32 _fromVal`

- `Int32 _toVal`

- `Text _currTextUp`

- `Text _currTextDown`

- `UIAnimationLocation _timeLineAnim`

- `Tween m_animTween`

- `Single m_animVal`

- `GameObject m_animTarget`

- `AnimationHandler m_animHandler`


## Methods

- `Void Play()`

- `Void Stop()`

- `Void _StopTweenIfNeeded()`

- `Single _GetVal()`

- `Void _SetVal(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyDuel
public class EnemyDuelEntryTimeLineView : MonoBehaviour, IHotfixable
{
	private Int32 _fromVal; // 0x18
	private Int32 _toVal; // 0x1c
	private Text _currTextUp; // 0x20
	private Text _currTextDown; // 0x28
	private UIAnimationLocation _timeLineAnim; // 0x30
	private Tween m_animTween; // 0x40
	private Single m_animVal; // 0x48
	private GameObject m_animTarget; // 0x50
	private AnimationHandler m_animHandler; // 0x58
	private static DelegateBridge __Hotfix0_Play; // 0x0
	private static DelegateBridge __Hotfix0_Stop; // 0x8
	private static DelegateBridge __Hotfix0__StopTweenIfNeeded; // 0x10
	private static DelegateBridge __Hotfix0__GetVal; // 0x18
	private static DelegateBridge __Hotfix0__SetVal; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x294a4ec VA: 0x7594f624ec
	public Void Play() { }
	// RVA: 0x294a768 VA: 0x7594f62768
	public Void Stop() { }
	// RVA: 0x294cb84 VA: 0x7594f64b84
	private Void _StopTweenIfNeeded() { }
	// RVA: 0x294cc24 VA: 0x7594f64c24
	private Single _GetVal() { }
	// RVA: 0x294cc8c VA: 0x7594f64c8c
	private Void _SetVal(Single val) { }
	// RVA: 0x294cdf0 VA: 0x7594f64df0
	public Void .ctor() { }
}
```