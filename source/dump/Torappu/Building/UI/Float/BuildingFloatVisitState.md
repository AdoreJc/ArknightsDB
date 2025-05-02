# BuildingFloatVisitState

**Namespace:** `Torappu.Building.UI.Float`


## Fields

- `BuildingTwoContentNotify _notify`

- `GameObject _btnVisitNext`

- `GameObject _iconVisitOrange`

- `GameObject _iconVisitGray`

- `Text _textSocialPoint`

- `Text _textRoomName`

- `BuildingNameCardView _nameCardView`

- `GetOtherPlayerNameCardResponse m_cachedResponse`

- `FriendInfo m_nextFriend`


## Methods

- `Void _UpdateSocialPoint()`

- `Void _UpdateRoomName(String)`

- `Void _OpenFriendNameCard(GetOtherPlayerNameCardResponse)`

- `Void OnSendClueButtonPressed()`

- `Void EventOnVisitNextClicked()`

- `Void EventOnNameCardClicked()`

- `Void OnEnable()`

- `Void OnDisable()`

- `Boolean CheckIfDataChanged(PlayerDataModel, PlayerDataModel, PlayerDataDelta)`

- `Void OnPlayerDataChanged()`

- `Void <EventOnNameCardClicked>b__19_0(GetOtherPlayerNameCardResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnStateUpdated(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Float
public class BuildingFloatVisitState : BuildingFloatState, IPlayerDataListener, IHotfixable
{
	private const String NAMECARD_REQUEST_SRC; // 0x0
	private BuildingTwoContentNotify _notify; // 0x40
	private GameObject _btnVisitNext; // 0x48
	private GameObject _iconVisitOrange; // 0x50
	private GameObject _iconVisitGray; // 0x58
	private Text _textSocialPoint; // 0x60
	private Text _textRoomName; // 0x68
	private BuildingNameCardView _nameCardView; // 0x70
	private GetOtherPlayerNameCardResponse m_cachedResponse; // 0x78
	private FriendInfo m_nextFriend; // 0x80
	private static DelegateBridge __Hotfix0_get_state; // 0x0
	private static DelegateBridge __Hotfix0__UpdateSocialPoint; // 0x8
	private static DelegateBridge __Hotfix0__UpdateRoomName; // 0x10
	private static DelegateBridge __Hotfix0__OpenFriendNameCard; // 0x18
	private static DelegateBridge __Hotfix0_OnEnter; // 0x20
	private static DelegateBridge __Hotfix0_OnStateUpdated; // 0x28
	private static DelegateBridge __Hotfix0_OnSendClueButtonPressed; // 0x30
	private static DelegateBridge __Hotfix0_EventOnVisitNextClicked; // 0x38
	private static DelegateBridge __Hotfix0_EventOnNameCardClicked; // 0x40
	private static DelegateBridge __Hotfix0_OnEnable; // 0x48
	private static DelegateBridge __Hotfix0_OnDisable; // 0x50
	private static DelegateBridge __Hotfix0_CheckIfDataChanged; // 0x58
	private static DelegateBridge __Hotfix0_OnPlayerDataChanged; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	protected override FloatState state { get; }

	// RVA: 0x3e2accc VA: 0x7596442ccc
	protected override FloatState get_state() { }
	// RVA: 0x3e2ad34 VA: 0x7596442d34
	private Void _UpdateSocialPoint() { }
	// RVA: 0x3e2ae04 VA: 0x7596442e04
	private Void _UpdateRoomName(String roomOwner) { }
	// RVA: 0x3e2aed4 VA: 0x7596442ed4
	private Void _OpenFriendNameCard(GetOtherPlayerNameCardResponse response) { }
	// RVA: 0x3e2afe8 VA: 0x7596442fe8
	protected override Void OnEnter() { }
	// RVA: 0x3e2b4b8 VA: 0x75964434b8
	protected override Void OnStateUpdated(Boolean isActive) { }
	// RVA: 0x3e2b558 VA: 0x7596443558
	public Void OnSendClueButtonPressed() { }
	// RVA: 0x3e2b69c VA: 0x759644369c
	public Void EventOnVisitNextClicked() { }
	// RVA: 0x3e2b788 VA: 0x7596443788
	public Void EventOnNameCardClicked() { }
	// RVA: 0x3e2ba0c VA: 0x7596443a0c
	private Void OnEnable() { }
	// RVA: 0x3e2ba78 VA: 0x7596443a78
	private Void OnDisable() { }
	// RVA: 0x3e2bae4 VA: 0x7596443ae4
	public Boolean CheckIfDataChanged(PlayerDataModel prevData, PlayerDataModel curData, PlayerDataDelta delta) { }
	// RVA: 0x3e2bc80 VA: 0x7596443c80
	public Void OnPlayerDataChanged() { }
	// RVA: 0x3e2bce8 VA: 0x7596443ce8
	public Void .ctor() { }
	// RVA: 0x3e2bd98 VA: 0x7596443d98
	private Void <EventOnNameCardClicked>b__19_0(GetOtherPlayerNameCardResponse response) { }
	// RVA: 0x3e2bdc8 VA: 0x7596443dc8
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3e2bdd0 VA: 0x7596443dd0
	private Void <>xLuaBaseProxy_OnStateUpdated(Boolean P0) { }
}
```