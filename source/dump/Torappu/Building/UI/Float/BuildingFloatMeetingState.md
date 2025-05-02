# BuildingFloatMeetingState

**Namespace:** `Torappu.Building.UI.Float`


## Fields

- `RectTransform _settleAnchor`

- `MeetingTransferStateView _transferStateView`

- `MeetingFloatStateCornerView _cornerView`

- `Transform _trackPointContainer`

- `GameObject _trackPointPrefab`

- `BuildingTwoContentNotify _socialNotify`

- `BuildingTwoContentNotify _cashNotify`

- `Boolean m_transferVisitNumServiceSent`

- `MeetingViewModel m_viewModel`

- `BuildingMeetingSession m_meetingSession`

- `Boolean m_visitNumberAvailable`


## Properties

- `IMeetingSession meetingSession`


## Methods

- `IMeetingSession get_meetingSession()`

- `Void _UpdateTransferringPanel()`

- `Void _RewardsHandler(List`1)`

- `Void EventOnDIYClick()`

- `Void EventOnBtnFriendClicked()`

- `Void EventOnSettleCreditClicked()`

- `Void _SendUpdateTransferServiceIfNeeded()`

- `Void _RefreshState()`

- `Void _TryShowTransferResult()`

- `Void <_SendUpdateTransferServiceIfNeeded>b__25_0(Int32)`

- `Void <>xLuaBaseProxy_OnInit()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnStateUpdated(Boolean)`

- `Void <>xLuaBaseProxy_OnPlayerDataChanged(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Float
public class BuildingFloatMeetingState : BuildingFloatVaultInfoState
{
	private RectTransform _settleAnchor; // 0xa0
	private MeetingTransferStateView _transferStateView; // 0xa8
	private MeetingFloatStateCornerView _cornerView; // 0xb0
	private Transform _trackPointContainer; // 0xb8
	private GameObject _trackPointPrefab; // 0xc0
	private BuildingTwoContentNotify _socialNotify; // 0xc8
	private BuildingTwoContentNotify _cashNotify; // 0xd0
	private Boolean m_transferVisitNumServiceSent; // 0xd8
	private MeetingViewModel m_viewModel; // 0xe0
	private BuildingMeetingSession m_meetingSession; // 0xe8
	private Boolean m_visitNumberAvailable; // 0xf0
	public static IMeetingSession s_meetingSession; // 0x0
	private static DelegateBridge __Hotfix0_get_meetingSession; // 0x8
	private static DelegateBridge __Hotfix0_get_state; // 0x10
	private static DelegateBridge __Hotfix0__UpdateTransferringPanel; // 0x18
	private static DelegateBridge __Hotfix0__RewardsHandler; // 0x20
	private static DelegateBridge __Hotfix0_OnInit; // 0x28
	private static DelegateBridge __Hotfix0_OnEnter; // 0x30
	private static DelegateBridge __Hotfix0_OnStateUpdated; // 0x38
	private static DelegateBridge __Hotfix0_OnPlayerDataChanged; // 0x40
	private static DelegateBridge __Hotfix0_EventOnDIYClick; // 0x48
	private static DelegateBridge __Hotfix0_EventOnBtnFriendClicked; // 0x50
	private static DelegateBridge __Hotfix0_EventOnSettleCreditClicked; // 0x58
	private static DelegateBridge __Hotfix0__SendUpdateTransferServiceIfNeeded; // 0x60
	private static DelegateBridge __Hotfix0__RefreshState; // 0x68
	private static DelegateBridge __Hotfix0__TryShowTransferResult; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78

	private IMeetingSession meetingSession { get; }
	protected override FloatState state { get; }

	// RVA: 0x3e1df0c VA: 0x7596435f0c
	private IMeetingSession get_meetingSession() { }
	// RVA: 0x3e1df7c VA: 0x7596435f7c
	protected override FloatState get_state() { }
	// RVA: 0x3e1dfe4 VA: 0x7596435fe4
	private Void _UpdateTransferringPanel() { }
	// RVA: 0x3e1e1b0 VA: 0x75964361b0
	private Void _RewardsHandler(List`1 rewards) { }
	// RVA: 0x3e1e46c VA: 0x759643646c
	protected override Void OnInit() { }
	// RVA: 0x3e1e718 VA: 0x7596436718
	protected override Void OnEnter() { }
	// RVA: 0x3e1e82c VA: 0x759643682c
	protected override Void OnStateUpdated(Boolean isActive) { }
	// RVA: 0x3e1e9a4 VA: 0x75964369a4
	protected override Void OnPlayerDataChanged(Object args) { }
	// RVA: 0x3e1ead4 VA: 0x7596436ad4
	public Void EventOnDIYClick() { }
	// RVA: 0x3e1ebf4 VA: 0x7596436bf4
	public Void EventOnBtnFriendClicked() { }
	// RVA: 0x3e1ec9c VA: 0x7596436c9c
	public Void EventOnSettleCreditClicked() { }
	// RVA: 0x3e1e638 VA: 0x7596436638
	private Void _SendUpdateTransferServiceIfNeeded() { }
	// RVA: 0x3e1e8e4 VA: 0x75964368e4
	private Void _RefreshState() { }
	// RVA: 0x3e1f240 VA: 0x7596437240
	private Void _TryShowTransferResult() { }
	// RVA: 0x3e1f384 VA: 0x7596437384
	public Void .ctor() { }
	// RVA: 0x3e1f464 VA: 0x7596437464
	private Void <_SendUpdateTransferServiceIfNeeded>b__25_0(Int32 result) { }
	// RVA: 0x3e1f494 VA: 0x7596437494
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x3e1f49c VA: 0x759643749c
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3e1f4a4 VA: 0x75964374a4
	private Void <>xLuaBaseProxy_OnStateUpdated(Boolean P0) { }
	// RVA: 0x3e1f4b0 VA: 0x75964374b0
	private Void <>xLuaBaseProxy_OnPlayerDataChanged(Object P0) { }
}
```