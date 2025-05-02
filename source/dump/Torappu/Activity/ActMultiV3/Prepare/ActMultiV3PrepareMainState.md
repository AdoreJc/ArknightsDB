# ActMultiV3PrepareMainState

**Namespace:** `Torappu.Activity.ActMultiV3.Prepare`


## Fields

- `ActMultiV3PrepareMainStepView _stepView`

- `Transform _popViewContainer`

- `ActMultiV3PrepareMainBannerView _bannerView`

- `ActMultiV3EmoticonController _emoticonController`

- `ActMultiV3PrepareMainViewModelProperty m_prop`

- `UICompDialogMgr m_dlgMgr`

- `Int32 m_leaveRoomDlgInstId`

- `Int32 m_kickDlgInstId`

- `Int32 m_enterGameOnPartnerOfflineDlgInstId`

- `String m_partnerIdToKick`


## Properties

- `UICompDialogMgr dlgMgr`

- `ActMultiV3PrepareMainBannerView banner`


## Methods

- `UICompDialogMgr get_dlgMgr()`

- `Void HandleCallBack(Int32, ValueBundle)`

- `Void OnDestroy()`

- `Void _Release()`

- `Void Update()`

- `Void _InitIfNot()`

- `Void SetPopViewLayer(Transform)`

- `Void UpdateMainViewConfig()`

- `ActMultiV3PrepareMainBannerView get_banner()`

- `Void _OnJumpToStageListState(IStateBean)`

- `Boolean CustomSetActive(Boolean)`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _EventOnExit()`

- `Void _EventOnBack()`

- `Void _EventOnSetEmergency(Boolean)`

- `Void _OpenChat()`

- `Void _EventOnKick()`

- `Void _EventOnCheckNameCard()`

- `Void _EventOnOpenStageDetailDialog()`

- `Void _EventOnOpenSquadEffectInfoDialog()`

- `Void _EventOnOpenStageChooseState()`

- `Void _EventOnEnterGameOnPartnerOffline()`

- `Void _OpenNameCardPage()`

- `Void _OnSendChat()`

- `Void _UnRegiesterSvrEvent()`

- `Void _RegisterSvrEvent()`

- `Void _HandleTeamChanged(Object)`

- `Void _HandleTeamChat(Object)`

- `Void _HandleGetNameCardRet(Object)`

- `Void CloseDialogsAndEmoticonPanel()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3.Prepare
public class ActMultiV3PrepareMainState : State, IValueMsgReceiver, IPopupCustomActive, ICompDialogCallBack
{
	private ActMultiV3PrepareMainStepView _stepView; // 0x50
	private ActMultiV3PrepareMainViewBase[] _staticMainViews; // 0x58
	private DynViewPrefab[] _viewPrefabs; // 0x60
	private Transform _popViewContainer; // 0x68
	private ActMultiV3PrepareMainBannerView _bannerView; // 0x70
	private ActMultiV3EmoticonController _emoticonController; // 0x78
	private ActMultiV3PrepareMainViewModelProperty m_prop; // 0x80
	private List`1 m_stepPanels; // 0x88
	private List`1 m_mainViews; // 0x90
	private UICompDialogMgr m_dlgMgr; // 0x98
	private Int32 m_leaveRoomDlgInstId; // 0xa0
	private Int32 m_kickDlgInstId; // 0xa4
	private Int32 m_enterGameOnPartnerOfflineDlgInstId; // 0xa8
	private String m_partnerIdToKick; // 0xb0
	private static DelegateBridge __Hotfix0_get_dlgMgr; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x10
	private static DelegateBridge __Hotfix0_HandleCallBack; // 0x18
	private static DelegateBridge __Hotfix0_OnEnter; // 0x20
	private static DelegateBridge __Hotfix0_OnExit; // 0x28
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x30
	private static DelegateBridge __Hotfix0__Release; // 0x38
	private static DelegateBridge __Hotfix0_Update; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x48
	private static DelegateBridge __Hotfix0_SetPopViewLayer; // 0x50
	private static DelegateBridge __Hotfix0_UpdateMainViewConfig; // 0x58
	private static DelegateBridge __Hotfix0_get_banner; // 0x60
	private static DelegateBridge __Hotfix0__OnJumpToStageListState; // 0x68
	private static DelegateBridge __Hotfix0_CustomSetActive; // 0x70
	private static DelegateBridge __Hotfix0_OnMessage; // 0x78
	private static DelegateBridge __Hotfix0__EventOnExit; // 0x80
	private static DelegateBridge __Hotfix0__EventOnBack; // 0x88
	private static DelegateBridge __Hotfix0__EventOnSetEmergency; // 0x90
	private static DelegateBridge __Hotfix0__OpenChat; // 0x98
	private static DelegateBridge __Hotfix0__EventOnKick; // 0xa0
	private static DelegateBridge __Hotfix0__EventOnCheckNameCard; // 0xa8
	private static DelegateBridge __Hotfix0__EventOnOpenStageDetailDialog; // 0xb0
	private static DelegateBridge __Hotfix0__EventOnOpenSquadEffectInfoDialog; // 0xb8
	private static DelegateBridge __Hotfix0__EventOnOpenStageChooseState; // 0xc0
	private static DelegateBridge __Hotfix0__EventOnEnterGameOnPartnerOffline; // 0xc8
	private static DelegateBridge __Hotfix0__OpenNameCardPage; // 0xd0
	private static DelegateBridge __Hotfix0__OnSendChat; // 0xd8
	private static DelegateBridge __Hotfix0__UnRegiesterSvrEvent; // 0xe0
	private static DelegateBridge __Hotfix0__RegisterSvrEvent; // 0xe8
	private static DelegateBridge __Hotfix0__HandleTeamChanged; // 0xf0
	private static DelegateBridge __Hotfix0__HandleTeamChat; // 0xf8
	private static DelegateBridge __Hotfix0__HandleGetNameCardRet; // 0x100
	private static DelegateBridge __Hotfix0_CloseDialogsAndEmoticonPanel; // 0x108
	private static DelegateBridge _c__Hotfix0_ctor; // 0x110

	public UICompDialogMgr dlgMgr { get; }
	public ActMultiV3PrepareMainBannerView banner { get; }

	// RVA: 0x3157640 VA: 0x759576f640
	public UICompDialogMgr get_dlgMgr() { }
	// RVA: 0x31576a8 VA: 0x759576f6a8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x315770c VA: 0x759576f70c
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x3157884 VA: 0x759576f884
	public Void HandleCallBack(Int32 instId, ValueBundle output) { }
	// RVA: 0x31579ec VA: 0x759576f9ec
	protected override Void OnEnter() { }
	// RVA: 0x315802c VA: 0x759577002c
	protected override Void OnExit() { }
	// RVA: 0x3158118 VA: 0x7595770118
	private Void OnDestroy() { }
	// RVA: 0x31580a0 VA: 0x75957700a0
	private Void _Release() { }
	// RVA: 0x3158458 VA: 0x7595770458
	private Void Update() { }
	// RVA: 0x3157a60 VA: 0x759576fa60
	private Void _InitIfNot() { }
	// RVA: 0x3159260 VA: 0x7595771260
	public Void SetPopViewLayer(Transform viewTrans) { }
	// RVA: 0x3158f10 VA: 0x7595770f10
	public Void UpdateMainViewConfig() { }
	// RVA: 0x315950c VA: 0x759577150c
	public ActMultiV3PrepareMainBannerView get_banner() { }
	// RVA: 0x3159574 VA: 0x7595771574
	private Void _OnJumpToStageListState(IStateBean stateBean) { }
	// RVA: 0x3159858 VA: 0x7595771858
	public Boolean CustomSetActive(Boolean active) { }
	// RVA: 0x31598d4 VA: 0x75957718d4
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x3159a90 VA: 0x7595771a90
	private Void _EventOnExit() { }
	// RVA: 0x3159cb4 VA: 0x7595771cb4
	private Void _EventOnBack() { }
	// RVA: 0x3159d24 VA: 0x7595771d24
	private Void _EventOnSetEmergency(Boolean emergency) { }
	// RVA: 0x315a198 VA: 0x7595772198
	private Void _OpenChat() { }
	// RVA: 0x3159df4 VA: 0x7595771df4
	private Void _EventOnKick() { }
	// RVA: 0x315a07c VA: 0x759577207c
	private Void _EventOnCheckNameCard() { }
	// RVA: 0x315a47c VA: 0x759577247c
	private Void _EventOnOpenStageDetailDialog() { }
	// RVA: 0x315a648 VA: 0x7595772648
	private Void _EventOnOpenSquadEffectInfoDialog() { }
	// RVA: 0x315a82c VA: 0x759577282c
	private Void _EventOnOpenStageChooseState() { }
	// RVA: 0x315aa04 VA: 0x7595772a04
	private Void _EventOnEnterGameOnPartnerOffline() { }
	// RVA: 0x315aef0 VA: 0x7595772ef0
	private Void _OpenNameCardPage() { }
	// RVA: 0x315b210 VA: 0x7595773210
	private Void _OnSendChat() { }
	// RVA: 0x3158180 VA: 0x7595770180
	private Void _UnRegiesterSvrEvent() { }
	// RVA: 0x3159010 VA: 0x7595771010
	private Void _RegisterSvrEvent() { }
	// RVA: 0x315b380 VA: 0x7595773380
	private Void _HandleTeamChanged(Object arg) { }
	// RVA: 0x315b624 VA: 0x7595773624
	private Void _HandleTeamChat(Object arg) { }
	// RVA: 0x315b880 VA: 0x7595773880
	private Void _HandleGetNameCardRet(Object arg) { }
	// RVA: 0x315ab30 VA: 0x7595772b30
	public Void CloseDialogsAndEmoticonPanel() { }
	// RVA: 0x315ba24 VA: 0x7595773a24
	public Void .ctor() { }
	// RVA: 0x315ba94 VA: 0x7595773a94
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x315ba9c VA: 0x7595773a9c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x315baa4 VA: 0x7595773aa4
	private Void <>xLuaBaseProxy_OnExit() { }
}
```