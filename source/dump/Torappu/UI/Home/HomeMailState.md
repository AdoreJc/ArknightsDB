# HomeMailState

**Namespace:** `Torappu.UI.Home`


## Fields

- `Image _imgBlurBkg`

- `HomeMailStateBean _stateBean`

- `GameObject _btnDebug`

- `HomeMailGroupView _groupView`

- `HomeMailTitleView _titleView`

- `Boolean m_isInited`

- `HomeMailIndex m_clickedMailIdCache`

- `Boolean m_sendFlag`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void OnJumpToDetailView(HomeMailDetailStateBean)`

- `Void OnJumpFromDetailView(HomeMailDetailStateBean)`

- `Void EventOnDetailClick(HomeMailIndex)`

- `Void EventOnReceiveAllClick()`

- `Void EventOnRemoveAllClick()`

- `Void EventOnMailClick(HomeMailIndex)`

- `Void EventOnBtnBackClick()`

- `Void EventOnArchiveClick()`

- `Void EventOnBtnDebugClick()`

- `Void _OnReceiveItemSucceed(ReceiveMailResponse)`

- `Void _OnReceiveAllItemSucceed(ReceiveAllMailResponse)`

- `Void _InitIfNot()`

- `Void _LoadData()`

- `Void _LoadMetaData(Boolean)`

- `Void _SendListMailBoxService(Boolean)`

- `Void _SendReceiveMailService(MailItemViewModel)`

- `Void _SendReceiveAllMailService()`

- `Void _SendRemoveAllReceivedMailService()`

- `Void <RegisterToDataListener>b__13_0(IStateBean)`

- `Void <RegisterFromDataListener>b__14_0(IStateBean)`

- `Void <_SendReceiveAllMailService>b__32_0(ReceiveAllMailResponse)`

- `Void <_SendRemoveAllReceivedMailService>b__33_0(RemoveAllRecievedMailResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeMailState : PopupFadeState, IValueMsgReceiver
{
	private readonly ListMailBoxResponse EMPTY_RESPONSE; // 0x70
	public const Int32 MSG_ON_MAIL_NEXT_PAGE; // 0x0
	private Image _imgBlurBkg; // 0x78
	private HomeMailStateBean _stateBean; // 0x80
	private GameObject _btnDebug; // 0x88
	private HomeMailGroupView _groupView; // 0x90
	private HomeMailTitleView _titleView; // 0x98
	private Boolean m_isInited; // 0xa0
	private HomeMailIndex m_clickedMailIdCache; // 0xa8
	private Boolean m_sendFlag; // 0xc0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnMessage; // 0x10
	private static DelegateBridge __Hotfix0_OnResume; // 0x18
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x20
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x28
	private static DelegateBridge __Hotfix0_OnJumpToDetailView; // 0x30
	private static DelegateBridge __Hotfix0_OnJumpFromDetailView; // 0x38
	private static DelegateBridge __Hotfix0_EventOnDetailClick; // 0x40
	private static DelegateBridge __Hotfix0_EventOnReceiveAllClick; // 0x48
	private static DelegateBridge __Hotfix0_EventOnRemoveAllClick; // 0x50
	private static DelegateBridge __Hotfix0_EventOnMailClick; // 0x58
	private static DelegateBridge __Hotfix0_EventOnBtnBackClick; // 0x60
	private static DelegateBridge __Hotfix0_EventOnArchiveClick; // 0x68
	private static DelegateBridge __Hotfix0_EventOnBtnDebugClick; // 0x70
	private static DelegateBridge __Hotfix0__OnReceiveItemSucceed; // 0x78
	private static DelegateBridge __Hotfix0__OnReceiveAllItemSucceed; // 0x80
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x88
	private static DelegateBridge __Hotfix0__LoadData; // 0x90
	private static DelegateBridge __Hotfix0__LoadMetaData; // 0x98
	private static DelegateBridge __Hotfix0__SendListMailBoxService; // 0xa0
	private static DelegateBridge __Hotfix0__SendReceiveMailService; // 0xa8
	private static DelegateBridge __Hotfix0__SendReceiveAllMailService; // 0xb0
	private static DelegateBridge __Hotfix0__SendRemoveAllReceivedMailService; // 0xb8
	private static DelegateBridge __Hotfix0_ReceiveItemsCoroutine; // 0xc0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc8


	// RVA: 0x27f5e44 VA: 0x7594e0de44
	public override IStateBean GetCacheBean() { }
	// RVA: 0x27f5eac VA: 0x7594e0deac
	protected override Void OnEnter() { }
	// RVA: 0x27f61c8 VA: 0x7594e0e1c8
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x27f67a4 VA: 0x7594e0e7a4
	protected override Void OnResume() { }
	// RVA: 0x27f6898 VA: 0x7594e0e898
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x27f6a10 VA: 0x7594e0ea10
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x27f6b88 VA: 0x7594e0eb88
	private Void OnJumpToDetailView(HomeMailDetailStateBean stateBean) { }
	// RVA: 0x27f6c7c VA: 0x7594e0ec7c
	private Void OnJumpFromDetailView(HomeMailDetailStateBean stateBean) { }
	// RVA: 0x27f6d80 VA: 0x7594e0ed80
	public Void EventOnDetailClick(HomeMailIndex index) { }
	// RVA: 0x27f6ec0 VA: 0x7594e0eec0
	public Void EventOnReceiveAllClick() { }
	// RVA: 0x27f7350 VA: 0x7594e0f350
	public Void EventOnRemoveAllClick() { }
	// RVA: 0x27f78bc VA: 0x7594e0f8bc
	public Void EventOnMailClick(HomeMailIndex index) { }
	// RVA: 0x27f7bf8 VA: 0x7594e0fbf8
	public Void EventOnBtnBackClick() { }
	// RVA: 0x27f7c84 VA: 0x7594e0fc84
	public Void EventOnArchiveClick() { }
	// RVA: 0x27f7e4c VA: 0x7594e0fe4c
	public Void EventOnBtnDebugClick() { }
	// RVA: 0x27f7eb0 VA: 0x7594e0feb0
	public Void _OnReceiveItemSucceed(ReceiveMailResponse response) { }
	// RVA: 0x27f80cc VA: 0x7594e100cc
	private Void _OnReceiveAllItemSucceed(ReceiveAllMailResponse response) { }
	// RVA: 0x27f600c VA: 0x7594e0e00c
	private Void _InitIfNot() { }
	// RVA: 0x27f60bc VA: 0x7594e0e0bc
	private Void _LoadData() { }
	// RVA: 0x27f8284 VA: 0x7594e10284
	public Void _LoadMetaData(Boolean isEnter) { }
	// RVA: 0x27f6270 VA: 0x7594e0e270
	private Void _SendListMailBoxService(Boolean isEnter) { }
	// RVA: 0x27f7a40 VA: 0x7594e0fa40
	private Void _SendReceiveMailService(MailItemViewModel targetMail) { }
	// RVA: 0x27f6f40 VA: 0x7594e0ef40
	private Void _SendReceiveAllMailService() { }
	// RVA: 0x27f73d0 VA: 0x7594e0f3d0
	private Void _SendRemoveAllReceivedMailService() { }
	// RVA: 0x27f5894 VA: 0x7594e0d894
	public static IEnumerator ReceiveItemsCoroutine(List`1 items) { }
	// RVA: 0x27f8514 VA: 0x7594e10514
	public Void .ctor() { }
	// RVA: 0x27f85c4 VA: 0x7594e105c4
	private Void <RegisterToDataListener>b__13_0(IStateBean stateBean) { }
	// RVA: 0x27f8644 VA: 0x7594e10644
	private Void <RegisterFromDataListener>b__14_0(IStateBean stateBean) { }
	// RVA: 0x27f86c4 VA: 0x7594e106c4
	private Void <_SendReceiveAllMailService>b__32_0(ReceiveAllMailResponse response) { }
	// RVA: 0x27f86c8 VA: 0x7594e106c8
	private Void <_SendRemoveAllReceivedMailService>b__33_0(RemoveAllRecievedMailResponse response) { }
	// RVA: 0x27f86d0 VA: 0x7594e106d0
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x27f86d8 VA: 0x7594e106d8
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x27f86e0 VA: 0x7594e106e0
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x27f86e8 VA: 0x7594e106e8
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
}
```