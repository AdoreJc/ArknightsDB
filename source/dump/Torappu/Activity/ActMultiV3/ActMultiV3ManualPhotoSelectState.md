# ActMultiV3ManualPhotoSelectState

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `RectTransform _topMenuContainer`

- `ActMultiV3PhotoSelectView _view`

- `Boolean m_inited`

- `ActMultiV3ManualPhotoSelectStateBean m_stateBean`


## Methods

- `Void _InitIfNot()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _OnSelectPhoto(Int32)`

- `Void _OnApplyFriend()`

- `Void _OnSendFriendReqSuc(String)`

- `Void _OnCheckNameCard()`

- `Void _OpenNameCardDisplayPage(FriendDataWithNameCard)`

- `Boolean _TryGetNameCardData(String, out)`

- `Void _CacheNameCardData(String, FriendDataWithNameCard)`

- `Void _OnSubmitPhoto()`

- `Void _OnClickComittedPhoto()`

- `Void _OnShowHideDetail()`

- `Boolean _IsStateStable()`

- `Void <_OnCheckNameCard>b__17_0(GetOtherPlayerNameCardResponse)`

- `Void <_OnSubmitPhoto>b__21_0(ActMultiV3ChangePhotoResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3ManualPhotoSelectState : PopupFadeState, IValueMsgReceiver
{
	public const Int32 ON_SELECT_PHOTO; // 0x0
	public const Int32 ON_APPLY_FRIEND; // 0x0
	public const Int32 ON_CHECK_NAMECARD; // 0x0
	public const Int32 ON_SUBMIT_PHOTO; // 0x0
	public const Int32 ON_CLICK_COMITTED_PHOTO; // 0x0
	public const Int32 ON_SHOW_HIDE_DETAIL; // 0x0
	private RectTransform _topMenuContainer; // 0x70
	private ActMultiV3PhotoSelectView _view; // 0x78
	private Boolean m_inited; // 0x80
	private ActMultiV3ManualPhotoSelectStateBean m_stateBean; // 0x88
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnMessage; // 0x18
	private static DelegateBridge __Hotfix0__OnSelectPhoto; // 0x20
	private static DelegateBridge __Hotfix0__OnApplyFriend; // 0x28
	private static DelegateBridge __Hotfix0__OnSendFriendReqSuc; // 0x30
	private static DelegateBridge __Hotfix0__OnCheckNameCard; // 0x38
	private static DelegateBridge __Hotfix0__OpenNameCardDisplayPage; // 0x40
	private static DelegateBridge __Hotfix0__TryGetNameCardData; // 0x48
	private static DelegateBridge __Hotfix0__CacheNameCardData; // 0x50
	private static DelegateBridge __Hotfix0__OnSubmitPhoto; // 0x58
	private static DelegateBridge __Hotfix0__OnClickComittedPhoto; // 0x60
	private static DelegateBridge __Hotfix0__OnShowHideDetail; // 0x68
	private static DelegateBridge __Hotfix0__IsStateStable; // 0x70
	private static DelegateBridge _c__Hotfix0_ctor; // 0x78


	// RVA: 0x30f6c80 VA: 0x759570ec80
	public override IStateBean GetCacheBean() { }
	// RVA: 0x30f6ce8 VA: 0x759570ece8
	protected override Void OnEnter() { }
	// RVA: 0x30f6d8c VA: 0x759570ed8c
	private Void _InitIfNot() { }
	// RVA: 0x30f6e88 VA: 0x759570ee88
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x30f6fc4 VA: 0x759570efc4
	private Void _OnSelectPhoto(Int32 photoIdx) { }
	// RVA: 0x30f70b8 VA: 0x759570f0b8
	private Void _OnApplyFriend() { }
	// RVA: 0x30f7c08 VA: 0x759570fc08
	private Void _OnSendFriendReqSuc(String uid) { }
	// RVA: 0x30f73f0 VA: 0x759570f3f0
	private Void _OnCheckNameCard() { }
	// RVA: 0x30f7f10 VA: 0x759570ff10
	private Void _OpenNameCardDisplayPage(FriendDataWithNameCard friendData) { }
	// RVA: 0x30f7dc8 VA: 0x759570fdc8
	private Boolean _TryGetNameCardData(String uid, out FriendDataWithNameCard data) { }
	// RVA: 0x30f8018 VA: 0x7595710018
	private Void _CacheNameCardData(String uid, FriendDataWithNameCard data) { }
	// RVA: 0x30f7684 VA: 0x759570f684
	private Void _OnSubmitPhoto() { }
	// RVA: 0x30f7954 VA: 0x759570f954
	private Void _OnClickComittedPhoto() { }
	// RVA: 0x30f7a30 VA: 0x759570fa30
	private Void _OnShowHideDetail() { }
	// RVA: 0x30f7af8 VA: 0x759570faf8
	private Boolean _IsStateStable() { }
	// RVA: 0x30f8150 VA: 0x7595710150
	public Void .ctor() { }
	// RVA: 0x30f82fc VA: 0x75957102fc
	private Void <_OnCheckNameCard>b__17_0(GetOtherPlayerNameCardResponse response) { }
	// RVA: 0x30f8340 VA: 0x7595710340
	private Void <_OnSubmitPhoto>b__21_0(ActMultiV3ChangePhotoResponse response) { }
	// RVA: 0x30f8350 VA: 0x7595710350
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```