# RoguelikeFriendAssistDetailState

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RectTransform _topMenuContainer`

- `RoguelikeFriendAssistDetailView _view`

- `Boolean m_inited`

- `RoguelikeCommonTopMenu m_topMenu`

- `MenuAdapter m_menuAdapter`

- `RoguelikeFriendAssistDetailStateBean m_stateBean`


## Methods

- `Void _InitIfNot()`

- `Void _WrapperDismiss()`

- `Void _SendFriendRequest(Action)`

- `Void _SendRecruitCharRequest(Action)`

- `Void _RemoveToInitState()`

- `Void _UpdateGacha()`

- `Void OnAlreadyRequestClick()`

- `Void OnFriendRequestClick()`

- `Void OnRecruitCharClick()`

- `Void OnBtnCharShow()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnFriendAvatarClick(String)`

- `Void _OpenFriendNameCard(GetOtherPlayerNameCardResponse)`

- `Void <OnFriendRequestClick>b__17_0()`

- `Void <OnRecruitCharClick>b__18_0()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeFriendAssistDetailState : PopupFloatState, IValueMsgReceiver
{
	public const Int32 ON_FRIEND_AVATAR_CLICK; // 0x0
	private RectTransform _topMenuContainer; // 0x70
	private RoguelikeFriendAssistDetailView _view; // 0x78
	private Boolean m_inited; // 0x80
	private RoguelikeCommonTopMenu m_topMenu; // 0x88
	private MenuAdapter m_menuAdapter; // 0x90
	private RoguelikeFriendAssistDetailStateBean m_stateBean; // 0x98
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__WrapperDismiss; // 0x18
	private static DelegateBridge __Hotfix0__SendFriendRequest; // 0x20
	private static DelegateBridge __Hotfix0__SendRecruitCharRequest; // 0x28
	private static DelegateBridge __Hotfix0__RemoveToInitState; // 0x30
	private static DelegateBridge __Hotfix0__UpdateGacha; // 0x38
	private static DelegateBridge __Hotfix0_OnAlreadyRequestClick; // 0x40
	private static DelegateBridge __Hotfix0_OnFriendRequestClick; // 0x48
	private static DelegateBridge __Hotfix0_OnRecruitCharClick; // 0x50
	private static DelegateBridge __Hotfix0_OnBtnCharShow; // 0x58
	private static DelegateBridge __Hotfix0_OnMessage; // 0x60
	private static DelegateBridge __Hotfix0__OnFriendAvatarClick; // 0x68
	private static DelegateBridge __Hotfix0__OpenFriendNameCard; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78


	// RVA: 0x2a366f8 VA: 0x759504e6f8
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2a36760 VA: 0x759504e760
	protected override Void OnEnter() { }
	// RVA: 0x2a368f4 VA: 0x759504e8f4
	private Void _InitIfNot() { }
	// RVA: 0x2a36a8c VA: 0x759504ea8c
	private Void _WrapperDismiss() { }
	// RVA: 0x2a36b00 VA: 0x759504eb00
	private Void _SendFriendRequest(Action onComplete) { }
	// RVA: 0x2a36db8 VA: 0x759504edb8
	private Void _SendRecruitCharRequest(Action onComplete) { }
	// RVA: 0x2a37224 VA: 0x759504f224
	private Void _RemoveToInitState() { }
	// RVA: 0x2a3732c VA: 0x759504f32c
	private Void _UpdateGacha() { }
	// RVA: 0x2a374f0 VA: 0x759504f4f0
	public Void OnAlreadyRequestClick() { }
	// RVA: 0x2a3758c VA: 0x759504f58c
	public Void OnFriendRequestClick() { }
	// RVA: 0x2a37644 VA: 0x759504f644
	public Void OnRecruitCharClick() { }
	// RVA: 0x2a376fc VA: 0x759504f6fc
	public Void OnBtnCharShow() { }
	// RVA: 0x2a3785c VA: 0x759504f85c
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2a37904 VA: 0x759504f904
	private Void _OnFriendAvatarClick(String uid) { }
	// RVA: 0x2a37b08 VA: 0x759504fb08
	private Void _OpenFriendNameCard(GetOtherPlayerNameCardResponse response) { }
	// RVA: 0x2a37c1c VA: 0x759504fc1c
	public Void .ctor() { }
	// RVA: 0x2a37d74 VA: 0x759504fd74
	private Void <OnFriendRequestClick>b__17_0() { }
	// RVA: 0x2a37e60 VA: 0x759504fe60
	private Void <OnRecruitCharClick>b__18_0() { }
	// RVA: 0x2a37e78 VA: 0x759504fe78
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```