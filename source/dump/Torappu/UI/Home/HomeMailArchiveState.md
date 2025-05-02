# HomeMailArchiveState

**Namespace:** `Torappu.UI.Home`


## Fields

- `Image _imgBlurBkg`

- `RectTransform _backRect`

- `HomeMailArchiveListView _listView`

- `HomeMailArchiveStateBean m_stateBean`

- `Boolean m_hasInited`


## Methods

- `Void OnMessage(Int32, ValueBundle)`

- `Void EventOnMailClicked()`

- `Void EventOnBackClicked()`

- `Void _OnGetListProceed(MailCollectionGetListResponse)`

- `Void _EventOnItemClicked(String)`

- `Void _EventOnBarItemClicked(Int32)`

- `Void _InitIfNot()`

- `Void _OnJumpToArchiveDetailState(IStateBean)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeMailArchiveState : PopupFadeState, IValueMsgReceiver, IHotfixable
{
	public const Int32 ON_BAR_ITEM_CLICKED; // 0x0
	public const Int32 ON_ARCHIVE_ITEM_CLICKED; // 0x0
	private Image _imgBlurBkg; // 0x70
	private RectTransform _backRect; // 0x78
	private HomeMailArchiveListView _listView; // 0x80
	private HomeMailArchiveStateBean m_stateBean; // 0x88
	private Boolean m_hasInited; // 0x90
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnMessage; // 0x10
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x18
	private static DelegateBridge __Hotfix0_EventOnMailClicked; // 0x20
	private static DelegateBridge __Hotfix0_EventOnBackClicked; // 0x28
	private static DelegateBridge __Hotfix0__OnGetListProceed; // 0x30
	private static DelegateBridge __Hotfix0__EventOnItemClicked; // 0x38
	private static DelegateBridge __Hotfix0__EventOnBarItemClicked; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x48
	private static DelegateBridge __Hotfix0__OnJumpToArchiveDetailState; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x27f35e4 VA: 0x7594e0b5e4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x27f364c VA: 0x7594e0b64c
	protected override Void OnEnter() { }
	// RVA: 0x27f3a2c VA: 0x7594e0ba2c
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x27f3edc VA: 0x7594e0bedc
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x27f4054 VA: 0x7594e0c054
	public Void EventOnMailClicked() { }
	// RVA: 0x27f4214 VA: 0x7594e0c214
	public Void EventOnBackClicked() { }
	// RVA: 0x27f4358 VA: 0x7594e0c358
	private Void _OnGetListProceed(MailCollectionGetListResponse response) { }
	// RVA: 0x27f3c54 VA: 0x7594e0bc54
	private Void _EventOnItemClicked(String itemId) { }
	// RVA: 0x27f3b1c VA: 0x7594e0bb1c
	private Void _EventOnBarItemClicked(Int32 year) { }
	// RVA: 0x27f3924 VA: 0x7594e0b924
	private Void _InitIfNot() { }
	// RVA: 0x27f4418 VA: 0x7594e0c418
	private Void _OnJumpToArchiveDetailState(IStateBean sb) { }
	// RVA: 0x27f4534 VA: 0x7594e0c534
	public Void .ctor() { }
	// RVA: 0x27f4690 VA: 0x7594e0c690
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x27f4698 VA: 0x7594e0c698
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
}
```