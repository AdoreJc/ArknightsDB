# SquadFriendAssistState

**Namespace:** `Torappu.UI.Squad`


## Fields

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`

- `SquadFriendView _friendView`

- `SquadFriendDetailView _detailView`

- `Text _textTips`

- `SquadFriendAssistStateBean m_stateBean`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void EventOnApplyAssist(SquadAssistData, Boolean)`

- `Void _SendAssistCharListRequest(ProfessionCategory, Boolean)`

- `Void _OnChangeProfessionTab(ProfessionCategory)`

- `Boolean _TryGetNameCardData(String, out)`

- `Void _CacheNameCardData(String, FriendDataWithNameCard)`

- `Void _ApplyAssistImpl(SquadAssistData, Boolean, FriendDataWithNameCard)`

- `Boolean _IsStateStable()`

- `Void RefreshSquadAssist()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnFriendAvatarClick(String)`

- `Void _OnGetNameCardSuc(GetOtherPlayerNameCardResponse)`

- `Void _OpenNameCardDisplayPage(FriendDataWithNameCard)`

- `Void _SelectAssistSkill(Int32)`

- `Void _SelectAssistEquip(String)`

- `Void _CloseAssistDetail()`

- `Void _ConfirmAssistChar()`

- `Void _SendFriendRequest(String)`

- `Void _OnSendFriendReqSuc(String)`

- `Void _OpenCharShowPage()`

- `Void <_InitIfNot>b__15_0(GameObject)`

- `Void <_InitIfNot>b__15_1()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Squad
public class SquadFriendAssistState : PopupFadeState, IValueMsgReceiver
{
	public const Int32 ON_FRIEND_AVATAR_CLICK; // 0x0
	public const Int32 ON_DETAIL_SKILL_CLICK; // 0x0
	public const Int32 ON_DETAIL_EQUIP_CLICK; // 0x0
	public const Int32 CLOSE_DETAIL_VIEW; // 0x0
	public const Int32 CONFIRM_ASSIST_CHAR; // 0x0
	public const Int32 SEND_FRIEND_REQUEST; // 0x0
	public const Int32 OPEN_CHAR_SHOW_PAGE; // 0x0
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0x70
	private SquadFriendView _friendView; // 0x78
	private SquadFriendDetailView _detailView; // 0x80
	private Text _textTips; // 0x88
	private SquadFriendAssistStateBean m_stateBean; // 0x90
	private Boolean m_isInited; // 0x98
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_EventOnApplyAssist; // 0x10
	private static DelegateBridge __Hotfix0_OnEnter; // 0x18
	private static DelegateBridge __Hotfix0_OnResume; // 0x20
	private static DelegateBridge __Hotfix0_OnExit; // 0x28
	private static DelegateBridge __Hotfix0__SendAssistCharListRequest; // 0x30
	private static DelegateBridge __Hotfix0__OnChangeProfessionTab; // 0x38
	private static DelegateBridge __Hotfix0__TryGetNameCardData; // 0x40
	private static DelegateBridge __Hotfix0__CacheNameCardData; // 0x48
	private static DelegateBridge __Hotfix0__ApplyAssistImpl; // 0x50
	private static DelegateBridge __Hotfix0__IsStateStable; // 0x58
	private static DelegateBridge __Hotfix0_RefreshSquadAssist; // 0x60
	private static DelegateBridge __Hotfix0_OnMessage; // 0x68
	private static DelegateBridge __Hotfix0__OnFriendAvatarClick; // 0x70
	private static DelegateBridge __Hotfix0__OnGetNameCardSuc; // 0x78
	private static DelegateBridge __Hotfix0__OpenNameCardDisplayPage; // 0x80
	private static DelegateBridge __Hotfix0__SelectAssistSkill; // 0x88
	private static DelegateBridge __Hotfix0__SelectAssistEquip; // 0x90
	private static DelegateBridge __Hotfix0__CloseAssistDetail; // 0x98
	private static DelegateBridge __Hotfix0__ConfirmAssistChar; // 0xa0
	private static DelegateBridge __Hotfix0__SendFriendRequest; // 0xa8
	private static DelegateBridge __Hotfix0__OnSendFriendReqSuc; // 0xb0
	private static DelegateBridge __Hotfix0__OpenCharShowPage; // 0xb8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc0


	// RVA: 0x2379df0 VA: 0x7594991df0
	private Void _InitIfNot() { }
	// RVA: 0x2379f00 VA: 0x7594991f00
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2379f68 VA: 0x7594991f68
	public Void EventOnApplyAssist(SquadAssistData friendApplied, Boolean isFriend) { }
	// RVA: 0x237a598 VA: 0x7594992598
	protected override Void OnEnter() { }
	// RVA: 0x237a85c VA: 0x759499285c
	protected override Void OnResume() { }
	// RVA: 0x237a8d0 VA: 0x75949928d0
	protected override Void OnExit() { }
	// RVA: 0x237a98c VA: 0x759499298c
	private Void _SendAssistCharListRequest(ProfessionCategory profession, Boolean refreshFlag) { }
	// RVA: 0x237ace8 VA: 0x7594992ce8
	private Void _OnChangeProfessionTab(ProfessionCategory profession) { }
	// RVA: 0x237a218 VA: 0x7594992218
	private Boolean _TryGetNameCardData(String uid, out FriendDataWithNameCard data) { }
	// RVA: 0x237ae00 VA: 0x7594992e00
	private Void _CacheNameCardData(String uid, FriendDataWithNameCard data) { }
	// RVA: 0x237a360 VA: 0x7594992360
	private Void _ApplyAssistImpl(SquadAssistData friendApplied, Boolean isFriend, FriendDataWithNameCard nameCardData) { }
	// RVA: 0x237af38 VA: 0x7594992f38
	private Boolean _IsStateStable() { }
	// RVA: 0x237b038 VA: 0x7594993038
	public Void RefreshSquadAssist() { }
	// RVA: 0x237b124 VA: 0x7594993124
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x237b284 VA: 0x7594993284
	private Void _OnFriendAvatarClick(String uid) { }
	// RVA: 0x237bc9c VA: 0x7594993c9c
	private Void _OnGetNameCardSuc(GetOtherPlayerNameCardResponse response) { }
	// RVA: 0x237bb94 VA: 0x7594993b94
	private Void _OpenNameCardDisplayPage(FriendDataWithNameCard friendData) { }
	// RVA: 0x237b4b0 VA: 0x75949934b0
	private Void _SelectAssistSkill(Int32 index) { }
	// RVA: 0x237b594 VA: 0x7594993594
	private Void _SelectAssistEquip(String equipId) { }
	// RVA: 0x237b678 VA: 0x7594993678
	private Void _CloseAssistDetail() { }
	// RVA: 0x237b744 VA: 0x7594993744
	private Void _ConfirmAssistChar() { }
	// RVA: 0x237b818 VA: 0x7594993818
	private Void _SendFriendRequest(String uid) { }
	// RVA: 0x237bd48 VA: 0x7594993d48
	private Void _OnSendFriendReqSuc(String uid) { }
	// RVA: 0x237ba70 VA: 0x7594993a70
	private Void _OpenCharShowPage() { }
	// RVA: 0x237be74 VA: 0x7594993e74
	public Void .ctor() { }
	// RVA: 0x237bf24 VA: 0x7594993f24
	private Void <_InitIfNot>b__15_0(GameObject gameObj) { }
	// RVA: 0x237c020 VA: 0x7594994020
	private Void <_InitIfNot>b__15_1() { }
	// RVA: 0x237c030 VA: 0x7594994030
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x237c038 VA: 0x7594994038
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x237c040 VA: 0x7594994040
	private Void <>xLuaBaseProxy_OnExit() { }
}
```