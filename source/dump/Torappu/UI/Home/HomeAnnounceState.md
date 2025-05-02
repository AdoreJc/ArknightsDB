# HomeAnnounceState

**Namespace:** `Torappu.UI.Home`


## Fields

- `HomeMainStateBean _stateBean`

- `UIUniWebView _webView`

- `Transform _prefabContainer`

- `Transform _tabContainer`

- `HomeAnnounceTab _announceTab`

- `ScrollRectSoftMask _softMask`

- `Boolean m_isInited`

- `AnnounceData m_database`


## Methods

- `Void _InitIfNot()`

- `Void OnReceivedMessage(UniWebView, UniWebViewMessage)`

- `Void _InitData()`

- `Void _SetDefaultAnnounce(AnnounceSinglePageData)`

- `Void OnSelectActivityGroup()`

- `Void OnSelectSystemGroup()`

- `Void OnSelectTab(Int32)`

- `Void _OnSelectTab(Int32, Boolean)`

- `Void _OnSelectTab(AnnounceSinglePageData, Boolean)`

- `Void _OnSelectGroup(AnnounceGroup, AnnounceSinglePageData, Boolean)`

- `Void _OpenWebView(AnnounceSinglePageData)`

- `Void _HandleWebViewMessage(UniWebViewMessage)`

- `Void _HandleJumpingCharRepoMessage(UniWebViewMessage)`

- `Void _HandleJumpingShopMessage(UniWebViewMessage)`

- `Void EventOnBtnBackClick()`

- `Void _HandleJumpToActivityStageMessage(UniWebViewMessage)`

- `IEnumerator <>n__0(TransactionContext)`

- `Void <_InitData>b__16_1(MIMEObject)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `IEnumerator <>xLuaBaseProxy_HideCoroutine(TransactionContext)`

- `Void <>xLuaBaseProxy_HideImmediately(TransactionContext)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeAnnounceState : PopupFloatState
{
	private HomeMainStateBean _stateBean; // 0x70
	private UIUniWebView _webView; // 0x78
	private Transform _prefabContainer; // 0x80
	private Transform _tabContainer; // 0x88
	private List`1 _tagList; // 0x90
	private HomeAnnounceTab _announceTab; // 0x98
	private ScrollRectSoftMask _softMask; // 0xa0
	private List`1 m_announceTabList; // 0xa8
	private Boolean m_isInited; // 0xb0
	private AnnounceData m_database; // 0xb8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x18
	private static DelegateBridge __Hotfix0_HideImmediately; // 0x20
	private static DelegateBridge __Hotfix0_OnReceivedMessage; // 0x28
	private static DelegateBridge __Hotfix0__InitData; // 0x30
	private static DelegateBridge __Hotfix0__SetDefaultAnnounce; // 0x38
	private static DelegateBridge __Hotfix0_OnSelectActivityGroup; // 0x40
	private static DelegateBridge __Hotfix0_OnSelectSystemGroup; // 0x48
	private static DelegateBridge __Hotfix0_OnSelectTab; // 0x50
	private static DelegateBridge __Hotfix0__OnSelectTab; // 0x58
	private static DelegateBridge __Hotfix1__OnSelectTab; // 0x60
	private static DelegateBridge __Hotfix0__GetAnnounceDataByAnnounceGroup; // 0x68
	private static DelegateBridge __Hotfix0__OnSelectGroup; // 0x70
	private static DelegateBridge __Hotfix0__OpenWebView; // 0x78
	private static DelegateBridge __Hotfix0__InjectGameInfoToUrl; // 0x80
	private static DelegateBridge __Hotfix0__GetGameInfoFromTag; // 0x88
	private static DelegateBridge __Hotfix0__HandleWebViewMessage; // 0x90
	private static DelegateBridge __Hotfix0__HandleJumpingCharRepoMessage; // 0x98
	private static DelegateBridge __Hotfix0__HandleJumpingShopMessage; // 0xa0
	private static DelegateBridge __Hotfix0_EventOnBtnBackClick; // 0xa8
	private static DelegateBridge __Hotfix0__HandleJumpToActivityStageMessage; // 0xb0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb8


	// RVA: 0x27e25dc VA: 0x7594dfa5dc
	private Void _InitIfNot() { }
	// RVA: 0x27e26ec VA: 0x7594dfa6ec
	public override IStateBean GetCacheBean() { }
	// RVA: 0x27e2754 VA: 0x7594dfa754
	protected override Void OnEnter() { }
	// RVA: 0x27e2abc VA: 0x7594dfaabc
	protected override IEnumerator HideCoroutine(TransactionContext context) { }
	// RVA: 0x27e2c28 VA: 0x7594dfac28
	protected override Void HideImmediately(TransactionContext context) { }
	// RVA: 0x27e2d68 VA: 0x7594dfad68
	public Void OnReceivedMessage(UniWebView webView, UniWebViewMessage message) { }
	// RVA: 0x27e28b0 VA: 0x7594dfa8b0
	private Void _InitData() { }
	// RVA: 0x27e35bc VA: 0x7594dfb5bc
	private Void _SetDefaultAnnounce(AnnounceSinglePageData announceData) { }
	// RVA: 0x27e3a54 VA: 0x7594dfba54
	public Void OnSelectActivityGroup() { }
	// RVA: 0x27e3ac8 VA: 0x7594dfbac8
	public Void OnSelectSystemGroup() { }
	// RVA: 0x27e3b3c VA: 0x7594dfbb3c
	public Void OnSelectTab(Int32 index) { }
	// RVA: 0x27e3bc0 VA: 0x7594dfbbc0
	private Void _OnSelectTab(Int32 index, Boolean unusedIsInit) { }
	// RVA: 0x27e3ec4 VA: 0x7594dfbec4
	private Void _OnSelectTab(AnnounceSinglePageData data, Boolean isInit) { }
	// RVA: 0x27e3fc4 VA: 0x7594dfbfc4
	private List`1 _GetAnnounceDataByAnnounceGroup(AnnounceGroup group) { }
	// RVA: 0x27e364c VA: 0x7594dfb64c
	private Void _OnSelectGroup(AnnounceGroup groupType, AnnounceSinglePageData pageData, Boolean isInit) { }
	// RVA: 0x27e3e1c VA: 0x7594dfbe1c
	private Void _OpenWebView(AnnounceSinglePageData data) { }
	// RVA: 0x27e4220 VA: 0x7594dfc220
	private static String _InjectGameInfoToUrl(String url) { }
	// RVA: 0x27e4490 VA: 0x7594dfc490
	private static String _GetGameInfoFromTag(String tag) { }
	// RVA: 0x27e2e04 VA: 0x7594dfae04
	private Void _HandleWebViewMessage(UniWebViewMessage msg) { }
	// RVA: 0x27e4b60 VA: 0x7594dfcb60
	private Void _HandleJumpingCharRepoMessage(UniWebViewMessage msg) { }
	// RVA: 0x27e4814 VA: 0x7594dfc814
	private Void _HandleJumpingShopMessage(UniWebViewMessage msg) { }
	// RVA: 0x27e4cc8 VA: 0x7594dfccc8
	public Void EventOnBtnBackClick() { }
	// RVA: 0x27e45bc VA: 0x7594dfc5bc
	private Void _HandleJumpToActivityStageMessage(UniWebViewMessage msg) { }
	// RVA: 0x27e4d3c VA: 0x7594dfcd3c
	public Void .ctor() { }
	// RVA: 0x27e4e00 VA: 0x7594dfce00
	private IEnumerator <>n__0(TransactionContext context) { }
	// RVA: 0x27e4e28 VA: 0x7594dfce28
	private Void <_InitData>b__16_1(MIMEObject response) { }
	// RVA: 0x27e50dc VA: 0x7594dfd0dc
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x27e50e4 VA: 0x7594dfd0e4
	private IEnumerator <>xLuaBaseProxy_HideCoroutine(TransactionContext P0) { }
	// RVA: 0x27e510c VA: 0x7594dfd10c
	private Void <>xLuaBaseProxy_HideImmediately(TransactionContext P0) { }
}
```