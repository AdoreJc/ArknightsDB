# ClimbTowerLayerState

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ClimbTowerLayerView _towerLayerView`

- `AnimationWrapper _animShow`

- `AnimationWrapper _animLayerNumRoll`

- `ClimbTowerMenuButton _menuButtonPrefab`

- `RectTransform _backBtn`

- `RectTransform _mapPreviewBtn`

- `ClimbTowerLayerStateBean m_stateBean`

- `MenuAdapter m_menuAdapter`

- `Boolean m_showMenu`

- `Boolean m_showEffect`

- `Boolean m_inited`

- `TweenType m_menuTweenType`

- `Boolean m_isPlayingEntrance`

- `EntranceConfig m_entranceConfig`

- `Coroutine m_tutorialCoroutine`

- `UIBlocker m_blocker`


## Properties

- `Boolean canClick`


## Methods

- `Boolean get_canClick()`

- `Void _InitIfNot()`

- `Void _ResetToBegin()`

- `Void _ResetToEnd()`

- `IEnumerator _PlayEntranceAnim()`

- `IEnumerator _CoroutinePlayEntranceAnim()`

- `Void _AnimSwitchLayer()`

- `Void _AnimShowBottomMenu()`

- `Void _TriggerTutorialCoroutine()`

- `Void _StopTutorialCoroutine()`

- `IEnumerator _WaitForEntranceAnimComplete()`

- `IEnumerator _WaitAndTrigTutorial()`

- `Void _OnJumpToEnemyHandBook(IStateBean)`

- `Void _OnJumpToRewardDetailView(IStateBean)`

- `IEnumerator _RouteToProperState()`

- `Void OnBtnBackClicked()`

- `Void OnBtnSettleClicked()`

- `Void OnBtnUpClicked()`

- `Void OnBtnDownClicked()`

- `Void OnJumpToEnemyHandbook()`

- `Void OnJumpToRewardDetailView()`

- `Void OnBtnMapTipsClicked()`

- `Void OnBtnExitMapTipsClicked()`

- `Void _EventOnMenuButtonClick()`

- `Void OnDestroy()`

- `Void <_InitIfNot>b__25_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnPause()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerLayerState : PopupFadeState
{
	private const String ANIM_SHOW_NAME; // 0x0
	private const String ANIM_LAYER_NUM_ROLL_NAME; // 0x0
	private ClimbTowerLayerView _towerLayerView; // 0x70
	private AnimationWrapper _animShow; // 0x78
	private AnimationWrapper _animLayerNumRoll; // 0x80
	private ClimbTowerMenuButton _menuButtonPrefab; // 0x88
	private RectTransform _backBtn; // 0x90
	private RectTransform _mapPreviewBtn; // 0x98
	private ClimbTowerLayerStateBean m_stateBean; // 0xa0
	private MenuAdapter m_menuAdapter; // 0xa8
	private Boolean m_showMenu; // 0xb0
	private Boolean m_showEffect; // 0xb1
	private Boolean m_inited; // 0xb2
	private TweenType m_menuTweenType; // 0xb4
	private Boolean m_isPlayingEntrance; // 0xb8
	private EntranceConfig m_entranceConfig; // 0xb9
	private Coroutine m_tutorialCoroutine; // 0xc0
	private List`1 m_cachedCoroutine; // 0xc8
	private UIBlocker m_blocker; // 0xd0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_get_canClick; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnEnter; // 0x18
	private static DelegateBridge __Hotfix0_OnResume; // 0x20
	private static DelegateBridge __Hotfix0_OnPause; // 0x28
	private static DelegateBridge __Hotfix0__ResetToBegin; // 0x30
	private static DelegateBridge __Hotfix0__ResetToEnd; // 0x38
	private static DelegateBridge __Hotfix0__PlayEntranceAnim; // 0x40
	private static DelegateBridge __Hotfix0__CoroutinePlayEntranceAnim; // 0x48
	private static DelegateBridge __Hotfix0__AnimSwitchLayer; // 0x50
	private static DelegateBridge __Hotfix0__AnimShowBottomMenu; // 0x58
	private static DelegateBridge __Hotfix0__TriggerTutorialCoroutine; // 0x60
	private static DelegateBridge __Hotfix0__StopTutorialCoroutine; // 0x68
	private static DelegateBridge __Hotfix0__WaitForEntranceAnimComplete; // 0x70
	private static DelegateBridge __Hotfix0__WaitAndTrigTutorial; // 0x78
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x80
	private static DelegateBridge __Hotfix0__OnJumpToEnemyHandBook; // 0x88
	private static DelegateBridge __Hotfix0__OnJumpToRewardDetailView; // 0x90
	private static DelegateBridge __Hotfix0__RouteToProperState; // 0x98
	private static DelegateBridge __Hotfix0_OnBtnBackClicked; // 0xa0
	private static DelegateBridge __Hotfix0_OnBtnSettleClicked; // 0xa8
	private static DelegateBridge __Hotfix0_OnBtnUpClicked; // 0xb0
	private static DelegateBridge __Hotfix0_OnBtnDownClicked; // 0xb8
	private static DelegateBridge __Hotfix0_OnJumpToEnemyHandbook; // 0xc0
	private static DelegateBridge __Hotfix0_OnJumpToRewardDetailView; // 0xc8
	private static DelegateBridge __Hotfix0_OnBtnMapTipsClicked; // 0xd0
	private static DelegateBridge __Hotfix0_OnBtnExitMapTipsClicked; // 0xd8
	private static DelegateBridge __Hotfix0__EventOnMenuButtonClick; // 0xe0
	private static DelegateBridge __Hotfix0_OnDestroy; // 0xe8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xf0

	public Boolean canClick { get; }

	// RVA: 0x2c94e84 VA: 0x75952ace84
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2c94eec VA: 0x75952aceec
	public Boolean get_canClick() { }
	// RVA: 0x2c94f5c VA: 0x75952acf5c
	private Void _InitIfNot() { }
	// RVA: 0x2c95104 VA: 0x75952ad104
	protected override Void OnEnter() { }
	// RVA: 0x2c95834 VA: 0x75952ad834
	protected override Void OnResume() { }
	// RVA: 0x2c95ac4 VA: 0x75952adac4
	protected override Void OnPause() { }
	// RVA: 0x2c954e8 VA: 0x75952ad4e8
	private Void _ResetToBegin() { }
	// RVA: 0x2c95724 VA: 0x75952ad724
	private Void _ResetToEnd() { }
	// RVA: 0x2c95970 VA: 0x75952ad970
	private IEnumerator _PlayEntranceAnim() { }
	// RVA: 0x2c95d90 VA: 0x75952add90
	private IEnumerator _CoroutinePlayEntranceAnim() { }
	// RVA: 0x2c95e64 VA: 0x75952ade64
	private Void _AnimSwitchLayer() { }
	// RVA: 0x2c95fc4 VA: 0x75952adfc4
	private Void _AnimShowBottomMenu() { }
	// RVA: 0x2c95a1c VA: 0x75952ada1c
	private Void _TriggerTutorialCoroutine() { }
	// RVA: 0x2c95cc0 VA: 0x75952adcc0
	private Void _StopTutorialCoroutine() { }
	// RVA: 0x2c960fc VA: 0x75952ae0fc
	private IEnumerator _WaitForEntranceAnimComplete() { }
	// RVA: 0x2c96050 VA: 0x75952ae050
	private IEnumerator _WaitAndTrigTutorial() { }
	// RVA: 0x2c961f8 VA: 0x75952ae1f8
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2c963ec VA: 0x75952ae3ec
	private Void _OnJumpToEnemyHandBook(IStateBean stateBean) { }
	// RVA: 0x2c96538 VA: 0x75952ae538
	private Void _OnJumpToRewardDetailView(IStateBean stateBean) { }
	// RVA: 0x2c96704 VA: 0x75952ae704
	private IEnumerator _RouteToProperState() { }
	// RVA: 0x2c967d8 VA: 0x75952ae7d8
	public Void OnBtnBackClicked() { }
	// RVA: 0x2c96990 VA: 0x75952ae990
	public Void OnBtnSettleClicked() { }
	// RVA: 0x2c96d20 VA: 0x75952aed20
	public Void OnBtnUpClicked() { }
	// RVA: 0x2c96f34 VA: 0x75952aef34
	public Void OnBtnDownClicked() { }
	// RVA: 0x2c97148 VA: 0x75952af148
	public Void OnJumpToEnemyHandbook() { }
	// RVA: 0x2c97438 VA: 0x75952af438
	public Void OnJumpToRewardDetailView() { }
	// RVA: 0x2c976b0 VA: 0x75952af6b0
	public Void OnBtnMapTipsClicked() { }
	// RVA: 0x2c97734 VA: 0x75952af734
	public Void OnBtnExitMapTipsClicked() { }
	// RVA: 0x2c977bc VA: 0x75952af7bc
	private Void _EventOnMenuButtonClick() { }
	// RVA: 0x2c97a38 VA: 0x75952afa38
	private Void OnDestroy() { }
	// RVA: 0x2c97acc VA: 0x75952afacc
	public Void .ctor() { }
	// RVA: 0x2c97cc8 VA: 0x75952afcc8
	private Void <_InitIfNot>b__25_0() { }
	// RVA: 0x2c97ce4 VA: 0x75952afce4
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2c97cec VA: 0x75952afcec
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2c97cf4 VA: 0x75952afcf4
	private Void <>xLuaBaseProxy_OnPause() { }
	// RVA: 0x2c97cfc VA: 0x75952afcfc
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```