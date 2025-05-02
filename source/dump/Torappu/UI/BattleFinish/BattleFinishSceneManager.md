# BattleFinishSceneManager

**Namespace:** `Torappu.UI.BattleFinish`


## Fields

- `BattleFinishHomeState _homeState`

- `GameObjectPoolComponent _objectPool`

- `UIItemDescFloatBinder _itemDescFloatBinder`

- `GameObject _panelLeftFloat`

- `BattleFinishFriendView _friendView`

- `GameObject _panelSaveBattleLog`

- `GameObject _panelAllowAutoBattle`

- `Transform _lvlUpContainer`

- `UIItemDescViewProperty m_itemDescProperty`

- `SquadFriendData m_cacheFriendData`

- `BattleFinishLevelUpView m_lvlUpView`

- `Action m_onLvlUpHide`

- `Boolean <hasCheckDontSkip>k__BackingField`


## Properties

- `Boolean hasCheckDontSkip`

- `GameObjectPool dropItemPool`

- `Int32 bgmInstId`


## Methods

- `Boolean get_hasCheckDontSkip()`

- `Void set_hasCheckDontSkip(Boolean)`

- `Void EventOnItemDescCloseClicked()`

- `Void EventOnConfirmSaveBattleLog()`

- `Void EventOnCancelSaveBattleLog()`

- `Void EventOnConfirmAllowAutoBattle()`

- `Void EventOnConfirmSendFriendRequest()`

- `Void EventOnCanncelSendFriendRequest()`

- `Void _OnLvlUpCloseClicked()`

- `GameObjectPool get_dropItemPool()`

- `Int32 get_bgmInstId()`

- `Void _ShowItemDescImpl(GameObject, UIItemViewModel)`

- `Void _ShowLvlUp(Action)`

- `Void _HideLvlUp()`

- `Void _DealWithAutoBattle(Action)`

- `Void _DealWithBattleLogSave(Boolean, Boolean, Data)`

- `Void _DealWithFriendAdd()`

- `Void _ActivityOnlyDealWithFriendAdd(SquadFriendData)`

- `Void _ActivityOnly_DealWithCancelFriendRequest()`

- `Void _SendFriendProcessRequestListRequest(SquadFriendData)`

- `Void _SendSaveBattleLogService(Action)`

- `BattleLogMeta _TryToCreateBattleLogMeta()`

- `BattleCharmsData _GeneCharmsData(BattleCharmMeta)`

- `BattleTechData _GeneTechesData(BattleTechMeta)`

- `BattleCartData _GeneCartData(BattleCartMeta)`

- `BattleTrapToolData _GeneTrapToolsData(BattleTrapToolMeta)`

- `BattlePerformanceData _GeneBattlePerformanceData(BattlePerformanceMeta)`

- `BattleFireworkData _GeneBattleFireworkData(BattleFireworkMeta)`

- `PredefinedAssistData _GenePredefinedAssistData(SquadFriendData)`

- `Void _ShowAllowAutoBattle(Boolean)`

- `Void _ShowSaveBattleLog(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BattleFinish
public class BattleFinishSceneManager : SingletonMonoBehaviour`1, ISingletonNotAutoCreate
{
	private BattleFinishHomeState _homeState; // 0x18
	private GameObjectPoolComponent _objectPool; // 0x20
	private UIItemDescFloatBinder _itemDescFloatBinder; // 0x28
	private GameObject _panelLeftFloat; // 0x30
	private BattleFinishFriendView _friendView; // 0x38
	private GameObject _panelSaveBattleLog; // 0x40
	private GameObject _panelAllowAutoBattle; // 0x48
	private Transform _lvlUpContainer; // 0x50
	private UIItemDescViewProperty m_itemDescProperty; // 0x58
	private SquadFriendData m_cacheFriendData; // 0x60
	private BattleFinishLevelUpView m_lvlUpView; // 0x68
	private Action m_onLvlUpHide; // 0x70
	private Boolean <hasCheckDontSkip>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_get_hasCheckDontSkip; // 0x0
	private static DelegateBridge __Hotfix0_set_hasCheckDontSkip; // 0x8
	private static DelegateBridge __Hotfix0_OnInit; // 0x10
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x18
	private static DelegateBridge __Hotfix0_EventOnItemDescCloseClicked; // 0x20
	private static DelegateBridge __Hotfix0_EventOnConfirmSaveBattleLog; // 0x28
	private static DelegateBridge __Hotfix0_EventOnCancelSaveBattleLog; // 0x30
	private static DelegateBridge __Hotfix0_EventOnConfirmAllowAutoBattle; // 0x38
	private static DelegateBridge __Hotfix0_EventOnConfirmSendFriendRequest; // 0x40
	private static DelegateBridge __Hotfix0_EventOnCanncelSendFriendRequest; // 0x48
	private static DelegateBridge __Hotfix0__OnLvlUpCloseClicked; // 0x50
	private static DelegateBridge __Hotfix0_get_dropItemPool; // 0x58
	private static DelegateBridge __Hotfix0_get_bgmInstId; // 0x60
	private static DelegateBridge __Hotfix0_ShowItemDesc; // 0x68
	private static DelegateBridge __Hotfix0_ShowLvlUp; // 0x70
	private static DelegateBridge __Hotfix0_HideLvlUp; // 0x78
	private static DelegateBridge __Hotfix0_StartDealWithAutoBattle; // 0x80
	private static DelegateBridge __Hotfix0_ActivityOnlyStartDealWithFriendAdd; // 0x88
	private static DelegateBridge __Hotfix0_ActivityOnly_DealWithCancelFriendRequest; // 0x90
	private static DelegateBridge __Hotfix0_RouteToHomeSceneDefault; // 0x98
	private static DelegateBridge __Hotfix0__JumpToHandBook; // 0xa0
	private static DelegateBridge __Hotfix0_JumpToCampaign; // 0xa8
	private static DelegateBridge __Hotfix0_JumpToClimbTower; // 0xb0
	private static DelegateBridge __Hotfix0_JumpToBossRush; // 0xb8
	private static DelegateBridge __Hotfix0__JumpToTrainingCamp; // 0xc0
	private static DelegateBridge __Hotfix0__SceneParamToBossRush; // 0xc8
	private static DelegateBridge __Hotfix0_LoadBattleFinishBkg; // 0xd0
	private static DelegateBridge __Hotfix0__ShowItemDescImpl; // 0xd8
	private static DelegateBridge __Hotfix0__ShowLvlUp; // 0xe0
	private static DelegateBridge __Hotfix0__HideLvlUp; // 0xe8
	private static DelegateBridge __Hotfix0__DealWithAutoBattle; // 0xf0
	private static DelegateBridge __Hotfix0__DealWithBattleLogSave; // 0xf8
	private static DelegateBridge __Hotfix0__DealWithFriendAdd; // 0x100
	private static DelegateBridge __Hotfix0__ActivityOnlyDealWithFriendAdd; // 0x108
	private static DelegateBridge __Hotfix0__ActivityOnly_DealWithCancelFriendRequest; // 0x110
	private static DelegateBridge __Hotfix0__SendFriendProcessRequestListRequest; // 0x118
	private static DelegateBridge __Hotfix0__SendSaveBattleLogService; // 0x120
	private static DelegateBridge __Hotfix0__TryToCreateBattleLogMeta; // 0x128
	private static DelegateBridge __Hotfix0__GeneCharmsData; // 0x130
	private static DelegateBridge __Hotfix0__GeneTechesData; // 0x138
	private static DelegateBridge __Hotfix0__GeneCartData; // 0x140
	private static DelegateBridge __Hotfix0__GeneTrapToolsData; // 0x148
	private static DelegateBridge __Hotfix0__GeneBattlePerformanceData; // 0x150
	private static DelegateBridge __Hotfix0__GeneBattleFireworkData; // 0x158
	private static DelegateBridge __Hotfix0__GenePredefinedAssistData; // 0x160
	private static DelegateBridge __Hotfix0__ShowAllowAutoBattle; // 0x168
	private static DelegateBridge __Hotfix0__ShowSaveBattleLog; // 0x170
	private static DelegateBridge __Hotfix0__JumpToStage; // 0x178
	private static DelegateBridge __Hotfix0__InjectBattleFinishInfoToStageBundle; // 0x180
	private static DelegateBridge __Hotfix0__InjectFlashAlertInfo; // 0x188
	private static DelegateBridge __Hotfix0__JumpToCrisisV2; // 0x190
	private static DelegateBridge __Hotfix0__JumpToSandboxV2; // 0x198
	private static DelegateBridge __Hotfix0__JumpWithRoutePolicy; // 0x1a0
	private static DelegateBridge __Hotfix0_JumpToAct4fun; // 0x1a8
	private static DelegateBridge __Hotfix0_JumpToAct6fun; // 0x1b0
	private static DelegateBridge __Hotfix0__RouteToHomeSceneActivity; // 0x1b8
	private static DelegateBridge __Hotfix0__ParamToHomeAct; // 0x1c0
	private static DelegateBridge __Hotfix0__TestFillPlayerLiveData; // 0x1c8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x1d0

	public Boolean hasCheckDontSkip { get; set; }
	public GameObjectPool dropItemPool { get; }
	public Int32 bgmInstId { get; }

	// RVA: 0x2e7ef08 VA: 0x7595496f08
	public Boolean get_hasCheckDontSkip() { }
	// RVA: 0x2e7ef70 VA: 0x7595496f70
	public Void set_hasCheckDontSkip(Boolean value) { }
	// RVA: 0x2e7eff0 VA: 0x7595496ff0
	protected override Void OnInit() { }
	// RVA: 0x2e7f108 VA: 0x7595497108
	protected override Void OnDestroy() { }
	// RVA: 0x2e7f248 VA: 0x7595497248
	public Void EventOnItemDescCloseClicked() { }
	// RVA: 0x2e7f2fc VA: 0x75954972fc
	public Void EventOnConfirmSaveBattleLog() { }
	// RVA: 0x2e7f894 VA: 0x7595497894
	public Void EventOnCancelSaveBattleLog() { }
	// RVA: 0x2e7f900 VA: 0x7595497900
	public Void EventOnConfirmAllowAutoBattle() { }
	// RVA: 0x2e7fa04 VA: 0x7595497a04
	public Void EventOnConfirmSendFriendRequest() { }
	// RVA: 0x2e7fd34 VA: 0x7595497d34
	public Void EventOnCanncelSendFriendRequest() { }
	// RVA: 0x2e7fdb4 VA: 0x7595497db4
	public Void _OnLvlUpCloseClicked() { }
	// RVA: 0x2e7ff04 VA: 0x7595497f04
	public GameObjectPool get_dropItemPool() { }
	// RVA: 0x2e7ff78 VA: 0x7595497f78
	public Int32 get_bgmInstId() { }
	// RVA: 0x2e7ffe4 VA: 0x7595497fe4
	public static Void ShowItemDesc(GameObject itemObj, UIItemViewModel itemModel) { }
	// RVA: 0x2e8022c VA: 0x759549822c
	public static Void ShowLvlUp(Action onLvlUpHide) { }
	// RVA: 0x2e80608 VA: 0x7595498608
	public static Void HideLvlUp() { }
	// RVA: 0x2e806d8 VA: 0x75954986d8
	public static Void StartDealWithAutoBattle(Action onFinished) { }
	// RVA: 0x2e80de4 VA: 0x7595498de4
	public static Void ActivityOnlyStartDealWithFriendAdd(SquadFriendData friendData) { }
	// RVA: 0x2e80f9c VA: 0x7595498f9c
	public static Void ActivityOnly_DealWithCancelFriendRequest() { }
	// RVA: 0x2e8110c VA: 0x759549910c
	public static Void RouteToHomeSceneDefault() { }
	// RVA: 0x2e81b5c VA: 0x7595499b5c
	private static Void _JumpToHandBook() { }
	// RVA: 0x2e82000 VA: 0x759549a000
	public static Void JumpToCampaign() { }
	// RVA: 0x2e82114 VA: 0x759549a114
	public static Void JumpToClimbTower() { }
	// RVA: 0x2e813d4 VA: 0x75954993d4
	public static Void JumpToBossRush() { }
	// RVA: 0x2e81c8c VA: 0x7595499c8c
	private static Void _JumpToTrainingCamp() { }
	// RVA: 0x2e823d0 VA: 0x759549a3d0
	private static ISceneParam _SceneParamToBossRush(DataBundle stageBundle, Params bossRushParam) { }
	// RVA: 0x2e824dc VA: 0x759549a4dc
	public static Sprite LoadBattleFinishBkg(BattleFinishBkg config) { }
	// RVA: 0x2e800dc VA: 0x75954980dc
	private Void _ShowItemDescImpl(GameObject itemObj, UIItemViewModel itemModel) { }
	// RVA: 0x2e80308 VA: 0x7595498308
	private Void _ShowLvlUp(Action onLvlUpHide) { }
	// RVA: 0x2e7fe1c VA: 0x7595497e1c
	private Void _HideLvlUp() { }
	// RVA: 0x2e80864 VA: 0x7595498864
	private Void _DealWithAutoBattle(Action onFinished) { }
	// RVA: 0x2e825c8 VA: 0x759549a5c8
	private Void _DealWithBattleLogSave(Boolean showAutoBattleUI, Boolean battleLogValid, Data battleCache) { }
	// RVA: 0x2e827d8 VA: 0x759549a7d8
	private Void _DealWithFriendAdd() { }
	// RVA: 0x2e80ec0 VA: 0x7595498ec0
	private Void _ActivityOnlyDealWithFriendAdd(SquadFriendData friendData) { }
	// RVA: 0x2e8106c VA: 0x759549906c
	private Void _ActivityOnly_DealWithCancelFriendRequest() { }
	// RVA: 0x2e7fa94 VA: 0x7595497a94
	private Void _SendFriendProcessRequestListRequest(SquadFriendData friend) { }
	// RVA: 0x2e7f374 VA: 0x7595497374
	private Void _SendSaveBattleLogService(Action onSucceed) { }
	// RVA: 0x2e82984 VA: 0x759549a984
	private BattleLogMeta _TryToCreateBattleLogMeta() { }
	// RVA: 0x2e82f38 VA: 0x759549af38
	private BattleCharmsData _GeneCharmsData(BattleCharmMeta charmMeta) { }
	// RVA: 0x2e82ff4 VA: 0x759549aff4
	private BattleTechData _GeneTechesData(BattleTechMeta techMeta) { }
	// RVA: 0x2e830b0 VA: 0x759549b0b0
	private BattleCartData _GeneCartData(BattleCartMeta cartMeta) { }
	// RVA: 0x2e8316c VA: 0x759549b16c
	private BattleTrapToolData _GeneTrapToolsData(BattleTrapToolMeta trapToolMeta) { }
	// RVA: 0x2e83228 VA: 0x759549b228
	private BattlePerformanceData _GeneBattlePerformanceData(BattlePerformanceMeta battlePerformanceMeta) { }
	// RVA: 0x2e832e4 VA: 0x759549b2e4
	private BattleFireworkData _GeneBattleFireworkData(BattleFireworkMeta battleFireworkMeta) { }
	// RVA: 0x2e82df0 VA: 0x759549adf0
	private PredefinedAssistData _GenePredefinedAssistData(SquadFriendData assistData) { }
	// RVA: 0x2e7f96c VA: 0x759549796c
	private Void _ShowAllowAutoBattle(Boolean isShow) { }
	// RVA: 0x2e7f7fc VA: 0x75954977fc
	private Void _ShowSaveBattleLog(Boolean isShow) { }
	// RVA: 0x2e81d94 VA: 0x7595499d94
	private static Void _JumpToStage() { }
	// RVA: 0x2e8221c VA: 0x759549a21c
	private static Void _InjectBattleFinishInfoToStageBundle(DataBundle stageBundle, BattleStageInfo lastStageData, CommonFinishBattleResponse finishResponse) { }
	// RVA: 0x2e833b8 VA: 0x759549b3b8
	private static Void _InjectFlashAlertInfo(DataBundle stageBundle, BattleStageInfo lastStageData, CommonFinishBattleResponse finishResponse) { }
	// RVA: 0x2e8191c VA: 0x759549991c
	private static Void _JumpToCrisisV2() { }
	// RVA: 0x2e81a2c VA: 0x7595499a2c
	private static Void _JumpToSandboxV2() { }
	// RVA: 0x2e8157c VA: 0x759549957c
	private static Void _JumpWithRoutePolicy() { }
	// RVA: 0x2e83498 VA: 0x759549b498
	public static Void JumpToAct4fun() { }
	// RVA: 0x2e83998 VA: 0x759549b998
	public static Void JumpToAct6fun() { }
	// RVA: 0x2e812ac VA: 0x75954992ac
	private static Boolean _RouteToHomeSceneActivity(InParams input) { }
	// RVA: 0x2e83e4c VA: 0x759549be4c
	private static UIPageControllerParam _ParamToHomeAct(String actId, DataBundle actMeta) { }
	// RVA: 0x2e840dc VA: 0x759549c0dc
	private static Void _TestFillPlayerLiveData(PlayerAct4funLiveData data) { }
	// RVA: 0x2e84720 VA: 0x759549c720
	public Void .ctor() { }
}
```