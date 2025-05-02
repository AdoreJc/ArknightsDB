# Act24sideQuestState

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `Act24sideQuestView _view`

- `RectTransform _btnExitRt`

- `UIAnimationLocation _animEnter`

- `Act24sideStageMapPreviewPluginView _mapPreviewPrefab`

- `RectTransform _mapPreviewContainer`

- `Boolean m_hasInited`

- `Act24sideQuestStateBean m_stateBean`

- `Act24sideStageMapPreviewPluginView m_mapPreview`

- `Tween m_enterTween`


## Methods

- `Void _OnJumpToEnemyHandbook(IStateBean)`

- `Void _OnJumpToRewardDetailView(IStateBean)`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnQuestItemClick(String)`

- `Void _InitIfNot()`

- `Void _OpenSquad(String, String, Boolean)`

- `Void EventOnBtnExit()`

- `Void EventOnBtnMap()`

- `Void EventOnBtnEnemy()`

- `Void EventOnRewardDetail()`

- `Void EventOnBtnStart()`

- `Boolean _CheckCostBeforeStartBattle(Act24sideQuestStageItemModel)`

- `Void EventOnBtnPractice()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideQuestState : State, IValueMsgReceiver
{
	private Act24sideQuestView _view; // 0x50
	private RectTransform _btnExitRt; // 0x58
	private UIAnimationLocation _animEnter; // 0x60
	private Act24sideStageMapPreviewPluginView _mapPreviewPrefab; // 0x70
	private RectTransform _mapPreviewContainer; // 0x78
	public const Int32 MSG_QUEST_CLICK; // 0x0
	private Boolean m_hasInited; // 0x80
	private Act24sideQuestStateBean m_stateBean; // 0x88
	private Act24sideStageMapPreviewPluginView m_mapPreview; // 0x90
	private Tween m_enterTween; // 0x98
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x10
	private static DelegateBridge __Hotfix0__OnJumpToEnemyHandbook; // 0x18
	private static DelegateBridge __Hotfix0__OnJumpToRewardDetailView; // 0x20
	private static DelegateBridge __Hotfix0_OnMessage; // 0x28
	private static DelegateBridge __Hotfix0__OnQuestItemClick; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x38
	private static DelegateBridge __Hotfix0__OpenSquad; // 0x40
	private static DelegateBridge __Hotfix0_EventOnBtnExit; // 0x48
	private static DelegateBridge __Hotfix0_EventOnBtnMap; // 0x50
	private static DelegateBridge __Hotfix0_EventOnBtnEnemy; // 0x58
	private static DelegateBridge __Hotfix0_EventOnRewardDetail; // 0x60
	private static DelegateBridge __Hotfix0_EventOnBtnStart; // 0x68
	private static DelegateBridge __Hotfix0__CheckCostBeforeStartBattle; // 0x70
	private static DelegateBridge __Hotfix0_EventOnBtnPractice; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80


	// RVA: 0x32c25e0 VA: 0x75958da5e0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x32c2648 VA: 0x75958da648
	protected override Void OnEnter() { }
	// RVA: 0x32c29d0 VA: 0x75958da9d0
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x32c2bc4 VA: 0x75958dabc4
	private Void _OnJumpToEnemyHandbook(IStateBean stateBean) { }
	// RVA: 0x32c324c VA: 0x75958db24c
	private Void _OnJumpToRewardDetailView(IStateBean stateBean) { }
	// RVA: 0x32c33bc VA: 0x75958db3bc
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x32c3468 VA: 0x75958db468
	private Void _OnQuestItemClick(String strVal) { }
	// RVA: 0x32c288c VA: 0x75958da88c
	private Void _InitIfNot() { }
	// RVA: 0x32c3554 VA: 0x75958db554
	private Void _OpenSquad(String actId, String stageId, Boolean isPractice) { }
	// RVA: 0x32c37e4 VA: 0x75958db7e4
	public Void EventOnBtnExit() { }
	// RVA: 0x32c38e0 VA: 0x75958db8e0
	public Void EventOnBtnMap() { }
	// RVA: 0x32c3b00 VA: 0x75958dbb00
	public Void EventOnBtnEnemy() { }
	// RVA: 0x32c3d10 VA: 0x75958dbd10
	public Void EventOnRewardDetail() { }
	// RVA: 0x32c3ec4 VA: 0x75958dbec4
	public Void EventOnBtnStart() { }
	// RVA: 0x32c4040 VA: 0x75958dc040
	private Boolean _CheckCostBeforeStartBattle(Act24sideQuestStageItemModel questItemModel) { }
	// RVA: 0x32c41c4 VA: 0x75958dc1c4
	public Void EventOnBtnPractice() { }
	// RVA: 0x32c43d8 VA: 0x75958dc3d8
	public Void .ctor() { }
	// RVA: 0x32c4488 VA: 0x75958dc488
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x32c4490 VA: 0x75958dc490
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```