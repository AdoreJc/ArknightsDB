# BuildingClueSendHomeState

**Namespace:** `Torappu.Building.UI.Meeting`


## Fields

- `UIRenderTextureImage _blueBackground`

- `MeetingClueSendOptionView _sendOptionView`

- `Button _prevPeerPageButton`

- `Button _nextPeerPageButton`

- `Int32 _peerPageSize`

- `MeetingPeerSendClueView _peerViewPrefab`

- `RectTransform _peerViewContainer`

- `GameObject _noFriendHint`

- `BuildingTwoContentNotify _notify`

- `Single _avatarViewScale`

- `IMeetingSession m_currentSession`

- `IMeetingClue m_selectClue`

- `Int32 m_peerPage`

- `Int32 m_pageCount`


## Properties

- `Int32 peerPageSize`


## Methods

- `Int32 get_peerPageSize()`

- `Void _InitPeerViewListIfNot()`

- `Void _SetupSendOptionView()`

- `Void _SetPeerPage(Int32)`

- `Void _SetupPeerView()`

- `Void SetupView()`

- `Void _OnPeerSendPressed(IPeer)`

- `Void OnPrevPeerPageButtonPressed()`

- `Void OnNextPeerPageButtonPressed()`

- `Void OnCloseButtonPressed()`

- `Void <_SetupSendOptionView>b__20_0(IMeetingClue, MeetingClueItemView)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Meeting
public class BuildingClueSendHomeState : State
{
	private UIRenderTextureImage _blueBackground; // 0x50
	private MeetingClueSendOptionView _sendOptionView; // 0x58
	private Button _prevPeerPageButton; // 0x60
	private Button _nextPeerPageButton; // 0x68
	private Int32 _peerPageSize; // 0x70
	private MeetingPeerSendClueView _peerViewPrefab; // 0x78
	private RectTransform _peerViewContainer; // 0x80
	private GameObject _noFriendHint; // 0x88
	private BuildingTwoContentNotify _notify; // 0x90
	private Single _avatarViewScale; // 0x98
	private IMeetingSession m_currentSession; // 0xa0
	private IMeetingClue m_selectClue; // 0xa8
	private Int32 m_peerPage; // 0xb0
	private Int32 m_pageCount; // 0xb4
	private List`1 m_peerViewList; // 0xb8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_get_peerPageSize; // 0x8
	private static DelegateBridge __Hotfix0__InitPeerViewListIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnEnter; // 0x18
	private static DelegateBridge __Hotfix0__SetupSendOptionView; // 0x20
	private static DelegateBridge __Hotfix0__SetPeerPage; // 0x28
	private static DelegateBridge __Hotfix0__SetupPeerView; // 0x30
	private static DelegateBridge __Hotfix0_SetupView; // 0x38
	private static DelegateBridge __Hotfix0__OnPeerSendPressed; // 0x40
	private static DelegateBridge __Hotfix0_OnPrevPeerPageButtonPressed; // 0x48
	private static DelegateBridge __Hotfix0_OnNextPeerPageButtonPressed; // 0x50
	private static DelegateBridge __Hotfix0_OnCloseButtonPressed; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	private Int32 peerPageSize { get; }

	// RVA: 0x3dedfb0 VA: 0x7596405fb0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3dee014 VA: 0x7596406014
	private Int32 get_peerPageSize() { }
	// RVA: 0x3dee07c VA: 0x759640607c
	private Void _InitPeerViewListIfNot() { }
	// RVA: 0x3dee2c4 VA: 0x75964062c4
	protected override Void OnEnter() { }
	// RVA: 0x3dee670 VA: 0x7596406670
	private Void _SetupSendOptionView() { }
	// RVA: 0x3dee74c VA: 0x759640674c
	private Void _SetPeerPage(Int32 page) { }
	// RVA: 0x3dee824 VA: 0x7596406824
	private Void _SetupPeerView() { }
	// RVA: 0x3dee460 VA: 0x7596406460
	private Void SetupView() { }
	// RVA: 0x3deed08 VA: 0x7596406d08
	private Void _OnPeerSendPressed(IPeer peer) { }
	// RVA: 0x3deeef8 VA: 0x7596406ef8
	public Void OnPrevPeerPageButtonPressed() { }
	// RVA: 0x3deef68 VA: 0x7596406f68
	public Void OnNextPeerPageButtonPressed() { }
	// RVA: 0x3deefd8 VA: 0x7596406fd8
	public Void OnCloseButtonPressed() { }
	// RVA: 0x3def054 VA: 0x7596407054
	public Void .ctor() { }
	// RVA: 0x3def0d8 VA: 0x75964070d8
	private Void <_SetupSendOptionView>b__20_0(IMeetingClue clue, MeetingClueItemView view) { }
	// RVA: 0x3def11c VA: 0x759640711c
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```