# BuildingFloatToDoNotifyState

**Namespace:** `Torappu.Building.UI.Float`


## Fields

- `BuildingToDoNotifyView _notifyView`

- `TwoStateToggle _toggleNormal`

- `TwoStateToggle _toggleEmer`

- `BuildingToDoCategory m_selectedCategory`

- `BuildingToDoType m_selectedType`

- `BuildingToDoNotifyModel m_viewModel`


## Methods

- `Void EventOnTabNormalClicked()`

- `Void EventOnTabEmerClicked()`

- `Void _OnPlayerDataChanged(Object)`

- `Void _OnHilightedMaskClicked(Object)`

- `Void _OnToDoItemClicked(BuildingToDoNotifyItemModel)`

- `Void _OnGainAllIntimacySuc(BuildingGainAllIntimacyResponse, String)`

- `Void _OnNewProductItemClicked(BuildingToDoNotifyItemModel)`

- `Void _OnNewFavorItemClicked(BuildingToDoNotifyItemModel)`

- `Void _OnNewOrdersItemClicked(BuildingToDoNotifyItemModel)`

- `Void _OnBatchWorkClicked()`

- `Void _OnBatchRestClicked()`

- `Void _OnProcessBatchOrder(BuildingDeliveryBatchOrderResponse)`

- `Void _DoBatchOrderToast(ListDict`2)`

- `Void _SendGainAllIntimacyService()`

- `String _PickRandomCharForGainAllIntimacyVoice()`

- `Void _UpdateStatus(BuildingToDoCategory, BuildingToDoType)`

- `Void _UpdateView()`

- `Void _OnLocalTrackUpdate(Object)`

- `Void <>xLuaBaseProxy_OnStateUpdated(Boolean)`

- `Void <>xLuaBaseProxy_OnInit()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Float
public class BuildingFloatToDoNotifyState : BuildingFloatState
{
	private const Single TOAST_DELAY; // 0x0
	private BuildingToDoNotifyView _notifyView; // 0x40
	private TwoStateToggle _toggleNormal; // 0x48
	private TwoStateToggle _toggleEmer; // 0x50
	private Text[] _textsNormalCount; // 0x58
	private Text[] _textsEmerCount; // 0x60
	private BuildingToDoCategory m_selectedCategory; // 0x68
	private BuildingToDoType m_selectedType; // 0x6c
	private BuildingToDoNotifyModel m_viewModel; // 0x70
	private static DelegateBridge __Hotfix0_get_state; // 0x0
	private static DelegateBridge __Hotfix0_OnStateUpdated; // 0x8
	private static DelegateBridge __Hotfix0_OnInit; // 0x10
	private static DelegateBridge __Hotfix0_OnEnter; // 0x18
	private static DelegateBridge __Hotfix0_OnExit; // 0x20
	private static DelegateBridge __Hotfix0_EventOnTabNormalClicked; // 0x28
	private static DelegateBridge __Hotfix0_EventOnTabEmerClicked; // 0x30
	private static DelegateBridge __Hotfix0__OnPlayerDataChanged; // 0x38
	private static DelegateBridge __Hotfix0__OnHilightedMaskClicked; // 0x40
	private static DelegateBridge __Hotfix0__OnToDoItemClicked; // 0x48
	private static DelegateBridge __Hotfix0__OnGainAllIntimacySuc; // 0x50
	private static DelegateBridge __Hotfix0__OnNewProductItemClicked; // 0x58
	private static DelegateBridge __Hotfix0__OnNewFavorItemClicked; // 0x60
	private static DelegateBridge __Hotfix0__OnNewOrdersItemClicked; // 0x68
	private static DelegateBridge __Hotfix0__OnBatchWorkClicked; // 0x70
	private static DelegateBridge __Hotfix0__OnBatchRestClicked; // 0x78
	private static DelegateBridge __Hotfix0__OnProcessBatchOrder; // 0x80
	private static DelegateBridge __Hotfix0__GenSyncSettleInfos; // 0x88
	private static DelegateBridge __Hotfix0__CalculateRoomSettleInfos; // 0x90
	private static DelegateBridge __Hotfix0__DoBatchOrderToast; // 0x98
	private static DelegateBridge __Hotfix0__SendGainAllIntimacyService; // 0xa0
	private static DelegateBridge __Hotfix0__PickRandomCharForGainAllIntimacyVoice; // 0xa8
	private static DelegateBridge __Hotfix0__UpdateStatus; // 0xb0
	private static DelegateBridge __Hotfix0__UpdateView; // 0xb8
	private static DelegateBridge __Hotfix0__TrySwitchToOverview; // 0xc0
	private static DelegateBridge __Hotfix0__UpdateTabButton; // 0xc8
	private static DelegateBridge __Hotfix0__OnLocalTrackUpdate; // 0xd0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd8

	protected override FloatState state { get; }

	// RVA: 0x3e21450 VA: 0x7596439450
	protected override FloatState get_state() { }
	// RVA: 0x3e214b8 VA: 0x75964394b8
	protected override Void OnStateUpdated(Boolean isActive) { }
	// RVA: 0x3e21698 VA: 0x7596439698
	protected override Void OnInit() { }
	// RVA: 0x3e21764 VA: 0x7596439764
	protected override Void OnEnter() { }
	// RVA: 0x3e21960 VA: 0x7596439960
	protected override Void OnExit() { }
	// RVA: 0x3e21b9c VA: 0x7596439b9c
	public Void EventOnTabNormalClicked() { }
	// RVA: 0x3e21d4c VA: 0x7596439d4c
	public Void EventOnTabEmerClicked() { }
	// RVA: 0x3e21dd8 VA: 0x7596439dd8
	private Void _OnPlayerDataChanged(Object arg) { }
	// RVA: 0x3e21e6c VA: 0x7596439e6c
	private Void _OnHilightedMaskClicked(Object arg) { }
	// RVA: 0x3e21ef0 VA: 0x7596439ef0
	private Void _OnToDoItemClicked(BuildingToDoNotifyItemModel selectedModel) { }
	// RVA: 0x3e22500 VA: 0x759643a500
	private Void _OnGainAllIntimacySuc(BuildingGainAllIntimacyResponse response, String voiceChar) { }
	// RVA: 0x3e22060 VA: 0x759643a060
	private Void _OnNewProductItemClicked(BuildingToDoNotifyItemModel selectedModel) { }
	// RVA: 0x3e221d8 VA: 0x759643a1d8
	private Void _OnNewFavorItemClicked(BuildingToDoNotifyItemModel selectedModel) { }
	// RVA: 0x3e22340 VA: 0x759643a340
	private Void _OnNewOrdersItemClicked(BuildingToDoNotifyItemModel selectedModel) { }
	// RVA: 0x3e22438 VA: 0x759643a438
	private Void _OnBatchWorkClicked() { }
	// RVA: 0x3e2249c VA: 0x759643a49c
	private Void _OnBatchRestClicked() { }
	// RVA: 0x3e22ba4 VA: 0x759643aba4
	private Void _OnProcessBatchOrder(BuildingDeliveryBatchOrderResponse resp) { }
	// RVA: 0x3e22e78 VA: 0x759643ae78
	private List`1 _GenSyncSettleInfos(BlueprintMode bpMode, Dictionary`2 rewardPairs) { }
	// RVA: 0x3e232b4 VA: 0x759643b2b4
	private List`1 _CalculateRoomSettleInfos(BlueprintMode bpMode, String slotId, List`1 rewards) { }
	// RVA: 0x3e23088 VA: 0x759643b088
	private Void _DoBatchOrderToast(ListDict`2 otherCountDict) { }
	// RVA: 0x3e22854 VA: 0x759643a854
	private Void _SendGainAllIntimacyService() { }
	// RVA: 0x3e23650 VA: 0x759643b650
	private String _PickRandomCharForGainAllIntimacyVoice() { }
	// RVA: 0x3e2156c VA: 0x759643956c
	private Void _UpdateStatus(BuildingToDoCategory targetCategory, BuildingToDoType targetType) { }
	// RVA: 0x3e23a08 VA: 0x759643ba08
	private Void _UpdateView() { }
	// RVA: 0x3e21c28 VA: 0x7596439c28
	private static Void _TrySwitchToOverview() { }
	// RVA: 0x3e23ab4 VA: 0x759643bab4
	private static Void _UpdateTabButton(TwoStateToggle toggle, Text[] textsCount, BuildingToDoNotifyModel viewModel, BuildingToDoCategory tabCategory, BuildingToDoCategory selectedCategory) { }
	// RVA: 0x3e23c1c VA: 0x759643bc1c
	private Void _OnLocalTrackUpdate(Object arg) { }
	// RVA: 0x3e23cac VA: 0x759643bcac
	public Void .ctor() { }
	// RVA: 0x3e23d58 VA: 0x759643bd58
	private Void <>xLuaBaseProxy_OnStateUpdated(Boolean P0) { }
	// RVA: 0x3e23d60 VA: 0x759643bd60
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x3e23d64 VA: 0x759643bd64
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3e23d68 VA: 0x759643bd68
	private Void <>xLuaBaseProxy_OnExit() { }
}
```