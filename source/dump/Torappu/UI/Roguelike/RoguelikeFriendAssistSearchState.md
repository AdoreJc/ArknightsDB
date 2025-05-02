# RoguelikeFriendAssistSearchState

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RectTransform _topMenuContainer`

- `RoguelikeFriendAssistSearchView _view`

- `TwoStateToggle _btnRefreshToggle`

- `Text _textCountDown`

- `RoguelikeFriendAssistSearchStateBean m_stateBean`

- `Boolean m_inited`

- `RoguelikeCommonTopMenu m_topMenu`

- `String m_topicId`

- `FriendAssistData m_cacheAssistData`

- `RoguelikeMenuAdapter m_menuAdapter`


## Methods

- `Void _RegisterToDetailState(IStateBean)`

- `Void _InitIfNot()`

- `Void _WrapperDismiss()`

- `Void _UpdateProp()`

- `Void _SendGetAssistListRequest(String, ProfessionCategory, Action)`

- `IEnumerator _WaitForRefreshCountDown()`

- `Void OnBtnRefresh()`

- `Void _OnAssistItemClick(FriendAssistData)`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnFriendAvatarClick(String)`

- `Void _OpenFriendNameCard(GetOtherPlayerNameCardResponse)`

- `Void <OnBtnRefresh>b__22_0()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeFriendAssistSearchState : PopupFadeState, IValueMsgReceiver
{
	public const Int32 ON_FRIEND_AVATAR_CLICK; // 0x0
	private RectTransform _topMenuContainer; // 0x70
	private RoguelikeFriendAssistSearchView _view; // 0x78
	private TwoStateToggle _btnRefreshToggle; // 0x80
	private Text _textCountDown; // 0x88
	private const Int32 COUNT_DOWN_SEC; // 0x0
	private RoguelikeFriendAssistSearchStateBean m_stateBean; // 0x90
	private Boolean m_inited; // 0x98
	private RoguelikeCommonTopMenu m_topMenu; // 0xa0
	private String m_topicId; // 0xa8
	private FriendAssistData m_cacheAssistData; // 0xb0
	private RoguelikeMenuAdapter m_menuAdapter; // 0xb8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0__RegisterToDetailState; // 0x20
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x28
	private static DelegateBridge __Hotfix0__WrapperDismiss; // 0x30
	private static DelegateBridge __Hotfix0__UpdateProp; // 0x38
	private static DelegateBridge __Hotfix0__SendGetAssistListRequest; // 0x40
	private static DelegateBridge __Hotfix0__WaitForRefreshCountDown; // 0x48
	private static DelegateBridge __Hotfix0_OnBtnRefresh; // 0x50
	private static DelegateBridge __Hotfix0__OnAssistItemClick; // 0x58
	private static DelegateBridge __Hotfix0_OnMessage; // 0x60
	private static DelegateBridge __Hotfix0__OnFriendAvatarClick; // 0x68
	private static DelegateBridge __Hotfix0__OpenFriendNameCard; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78


	// RVA: 0x2a39790 VA: 0x7595051790
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2a397f8 VA: 0x75950517f8
	protected override Void OnEnter() { }
	// RVA: 0x2a39bd0 VA: 0x7595051bd0
	protected override Void OnResume() { }
	// RVA: 0x2a39c60 VA: 0x7595051c60
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2a39dd8 VA: 0x7595051dd8
	private Void _RegisterToDetailState(IStateBean stateBean) { }
	// RVA: 0x2a39984 VA: 0x7595051984
	private Void _InitIfNot() { }
	// RVA: 0x2a3a0c0 VA: 0x75950520c0
	private Void _WrapperDismiss() { }
	// RVA: 0x2a39b08 VA: 0x7595051b08
	private Void _UpdateProp() { }
	// RVA: 0x2a3a27c VA: 0x759505227c
	private Void _SendGetAssistListRequest(String index, ProfessionCategory profession, Action onComplete) { }
	// RVA: 0x2a3a548 VA: 0x7595052548
	private IEnumerator _WaitForRefreshCountDown() { }
	// RVA: 0x2a3a61c VA: 0x759505261c
	public Void OnBtnRefresh() { }
	// RVA: 0x2a3a75c VA: 0x759505275c
	private Void _OnAssistItemClick(FriendAssistData assistData) { }
	// RVA: 0x2a3a888 VA: 0x7595052888
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2a3a930 VA: 0x7595052930
	private Void _OnFriendAvatarClick(String uid) { }
	// RVA: 0x2a3ab34 VA: 0x7595052b34
	private Void _OpenFriendNameCard(GetOtherPlayerNameCardResponse response) { }
	// RVA: 0x2a3ac48 VA: 0x7595052c48
	public Void .ctor() { }
	// RVA: 0x2a3ada0 VA: 0x7595052da0
	private Void <OnBtnRefresh>b__22_0() { }
	// RVA: 0x2a3ae10 VA: 0x7595052e10
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2a3ae18 VA: 0x7595052e18
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2a3ae20 VA: 0x7595052e20
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```