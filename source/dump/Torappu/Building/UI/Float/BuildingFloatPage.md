# BuildingFloatPage

**Namespace:** `Torappu.Building.UI.Float`


## Fields

- `PrefabInstHolder _topMenuHolder`

- `UIArchitectureCleanView _cleanPopupDialog`

- `UIArchitectureBuildView _buildPopupDialog`

- `UIArchitectureLevelupView _levelupPopupDialog`

- `UIArchitectureTeardownView _teardownPopupDialog`

- `UIArchitectureRoomDetailView _roomDetailView`

- `Image _blurMask`

- `Shader _blurShader`

- `UIRoomTypeColorMap _roomTypeColorMap`

- `BuildingFloatArchSwitchView _switchView`

- `DIYShopPanel m_diyShop`


## Properties

- `BuildingFloatArchSwitchView switchView`

- `UIArchitectureRoomDetailView arcRoomDetailView`


## Methods

- `BuildingFloatArchSwitchView get_switchView()`

- `UIArchitectureRoomDetailView get_arcRoomDetailView()`

- `Void NotifyArchPopViewShow(IUIArchitectureBaseView)`

- `Void NotifyArchPopViewClose(IUIArchitectureBaseView)`

- `Void SendFloatStateSignal(String)`

- `Boolean _ClosePopupViewAndInterruptBackEvent()`

- `Void _OnSelectRoom(Object)`

- `Void _OnUnSelectRoom(Object)`

- `Void _OnRoomRouteFail(Object)`

- `Void _OnBuildingModeChanged(Object)`

- `Void _OnOperationModeChanged(Object)`

- `Void _OnToDoNotifyStateChanged(Object)`

- `Void _OnPlayerDataChanged()`

- `Void _OnRequestDIY(Object)`

- `Void _OnBpRoomSettleRequested(Object)`

- `Void _OnBpRoomSettleImmediateRequested(Object)`

- `Void _OnBackBtnClicked()`

- `Void _OnRequestCharCtrlMode(Object)`

- `Void _OnStateUpdated(Object)`

- `Void OnSwitchModeBtnClicked()`

- `Void OnOperationModeSwitchClicked()`

- `Void OnStationManageClicked()`

- `Void PopupCleanDialog(Argument, Func`1)`

- `Void PopupBuildDialog(Argument, Func`1)`

- `Void PopupLevelupDialog(Argument, Func`1)`

- `Void PopupTeardownDialog(Argument, Func`1)`

- `Void ShowRoomDetailView(RoomSlotModel, Action, Action)`

- `Void SetDIYShopPanel(DIYShopPanel)`

- `Void _UpdateState()`

- `Void _ShowBlurMask()`

- `Void _ClearBlurMask()`

- `FloatState _CalculateCurrentState()`

- `Void _SwitchFloatState(FloatState)`

- `Void _GoBackFromVisitMode()`

- `Void _ConfirmExit(String, Action)`

- `Void _InitBuildingMusic()`

- `Void <OnCreate>b__21_0(GameObject)`

- `Void <OnCreate>b__21_1(GameObject)`

- `IEnumerator <>n__0(Boolean)`

- `AVGPageKey <>xLuaBaseProxy_get_avgPage()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `Void <>xLuaBaseProxy_OnStart()`

- `Void <>xLuaBaseProxy_OnStop()`

- `Void <>xLuaBaseProxy_OnStateEngineReady(Boolean)`

- `IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Float
public class BuildingFloatPage : BuildingCommonPage
{
	private static readonly ListSet`1 FADEOUT_TO_PAGES; // 0x0
	private PrefabInstHolder _topMenuHolder; // 0x110
	private DynamicBuildingFloatStateInstHolder[] _floatStateInstHolder; // 0x118
	private UIArchitectureCleanView _cleanPopupDialog; // 0x120
	private UIArchitectureBuildView _buildPopupDialog; // 0x128
	private UIArchitectureLevelupView _levelupPopupDialog; // 0x130
	private UIArchitectureTeardownView _teardownPopupDialog; // 0x138
	private UIArchitectureRoomDetailView _roomDetailView; // 0x140
	private Image _blurMask; // 0x148
	private Shader _blurShader; // 0x150
	private UIRoomTypeColorMap _roomTypeColorMap; // 0x158
	private BuildingFloatArchSwitchView _switchView; // 0x160
	private List`1 m_showingArchPopupViews; // 0x168
	private DIYShopPanel m_diyShop; // 0x170
	private List`1 m_floatStateList; // 0x178
	private static DelegateBridge __Hotfix0_get_avgPage; // 0x8
	private static DelegateBridge __Hotfix0_get_switchView; // 0x10
	private static DelegateBridge __Hotfix0_get_arcRoomDetailView; // 0x18
	private static DelegateBridge __Hotfix0_OnCreate; // 0x20
	private static DelegateBridge __Hotfix0_OnStart; // 0x28
	private static DelegateBridge __Hotfix0_OnStop; // 0x30
	private static DelegateBridge __Hotfix0_OnStateEngineReady; // 0x38
	private static DelegateBridge __Hotfix0_RegisterBuildingEvents; // 0x40
	private static DelegateBridge __Hotfix0_EffectsOnHide; // 0x48
	private static DelegateBridge __Hotfix0_NotifyArchPopViewShow; // 0x50
	private static DelegateBridge __Hotfix0_NotifyArchPopViewClose; // 0x58
	private static DelegateBridge __Hotfix0_SendFloatStateSignal; // 0x60
	private static DelegateBridge __Hotfix0__ClosePopupViewAndInterruptBackEvent; // 0x68
	private static DelegateBridge __Hotfix0__OnSelectRoom; // 0x70
	private static DelegateBridge __Hotfix0__OnUnSelectRoom; // 0x78
	private static DelegateBridge __Hotfix0__OnRoomRouteFail; // 0x80
	private static DelegateBridge __Hotfix0__OnBuildingModeChanged; // 0x88
	private static DelegateBridge __Hotfix0__OnOperationModeChanged; // 0x90
	private static DelegateBridge __Hotfix0__OnToDoNotifyStateChanged; // 0x98
	private static DelegateBridge __Hotfix0__OnPlayerDataChanged; // 0xa0
	private static DelegateBridge __Hotfix0__OnRequestDIY; // 0xa8
	private static DelegateBridge __Hotfix0__OnBpRoomSettleRequested; // 0xb0
	private static DelegateBridge __Hotfix0__OnBpRoomSettleImmediateRequested; // 0xb8
	private static DelegateBridge __Hotfix0__OnBackBtnClicked; // 0xc0
	private static DelegateBridge __Hotfix0__OnRequestCharCtrlMode; // 0xc8
	private static DelegateBridge __Hotfix0__OnStateUpdated; // 0xd0
	private static DelegateBridge __Hotfix0_OnSwitchModeBtnClicked; // 0xd8
	private static DelegateBridge __Hotfix0_OnOperationModeSwitchClicked; // 0xe0
	private static DelegateBridge __Hotfix0_OnStationManageClicked; // 0xe8
	private static DelegateBridge __Hotfix0_PopupCleanDialog; // 0xf0
	private static DelegateBridge __Hotfix0_PopupBuildDialog; // 0xf8
	private static DelegateBridge __Hotfix0_PopupLevelupDialog; // 0x100
	private static DelegateBridge __Hotfix0_PopupTeardownDialog; // 0x108
	private static DelegateBridge __Hotfix0_ShowRoomDetailView; // 0x110
	private static DelegateBridge __Hotfix0_SetDIYShopPanel; // 0x118
	private static DelegateBridge __Hotfix0__UpdateState; // 0x120
	private static DelegateBridge __Hotfix0__ShowBlurMask; // 0x128
	private static DelegateBridge __Hotfix0__ClearBlurMask; // 0x130
	private static DelegateBridge __Hotfix0__GetBuildingDialogConfirmCallback; // 0x138
	private static DelegateBridge __Hotfix0__CalculateCurrentState; // 0x140
	private static DelegateBridge __Hotfix0__SwitchFloatState; // 0x148
	private static DelegateBridge __Hotfix0__GoBackFromVisitMode; // 0x150
	private static DelegateBridge __Hotfix0__ConfirmExit; // 0x158
	private static DelegateBridge __Hotfix0__InitBuildingMusic; // 0x160
	private static DelegateBridge _c__Hotfix0_ctor; // 0x168

	public override AVGPageKey avgPage { get; }
	public BuildingFloatArchSwitchView switchView { get; }
	public UIArchitectureRoomDetailView arcRoomDetailView { get; }

	// RVA: 0x3e12554 VA: 0x759642a554
	public override AVGPageKey get_avgPage() { }
	// RVA: 0x3e125cc VA: 0x759642a5cc
	public BuildingFloatArchSwitchView get_switchView() { }
	// RVA: 0x3e12644 VA: 0x759642a644
	public UIArchitectureRoomDetailView get_arcRoomDetailView() { }
	// RVA: 0x3e126bc VA: 0x759642a6bc
	protected override Void OnCreate(DataBundle savedInstance) { }
	// RVA: 0x3e12924 VA: 0x759642a924
	protected override Void OnStart() { }
	// RVA: 0x3e12b7c VA: 0x759642ab7c
	protected override Void OnStop() { }
	// RVA: 0x3e12d8c VA: 0x759642ad8c
	protected override Void OnStateEngineReady(Boolean isFromStack) { }
	// RVA: 0x3e12f9c VA: 0x759642af9c
	public override ListDict`2 RegisterBuildingEvents() { }
	// RVA: 0x3e1335c VA: 0x759642b35c
	protected override IEnumerator EffectsOnHide(Boolean isIntoStack) { }
	// RVA: 0x3e1345c VA: 0x759642b45c
	public Void NotifyArchPopViewShow(IUIArchitectureBaseView view) { }
	// RVA: 0x3e135a8 VA: 0x759642b5a8
	public Void NotifyArchPopViewClose(IUIArchitectureBaseView view) { }
	// RVA: 0x3e13658 VA: 0x759642b658
	public Void SendFloatStateSignal(String signal) { }
	// RVA: 0x3e1375c VA: 0x759642b75c
	private Boolean _ClosePopupViewAndInterruptBackEvent() { }
	// RVA: 0x3e1396c VA: 0x759642b96c
	private Void _OnSelectRoom(Object arg) { }
	// RVA: 0x3e139f8 VA: 0x759642b9f8
	private Void _OnUnSelectRoom(Object arg) { }
	// RVA: 0x3e13a84 VA: 0x759642ba84
	private Void _OnRoomRouteFail(Object arg) { }
	// RVA: 0x3e13b10 VA: 0x759642bb10
	private Void _OnBuildingModeChanged(Object arg) { }
	// RVA: 0x3e13b9c VA: 0x759642bb9c
	private Void _OnOperationModeChanged(Object arg) { }
	// RVA: 0x3e13c28 VA: 0x759642bc28
	private Void _OnToDoNotifyStateChanged(Object arg) { }
	// RVA: 0x3e13cb4 VA: 0x759642bcb4
	private Void _OnPlayerDataChanged() { }
	// RVA: 0x3e13d2c VA: 0x759642bd2c
	private Void _OnRequestDIY(Object arg) { }
	// RVA: 0x3e13df0 VA: 0x759642bdf0
	private Void _OnBpRoomSettleRequested(Object arg) { }
	// RVA: 0x3e13f58 VA: 0x759642bf58
	private Void _OnBpRoomSettleImmediateRequested(Object arg) { }
	// RVA: 0x3e140d4 VA: 0x759642c0d4
	private Void _OnBackBtnClicked() { }
	// RVA: 0x3e1485c VA: 0x759642c85c
	private Void _OnRequestCharCtrlMode(Object arg) { }
	// RVA: 0x3e14a1c VA: 0x759642ca1c
	private Void _OnStateUpdated(Object arg) { }
	// RVA: 0x3e14e94 VA: 0x759642ce94
	public Void OnSwitchModeBtnClicked() { }
	// RVA: 0x3e14f30 VA: 0x759642cf30
	public Void OnOperationModeSwitchClicked() { }
	// RVA: 0x3e14ff4 VA: 0x759642cff4
	public Void OnStationManageClicked() { }
	// RVA: 0x3e15084 VA: 0x759642d084
	public Void PopupCleanDialog(Argument arg, Func`1 onConfirm) { }
	// RVA: 0x3e154cc VA: 0x759642d4cc
	public Void PopupBuildDialog(Argument arg, Func`1 onConfirm) { }
	// RVA: 0x3e156a8 VA: 0x759642d6a8
	public Void PopupLevelupDialog(Argument arg, Func`1 onConfirm) { }
	// RVA: 0x3e15884 VA: 0x759642d884
	public Void PopupTeardownDialog(Argument arg, Func`1 onConfirm) { }
	// RVA: 0x3e15a60 VA: 0x759642da60
	public Void ShowRoomDetailView(RoomSlotModel model, Action onTeardown, Action onLevelup) { }
	// RVA: 0x3e15dd4 VA: 0x759642ddd4
	public Void SetDIYShopPanel(DIYShopPanel shop) { }
	// RVA: 0x3e129b0 VA: 0x759642a9b0
	private Void _UpdateState() { }
	// RVA: 0x3e15260 VA: 0x759642d260
	private Void _ShowBlurMask() { }
	// RVA: 0x3e12c74 VA: 0x759642ac74
	private Void _ClearBlurMask() { }
	// RVA: 0x3e153a8 VA: 0x759642d3a8
	private Func`1 _GetBuildingDialogConfirmCallback(Func`1 callback) { }
	// RVA: 0x3e14b34 VA: 0x759642cb34
	private FloatState _CalculateCurrentState() { }
	// RVA: 0x3e15e68 VA: 0x759642de68
	private Void _SwitchFloatState(FloatState state) { }
	// RVA: 0x3e14478 VA: 0x759642c478
	private Void _GoBackFromVisitMode() { }
	// RVA: 0x3e14720 VA: 0x759642c720
	private Void _ConfirmExit(String content, Action exitAction) { }
	// RVA: 0x3e12a34 VA: 0x759642aa34
	private Void _InitBuildingMusic() { }
	// RVA: 0x3e16058 VA: 0x759642e058
	public Void .ctor() { }
	// RVA: 0x3e1617c VA: 0x759642e17c
	private static Void .cctor() { }
	// RVA: 0x3e162a4 VA: 0x759642e2a4
	private Void <OnCreate>b__21_0(GameObject inst) { }
	// RVA: 0x3e16368 VA: 0x759642e368
	private Void <OnCreate>b__21_1(GameObject obj) { }
	// RVA: 0x3e165ac VA: 0x759642e5ac
	private IEnumerator <>n__0(Boolean isIntoStack) { }
	// RVA: 0x3e165b8 VA: 0x759642e5b8
	private AVGPageKey <>xLuaBaseProxy_get_avgPage() { }
	// RVA: 0x3e165c0 VA: 0x759642e5c0
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x3e165c8 VA: 0x759642e5c8
	private Void <>xLuaBaseProxy_OnStart() { }
	// RVA: 0x3e165d0 VA: 0x759642e5d0
	private Void <>xLuaBaseProxy_OnStop() { }
	// RVA: 0x3e165d8 VA: 0x759642e5d8
	private Void <>xLuaBaseProxy_OnStateEngineReady(Boolean P0) { }
	// RVA: 0x3e165e4 VA: 0x759642e5e4
	private ListDict`2 <>xLuaBaseProxy_RegisterBuildingEvents() { }
	// RVA: 0x3e165ec VA: 0x759642e5ec
	private IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean P0) { }
}
```