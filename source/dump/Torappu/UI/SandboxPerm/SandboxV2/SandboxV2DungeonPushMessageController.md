# SandboxV2DungeonPushMessageController

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `StateEngine _stateEngine`

- `SandboxV2DungeonAVGAdapter _avgAdapter`

- `Boolean m_isInited`

- `String m_topicId`

- `Int32 m_questStatusDialogInstId`

- `Int32 m_zoneUnlockDialogInstId`

- `Boolean m_isShowingDialog`


## Methods

- `Void Update()`

- `Boolean TutorialOnly_IsDungeonStable()`

- `Void HandleCallBack(Int32, ValueBundle)`

- `Boolean IsInDungeonAndStable()`

- `Boolean CheckFrontStateCanShowMonthMsg()`

- `Void TutorialOnly_HandleGuideStartPushMsg(SandboxV2DungeonGuideStartMsg)`

- `Void HandleMonthRewardPushMsg(List`1)`

- `Void HandleNotifyDialogMsg(String, SandboxV2DungeonDialogShowType, SandboxV2DungeonDialogQuestProcessType)`

- `Void HandleQuestFinishMsgWithToast(List`1)`

- `Void HandleRiftSubFinishMsgWithToast(List`1)`

- `Void HandleCraftUnlockMsgWithToast(List`1)`

- `Void HandleAchievementWithToast(List`1)`

- `Void Watch(SandboxV2DungeonPushMessageElement, HashSet`1)`

- `Void UnWatch(SandboxV2DungeonPushMessageElement)`

- `Void SetShowStatus(Boolean, Boolean, SandboxV2DungeonPushMessageObservableType, Object)`

- `Void _InitController()`

- `Void _TryToDealWithDialogItemWhenUpdate()`

- `SandboxV2DungeonDialogItemInfo _TryToPopPendingDialogItem()`

- `Boolean _TryToShowDialogByItemInfo(SandboxV2DungeonDialogItemInfo)`

- `Boolean _ShowDungeonZoneDialog(SandboxV2DungeonDialogItemInfo)`

- `Boolean _ShowDungeonQuestDialog(SandboxV2DungeonDialogItemInfo)`

- `Boolean _ShowDungeonRiftQuestDialog(SandboxV2DungeonDialogItemInfo)`

- `Boolean _TutorialOnly_TriggerWhenDialogQueueCompleted(SandboxV2DungeonDialogItemInfo)`

- `Boolean _CheckUIStable()`

- `Void _HandleQuestStatusCallback()`

- `Void _HandleZoneUnlockCallback()`

- `Void _TryToDealWithDialogItemWhenCallback(SandboxV2DungeonPushMessageObservableType)`

- `SandboxV2DungeonPushMessageObservableType _GetObservableTypeByDialogItem(SandboxV2DungeonDialogItemInfo)`

- `IEnumerator _ReceiveItemsCoroutine(List`1)`

- `Void <>xLuaBaseProxy_OnCreate()`

- `Void <>xLuaBaseProxy_OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DungeonPushMessageController : PageSingleComponent, ICompDialogCallBack
{
	private StateEngine _stateEngine; // 0x20
	private SandboxV2DungeonAVGAdapter _avgAdapter; // 0x28
	private Boolean m_isInited; // 0x30
	private String m_topicId; // 0x38
	private Int32 m_questStatusDialogInstId; // 0x40
	private Int32 m_zoneUnlockDialogInstId; // 0x44
	private PriorityQueue`1 m_notifyDialogItemQueue; // 0x48
	private Boolean m_isShowingDialog; // 0x50
	private List`1 m_elementInfos; // 0x58
	private static DelegateBridge __Hotfix0_OnCreate; // 0x0
	private static DelegateBridge __Hotfix0_Update; // 0x8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x10
	private static DelegateBridge __Hotfix0_TutorialOnly_IsDungeonStable; // 0x18
	private static DelegateBridge __Hotfix0_HandleCallBack; // 0x20
	private static DelegateBridge __Hotfix0_IsInDungeonAndStable; // 0x28
	private static DelegateBridge __Hotfix0_CheckFrontStateCanShowMonthMsg; // 0x30
	private static DelegateBridge __Hotfix0_TutorialOnly_HandleGuideStartPushMsg; // 0x38
	private static DelegateBridge __Hotfix0_HandleMonthRewardPushMsg; // 0x40
	private static DelegateBridge __Hotfix0_HandleNotifyDialogMsg; // 0x48
	private static DelegateBridge __Hotfix0_HandleQuestFinishMsgWithToast; // 0x50
	private static DelegateBridge __Hotfix0_HandleRiftSubFinishMsgWithToast; // 0x58
	private static DelegateBridge __Hotfix0_HandleCraftUnlockMsgWithToast; // 0x60
	private static DelegateBridge __Hotfix0_HandleAchievementWithToast; // 0x68
	private static DelegateBridge __Hotfix0_Watch; // 0x70
	private static DelegateBridge __Hotfix0_UnWatch; // 0x78
	private static DelegateBridge __Hotfix0_SetShowStatus; // 0x80
	private static DelegateBridge __Hotfix0__InitController; // 0x88
	private static DelegateBridge __Hotfix0__TryToDealWithDialogItemWhenUpdate; // 0x90
	private static DelegateBridge __Hotfix0__TryToPopPendingDialogItem; // 0x98
	private static DelegateBridge __Hotfix0__TryToShowDialogByItemInfo; // 0xa0
	private static DelegateBridge __Hotfix0__ShowDungeonZoneDialog; // 0xa8
	private static DelegateBridge __Hotfix0__ShowDungeonQuestDialog; // 0xb0
	private static DelegateBridge __Hotfix0__ShowDungeonRiftQuestDialog; // 0xb8
	private static DelegateBridge __Hotfix0__TutorialOnly_TriggerWhenDialogQueueCompleted; // 0xc0
	private static DelegateBridge __Hotfix0__CheckUIStable; // 0xc8
	private static DelegateBridge __Hotfix0__HandleQuestStatusCallback; // 0xd0
	private static DelegateBridge __Hotfix0__HandleZoneUnlockCallback; // 0xd8
	private static DelegateBridge __Hotfix0__TryToDealWithDialogItemWhenCallback; // 0xe0
	private static DelegateBridge __Hotfix0__GetObservableTypeByDialogItem; // 0xe8
	private static DelegateBridge __Hotfix0__ReceiveItemsCoroutine; // 0xf0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xf8


	// RVA: 0x253f62c VA: 0x7594b5762c
	protected override Void OnCreate() { }
	// RVA: 0x253f7f0 VA: 0x7594b577f0
	private Void Update() { }
	// RVA: 0x253f8e4 VA: 0x7594b578e4
	protected override Void OnDestroy() { }
	// RVA: 0x253f980 VA: 0x7594b57980
	public Boolean TutorialOnly_IsDungeonStable() { }
	// RVA: 0x253fa24 VA: 0x7594b57a24
	public Void HandleCallBack(Int32 instId, ValueBundle output) { }
	// RVA: 0x253fbbc VA: 0x7594b57bbc
	public Boolean IsInDungeonAndStable() { }
	// RVA: 0x253fd24 VA: 0x7594b57d24
	public Boolean CheckFrontStateCanShowMonthMsg() { }
	// RVA: 0x253ff28 VA: 0x7594b57f28
	public Void TutorialOnly_HandleGuideStartPushMsg(SandboxV2DungeonGuideStartMsg msg) { }
	// RVA: 0x2540084 VA: 0x7594b58084
	public Void HandleMonthRewardPushMsg(List`1 rewards) { }
	// RVA: 0x254026c VA: 0x7594b5826c
	public Void HandleNotifyDialogMsg(String id, SandboxV2DungeonDialogShowType showType, SandboxV2DungeonDialogQuestProcessType questProcessType) { }
	// RVA: 0x254038c VA: 0x7594b5838c
	public Void HandleQuestFinishMsgWithToast(List`1 questIds) { }
	// RVA: 0x2540630 VA: 0x7594b58630
	public Void HandleRiftSubFinishMsgWithToast(List`1 subTargetIds) { }
	// RVA: 0x25408d4 VA: 0x7594b588d4
	public Void HandleCraftUnlockMsgWithToast(List`1 itemIds) { }
	// RVA: 0x2540afc VA: 0x7594b58afc
	public Void HandleAchievementWithToast(List`1 achievementIds) { }
	// RVA: 0x2540da0 VA: 0x7594b58da0
	public Void Watch(SandboxV2DungeonPushMessageElement element, HashSet`1 observableTypes) { }
	// RVA: 0x2540ffc VA: 0x7594b58ffc
	public Void UnWatch(SandboxV2DungeonPushMessageElement element) { }
	// RVA: 0x2541198 VA: 0x7594b59198
	public Void SetShowStatus(Boolean isShow, Boolean isFastMode, SandboxV2DungeonPushMessageObservableType monoType, Object param) { }
	// RVA: 0x253f6a0 VA: 0x7594b576a0
	private Void _InitController() { }
	// RVA: 0x253f858 VA: 0x7594b57858
	private Void _TryToDealWithDialogItemWhenUpdate() { }
	// RVA: 0x25414a4 VA: 0x7594b594a4
	private SandboxV2DungeonDialogItemInfo _TryToPopPendingDialogItem() { }
	// RVA: 0x25415c0 VA: 0x7594b595c0
	private Boolean _TryToShowDialogByItemInfo(SandboxV2DungeonDialogItemInfo dialogItem) { }
	// RVA: 0x25416c4 VA: 0x7594b596c4
	private Boolean _ShowDungeonZoneDialog(SandboxV2DungeonDialogItemInfo dialogItemInfo) { }
	// RVA: 0x2541af0 VA: 0x7594b59af0
	private Boolean _ShowDungeonQuestDialog(SandboxV2DungeonDialogItemInfo dialogItemInfo) { }
	// RVA: 0x2541df8 VA: 0x7594b59df8
	private Boolean _ShowDungeonRiftQuestDialog(SandboxV2DungeonDialogItemInfo dialogItemInfo) { }
	// RVA: 0x25420e8 VA: 0x7594b5a0e8
	private Boolean _TutorialOnly_TriggerWhenDialogQueueCompleted(SandboxV2DungeonDialogItemInfo dialogItemInfo) { }
	// RVA: 0x253fe20 VA: 0x7594b57e20
	private Boolean _CheckUIStable() { }
	// RVA: 0x253fae4 VA: 0x7594b57ae4
	private Void _HandleQuestStatusCallback() { }
	// RVA: 0x253fb50 VA: 0x7594b57b50
	private Void _HandleZoneUnlockCallback() { }
	// RVA: 0x2542180 VA: 0x7594b5a180
	private Void _TryToDealWithDialogItemWhenCallback(SandboxV2DungeonPushMessageObservableType observableType) { }
	// RVA: 0x2542280 VA: 0x7594b5a280
	private SandboxV2DungeonPushMessageObservableType _GetObservableTypeByDialogItem(SandboxV2DungeonDialogItemInfo dialogItem) { }
	// RVA: 0x254019c VA: 0x7594b5819c
	private IEnumerator _ReceiveItemsCoroutine(List`1 items) { }
	// RVA: 0x254234c VA: 0x7594b5a34c
	public Void .ctor() { }
	// RVA: 0x2542460 VA: 0x7594b5a460
	private Void <>xLuaBaseProxy_OnCreate() { }
	// RVA: 0x2542468 VA: 0x7594b5a468
	private Void <>xLuaBaseProxy_OnDestroy() { }
}
```