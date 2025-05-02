# UICooperateRestingPanel

**Namespace:** `Torappu.Battle.UI.Cooperate`


## Fields

- `Text _timer`

- `Button _skipButton`

- `AnimationWrapper _leftAnimation`

- `AnimationWrapper _rightAnimation`

- `CooperateGameMode m_gameMode`

- `PeriodicTimer m_restingTicker`


## Methods

- `Void OnInit(CooperateGameMode)`

- `Void OnTick(FP)`

- `Void _OnRestingStateChanged(Object)`

- `Void OnSkipButtonClick()`

- `Void OnPlayerSkipResting(PlayerSide)`

- `Void ResetResting()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Cooperate
public class UICooperateRestingPanel : MonoBehaviour, IHotfixable
{
	private Text _timer; // 0x18
	private Button _skipButton; // 0x20
	private AnimationWrapper _leftAnimation; // 0x28
	private AnimationWrapper _rightAnimation; // 0x30
	private CooperateGameMode m_gameMode; // 0x38
	private PeriodicTimer m_restingTicker; // 0x40
	private readonly String m_leftAnimationName; // 0x48
	private readonly String m_rightAnimationName; // 0x50
	private readonly String m_str_s; // 0x58
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_OnTick; // 0x8
	private static DelegateBridge __Hotfix0__OnRestingStateChanged; // 0x10
	private static DelegateBridge __Hotfix0_OnSkipButtonClick; // 0x18
	private static DelegateBridge __Hotfix0_OnPlayerSkipResting; // 0x20
	private static DelegateBridge __Hotfix0_ResetResting; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x20d0294 VA: 0x75946e8294
	public Void OnInit(CooperateGameMode gameMode) { }
	// RVA: 0x20d0374 VA: 0x75946e8374
	public Void OnTick(FP deltaTime) { }
	// RVA: 0x20d0528 VA: 0x75946e8528
	private Void _OnRestingStateChanged(Object args) { }
	// RVA: 0x20d06ac VA: 0x75946e86ac
	public Void OnSkipButtonClick() { }
	// RVA: 0x20d0818 VA: 0x75946e8818
	public Void OnPlayerSkipResting(PlayerSide side) { }
	// RVA: 0x20d09e0 VA: 0x75946e89e0
	public Void ResetResting() { }
	// RVA: 0x20d0a7c VA: 0x75946e8a7c
	public Void .ctor() { }
}
```