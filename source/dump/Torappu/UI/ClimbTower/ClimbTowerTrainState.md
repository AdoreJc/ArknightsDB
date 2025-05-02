# ClimbTowerTrainState

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerTrainView _trainView`

- `RectTransform _topContainer`

- `Boolean m_hasInited`

- `ClimbTowerTrainStateBean m_stateBean`

- `Coroutine m_tutorialCoroutine`


## Methods

- `Void _OnJumpToPreview(IStateBean)`

- `Void OnContinueClicked()`

- `Void OnStartClicked()`

- `Void _TriggerTutorialCoroutine()`

- `Void _StopTutorialCoroutine()`

- `IEnumerator _WaitAndTrigTutorial()`

- `Void _TrainTowerGuideEndCallback(Story)`

- `Void _InitIfNot()`

- `Void _OnTowerSelected(String)`

- `Void _OnDetailClicked(String)`

- `Void <_InitIfNot>b__18_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnPause()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerTrainState : PopupFadeState, IHotfixable
{
	private ClimbTowerTrainView _trainView; // 0x70
	private RectTransform _topContainer; // 0x78
	private Boolean m_hasInited; // 0x80
	private ClimbTowerTrainStateBean m_stateBean; // 0x88
	private Coroutine m_tutorialCoroutine; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_OnPause; // 0x18
	private static DelegateBridge __Hotfix0_OnExit; // 0x20
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x28
	private static DelegateBridge __Hotfix0__OnJumpToPreview; // 0x30
	private static DelegateBridge __Hotfix0_OnContinueClicked; // 0x38
	private static DelegateBridge __Hotfix0_OnStartClicked; // 0x40
	private static DelegateBridge __Hotfix0__TriggerTutorialCoroutine; // 0x48
	private static DelegateBridge __Hotfix0__StopTutorialCoroutine; // 0x50
	private static DelegateBridge __Hotfix0__WaitAndTrigTutorial; // 0x58
	private static DelegateBridge __Hotfix0__TrainTowerGuideEndCallback; // 0x60
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x68
	private static DelegateBridge __Hotfix0__OnTowerSelected; // 0x70
	private static DelegateBridge __Hotfix0__OnDetailClicked; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80


	// RVA: 0x2ca5674 VA: 0x75952bd674
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2ca56dc VA: 0x75952bd6dc
	protected override Void OnEnter() { }
	// RVA: 0x2ca59a8 VA: 0x75952bd9a8
	protected override Void OnResume() { }
	// RVA: 0x2ca5b40 VA: 0x75952bdb40
	protected override Void OnPause() { }
	// RVA: 0x2ca5c5c VA: 0x75952bdc5c
	protected override Void OnExit() { }
	// RVA: 0x2ca5cdc VA: 0x75952bdcdc
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2ca5e54 VA: 0x75952bde54
	private Void _OnJumpToPreview(IStateBean stateBean) { }
	// RVA: 0x2ca5fac VA: 0x75952bdfac
	public Void OnContinueClicked() { }
	// RVA: 0x2ca6118 VA: 0x75952be118
	public Void OnStartClicked() { }
	// RVA: 0x2ca5a98 VA: 0x75952bda98
	private Void _TriggerTutorialCoroutine() { }
	// RVA: 0x2ca5bb4 VA: 0x75952bdbb4
	private Void _StopTutorialCoroutine() { }
	// RVA: 0x2ca63a0 VA: 0x75952be3a0
	private IEnumerator _WaitAndTrigTutorial() { }
	// RVA: 0x2ca6474 VA: 0x75952be474
	private Void _TrainTowerGuideEndCallback(Story story) { }
	// RVA: 0x2ca57bc VA: 0x75952bd7bc
	private Void _InitIfNot() { }
	// RVA: 0x2ca6554 VA: 0x75952be554
	private Void _OnTowerSelected(String towerId) { }
	// RVA: 0x2ca6640 VA: 0x75952be640
	private Void _OnDetailClicked(String towerId) { }
	// RVA: 0x2ca67f8 VA: 0x75952be7f8
	public Void .ctor() { }
	// RVA: 0x2ca6954 VA: 0x75952be954
	private Void <_InitIfNot>b__18_0() { }
	// RVA: 0x2ca6ac8 VA: 0x75952beac8
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2ca6ad0 VA: 0x75952bead0
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2ca6ad8 VA: 0x75952bead8
	private Void <>xLuaBaseProxy_OnPause() { }
	// RVA: 0x2ca6ae0 VA: 0x75952beae0
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x2ca6ae8 VA: 0x75952beae8
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```