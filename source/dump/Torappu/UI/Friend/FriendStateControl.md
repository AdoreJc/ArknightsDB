# FriendStateControl

**Namespace:** `Torappu.UI.Friend`


## Fields

- `StateEngine _stateEngine`

- `FriendListStateBean _stateBean`

- `Text _friendCount`

- `UICommonTrackPoint _friendTrackPoint`

- `Boolean m_isInited`

- `Boolean m_isAssistEnabled`


## Methods

- `Void _Init()`

- `Void SetAssistEnable(Boolean)`

- `Void OnFriendRequestList()`

- `Void ToFriendList()`

- `Void OnFriendList()`

- `Void ToFriendAssistList()`

- `Void OnNameCard()`

- `Void ToNameCard()`

- `Void OnFriendAssisList()`

- `Void ToFriendSearch()`

- `Void RemoveFriendSearch()`

- `Void ToFriendRequestList()`

- `Void RemoveFriendShowAssist()`

- `Void ToFriendShowAssistList()`

- `Void ToNameCardEditState()`

- `Void ToNameCardSkinChangeState()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Friend
public class FriendStateControl : DataBinder`1
{
	private StateEngine _stateEngine; // 0x20
	private TwoStateToggle[] _buttonFlag; // 0x28
	private FriendListStateBean _stateBean; // 0x30
	private Text _friendCount; // 0x38
	private UICommonTrackPoint _friendTrackPoint; // 0x40
	private Boolean m_isInited; // 0x48
	private Boolean m_isAssistEnabled; // 0x49
	private static DelegateBridge __Hotfix0__Init; // 0x0
	private static DelegateBridge __Hotfix0_SetAssistEnable; // 0x8
	private static DelegateBridge __Hotfix0_OnFriendRequestList; // 0x10
	private static DelegateBridge __Hotfix0_ToFriendList; // 0x18
	private static DelegateBridge __Hotfix0_OnFriendList; // 0x20
	private static DelegateBridge __Hotfix0_ToFriendAssistList; // 0x28
	private static DelegateBridge __Hotfix0_OnNameCard; // 0x30
	private static DelegateBridge __Hotfix0_ToNameCard; // 0x38
	private static DelegateBridge __Hotfix0_OnFriendAssisList; // 0x40
	private static DelegateBridge __Hotfix0_ToFriendSearch; // 0x48
	private static DelegateBridge __Hotfix0_RemoveFriendSearch; // 0x50
	private static DelegateBridge __Hotfix0_ToFriendRequestList; // 0x58
	private static DelegateBridge __Hotfix0_RemoveFriendShowAssist; // 0x60
	private static DelegateBridge __Hotfix0_ToFriendShowAssistList; // 0x68
	private static DelegateBridge __Hotfix0_ToNameCardEditState; // 0x70
	private static DelegateBridge __Hotfix0_ToNameCardSkinChangeState; // 0x78
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88


	// RVA: 0x28b5a5c VA: 0x7594ecda5c
	private Void _Init() { }
	// RVA: 0x28b5b3c VA: 0x7594ecdb3c
	public Void SetAssistEnable(Boolean isEnable) { }
	// RVA: 0x28b2740 VA: 0x7594eca740
	public Void OnFriendRequestList() { }
	// RVA: 0x28b5c60 VA: 0x7594ecdc60
	public Void ToFriendList() { }
	// RVA: 0x28af718 VA: 0x7594ec7718
	public Void OnFriendList() { }
	// RVA: 0x28b5cec VA: 0x7594ecdcec
	public Void ToFriendAssistList() { }
	// RVA: 0x28b5d8c VA: 0x7594ecdd8c
	public Void OnNameCard() { }
	// RVA: 0x28b5e48 VA: 0x7594ecde48
	public Void ToNameCard() { }
	// RVA: 0x28b5ed4 VA: 0x7594ecded4
	public Void OnFriendAssisList() { }
	// RVA: 0x28b5f90 VA: 0x7594ecdf90
	public Void ToFriendSearch() { }
	// RVA: 0x28b6080 VA: 0x7594ece080
	public Void RemoveFriendSearch() { }
	// RVA: 0x28b60f4 VA: 0x7594ece0f4
	public Void ToFriendRequestList() { }
	// RVA: 0x28b55e0 VA: 0x7594ecd5e0
	public Void RemoveFriendShowAssist() { }
	// RVA: 0x28af898 VA: 0x7594ec7898
	public Void ToFriendShowAssistList() { }
	// RVA: 0x28b6180 VA: 0x7594ece180
	public Void ToNameCardEditState() { }
	// RVA: 0x28b6208 VA: 0x7594ece208
	public Void ToNameCardSkinChangeState() { }
	// RVA: 0x28b6290 VA: 0x7594ece290
	public override Void OnValueChanged(FriendListProperty property) { }
	// RVA: 0x28b6430 VA: 0x7594ece430
	public Void .ctor() { }
}
```