# CommonFriendAssistState

**Namespace:** `Torappu.UI.CommonFriendAssist`


## Fields

- `CommonFriendAssistView _view`

- `Button _btnReturn`

- `CommonFriendAssistStateBean m_bean`

- `Boolean m_inited`


## Methods

- `Void _InitIfNot()`

- `Void EventOnReturn()`

- `Void _ReqRefresh()`

- `Void _DoneRefresh(CommonFriendAssistData)`

- `Void Refresh()`

- `Void ApplyAssist(FriendItemModel)`

- `Void _ApplyAssistSuccess()`

- `Void ShowFriendAvatar(String)`

- `Void _OpenFriendNameCard(GetOtherPlayerNameCardResponse)`

- `Void ChangeProfGrp(ProfessionCategory)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnPreResume(Boolean)`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CommonFriendAssist
public class CommonFriendAssistState : PopupFadeState, ICtrl, ICtrl, ICtrl
{
	private CommonFriendAssistView _view; // 0x70
	private Button _btnReturn; // 0x78
	private CommonFriendAssistStateBean m_bean; // 0x80
	private Boolean m_inited; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnPreResume; // 0x10
	private static DelegateBridge __Hotfix0_OnResume; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0_EventOnReturn; // 0x28
	private static DelegateBridge __Hotfix0__ReqRefresh; // 0x30
	private static DelegateBridge __Hotfix0__DoneRefresh; // 0x38
	private static DelegateBridge __Hotfix0_Refresh; // 0x40
	private static DelegateBridge __Hotfix0_ApplyAssist; // 0x48
	private static DelegateBridge __Hotfix0__ApplyAssistSuccess; // 0x50
	private static DelegateBridge __Hotfix0_ShowFriendAvatar; // 0x58
	private static DelegateBridge __Hotfix0__OpenFriendNameCard; // 0x60
	private static DelegateBridge __Hotfix0_ChangeProfGrp; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70


	// RVA: 0x2c48c8c VA: 0x7595260c8c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2c48cf4 VA: 0x7595260cf4
	protected override Void OnEnter() { }
	// RVA: 0x2c48f54 VA: 0x7595260f54
	protected override Void OnPreResume(Boolean isFromStack) { }
	// RVA: 0x2c490e4 VA: 0x75952610e4
	protected override Void OnResume() { }
	// RVA: 0x2c48d5c VA: 0x7595260d5c
	private Void _InitIfNot() { }
	// RVA: 0x2c497dc VA: 0x75952617dc
	public Void EventOnReturn() { }
	// RVA: 0x2c491f0 VA: 0x75952611f0
	private Void _ReqRefresh() { }
	// RVA: 0x2c498b8 VA: 0x75952618b8
	private Void _DoneRefresh(CommonFriendAssistData data) { }
	// RVA: 0x2c49c00 VA: 0x7595261c00
	public Void Refresh() { }
	// RVA: 0x2c49c68 VA: 0x7595261c68
	public Void ApplyAssist(FriendItemModel model) { }
	// RVA: 0x2c49ddc VA: 0x7595261ddc
	private Void _ApplyAssistSuccess() { }
	// RVA: 0x2c49e64 VA: 0x7595261e64
	public Void ShowFriendAvatar(String uid) { }
	// RVA: 0x2c4a068 VA: 0x7595262068
	private Void _OpenFriendNameCard(GetOtherPlayerNameCardResponse response) { }
	// RVA: 0x2c4a17c VA: 0x759526217c
	public Void ChangeProfGrp(ProfessionCategory prof) { }
	// RVA: 0x2c4a398 VA: 0x7595262398
	public Void .ctor() { }
	// RVA: 0x2c4a500 VA: 0x7595262500
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2c4a508 VA: 0x7595262508
	private Void <>xLuaBaseProxy_OnPreResume(Boolean P0) { }
	// RVA: 0x2c4a514 VA: 0x7595262514
	private Void <>xLuaBaseProxy_OnResume() { }
}
```