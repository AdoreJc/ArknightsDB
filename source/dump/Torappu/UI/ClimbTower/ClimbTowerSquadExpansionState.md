# ClimbTowerSquadExpansionState

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Image _imgBg`

- `ClimbTowerSquadExpansionView _view`

- `RectTransform _backBtnRt`

- `ClimbTowerSquadExpansionStateBean m_stateBean`

- `Boolean m_hasInited`

- `Coroutine m_coroutine`

- `Coroutine m_tutorialCoroutine`

- `Boolean m_isAnim`

- `MenuAdapter m_menuAdapter`

- `UIBlocker m_blocker`


## Methods

- `Void _PlaySpawnAnim()`

- `Void _ClearAnimCoroutine()`

- `IEnumerator _PlaySpawnAnimCoro()`

- `Void _InitIfNot()`

- `Void _OnCharSelect(Boolean, String, String)`

- `Void _OnConfirmCallBack()`

- `Void _NavToSquadState()`

- `Void _TriggerTutorialCoroutine()`

- `Void _StopTutorialCoroutine()`

- `IEnumerator _WaitForExpandAnimComplete()`

- `IEnumerator _WaitAndTrigTutorial()`

- `Void OnBtnRecruit()`

- `Void _RecordNewCharTrigger(String)`

- `Void OnDestroy()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnPause()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerSquadExpansionState : PopupFadeState
{
	private Image _imgBg; // 0x70
	private ClimbTowerSquadExpansionView _view; // 0x78
	private RectTransform _backBtnRt; // 0x80
	private ClimbTowerSquadExpansionStateBean m_stateBean; // 0x88
	private Boolean m_hasInited; // 0x90
	private Coroutine m_coroutine; // 0x98
	private Coroutine m_tutorialCoroutine; // 0xa0
	private Boolean m_isAnim; // 0xa8
	private MenuAdapter m_menuAdapter; // 0xb0
	private UIBlocker m_blocker; // 0xb8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnExit; // 0x10
	private static DelegateBridge __Hotfix0_OnResume; // 0x18
	private static DelegateBridge __Hotfix0_OnPause; // 0x20
	private static DelegateBridge __Hotfix0__PlaySpawnAnim; // 0x28
	private static DelegateBridge __Hotfix0__ClearAnimCoroutine; // 0x30
	private static DelegateBridge __Hotfix0__PlaySpawnAnimCoro; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge __Hotfix0__OnCharSelect; // 0x48
	private static DelegateBridge __Hotfix0__OnConfirmCallBack; // 0x50
	private static DelegateBridge __Hotfix0__NavToSquadState; // 0x58
	private static DelegateBridge __Hotfix0__TriggerTutorialCoroutine; // 0x60
	private static DelegateBridge __Hotfix0__StopTutorialCoroutine; // 0x68
	private static DelegateBridge __Hotfix0__WaitForExpandAnimComplete; // 0x70
	private static DelegateBridge __Hotfix0__WaitAndTrigTutorial; // 0x78
	private static DelegateBridge __Hotfix0_OnBtnRecruit; // 0x80
	private static DelegateBridge __Hotfix0__RecordNewCharTrigger; // 0x88
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x90
	private static DelegateBridge _c__Hotfix0_ctor; // 0x98


	// RVA: 0x2ccf6dc VA: 0x75952e76dc
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2ccf744 VA: 0x75952e7744
	protected override Void OnEnter() { }
	// RVA: 0x2ccfff8 VA: 0x75952e7ff8
	protected override Void OnExit() { }
	// RVA: 0x2cd0158 VA: 0x75952e8158
	protected override Void OnResume() { }
	// RVA: 0x2cd02c4 VA: 0x75952e82c4
	protected override Void OnPause() { }
	// RVA: 0x2ccff08 VA: 0x75952e7f08
	private Void _PlaySpawnAnim() { }
	// RVA: 0x2cd006c VA: 0x75952e806c
	private Void _ClearAnimCoroutine() { }
	// RVA: 0x2cd0414 VA: 0x75952e8414
	private IEnumerator _PlaySpawnAnimCoro() { }
	// RVA: 0x2ccf98c VA: 0x75952e798c
	private Void _InitIfNot() { }
	// RVA: 0x2cd056c VA: 0x75952e856c
	private Void _OnCharSelect(Boolean isGiveUp, String groupId, String charId) { }
	// RVA: 0x2cd0764 VA: 0x75952e8764
	private Void _OnConfirmCallBack() { }
	// RVA: 0x2cd08a4 VA: 0x75952e88a4
	private Void _NavToSquadState() { }
	// RVA: 0x2cd01e8 VA: 0x75952e81e8
	private Void _TriggerTutorialCoroutine() { }
	// RVA: 0x2cd0338 VA: 0x75952e8338
	private Void _StopTutorialCoroutine() { }
	// RVA: 0x2cd0b80 VA: 0x75952e8b80
	private IEnumerator _WaitForExpandAnimComplete() { }
	// RVA: 0x2cd0ad4 VA: 0x75952e8ad4
	private IEnumerator _WaitAndTrigTutorial() { }
	// RVA: 0x2cd0c7c VA: 0x75952e8c7c
	public Void OnBtnRecruit() { }
	// RVA: 0x2cd1044 VA: 0x75952e9044
	private Void _RecordNewCharTrigger(String selectCharId) { }
	// RVA: 0x2cd10c4 VA: 0x75952e90c4
	private Void OnDestroy() { }
	// RVA: 0x2cd1158 VA: 0x75952e9158
	public Void .ctor() { }
	// RVA: 0x2cd1398 VA: 0x75952e9398
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2cd13a0 VA: 0x75952e93a0
	private Void <>xLuaBaseProxy_OnExit() { }
	// RVA: 0x2cd13a8 VA: 0x75952e93a8
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2cd13b0 VA: 0x75952e93b0
	private Void <>xLuaBaseProxy_OnPause() { }
}
```