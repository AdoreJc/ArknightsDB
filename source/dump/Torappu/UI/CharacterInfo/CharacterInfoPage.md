# CharacterInfoPage

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`

- `CharacterTokenDetailView _tokenDetailView`

- `RectTransform _tokenViewContainer`

- `CharacterTokenDetailView m_tokenDetailView`

- `ICharInfoHomeInitParam m_initHomeParamCache`

- `Boolean m_isTokenPanelInited`

- `HandBookJumpParam <jumpParam>k__BackingField`


## Properties

- `HandBookJumpParam jumpParam`


## Methods

- `HandBookJumpParam get_jumpParam()`

- `Void set_jumpParam(HandBookJumpParam)`

- `Void SetTopMenuActive(Boolean)`

- `ICharInfoHomeInitParam GetCharInitHomeParam()`

- `Void ShowTokenInfoPanel(CharTokenViewModel)`

- `Void _ReturnPage()`

- `Void _OnInitTopMenu(GameObject)`

- `Void _InitTokenPanelIfNot()`

- `IEnumerator <>n__0()`

- `Void <_OnInitTopMenu>b__21_0()`

- `AVGPageKey <>xLuaBaseProxy_get_avgPage()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `IEnumerator <>xLuaBaseProxy_InitStateEngine()`

- `Void <>xLuaBaseProxy_OnPageRouted()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoPage : StateEnginePage
{
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0xe8
	private CharacterTokenDetailView _tokenDetailView; // 0xf0
	private RectTransform _tokenViewContainer; // 0xf8
	private CharacterTokenDetailView m_tokenDetailView; // 0x100
	private ICharInfoHomeInitParam m_initHomeParamCache; // 0x108
	private Boolean m_isTokenPanelInited; // 0x110
	private HandBookJumpParam <jumpParam>k__BackingField; // 0x118
	private static DelegateBridge __Hotfix0_get_jumpParam; // 0x0
	private static DelegateBridge __Hotfix0_set_jumpParam; // 0x8
	private static DelegateBridge __Hotfix0_get_avgPage; // 0x10
	private static DelegateBridge __Hotfix0_SetTopMenuActive; // 0x18
	private static DelegateBridge __Hotfix0_GetCharInitHomeParam; // 0x20
	private static DelegateBridge __Hotfix0_ShowTokenInfoPanel; // 0x28
	private static DelegateBridge __Hotfix0__ReturnPage; // 0x30
	private static DelegateBridge __Hotfix0_OnCreate; // 0x38
	private static DelegateBridge __Hotfix0_InitStateEngine; // 0x40
	private static DelegateBridge __Hotfix0_OnPageRouted; // 0x48
	private static DelegateBridge __Hotfix0__OnInitTopMenu; // 0x50
	private static DelegateBridge __Hotfix0__InitTokenPanelIfNot; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public HandBookJumpParam jumpParam { get; set; }
	public override AVGPageKey avgPage { get; }

	// RVA: 0x2d3c534 VA: 0x7595354534
	public HandBookJumpParam get_jumpParam() { }
	// RVA: 0x2d3c59c VA: 0x759535459c
	public Void set_jumpParam(HandBookJumpParam value) { }
	// RVA: 0x2d3c620 VA: 0x7595354620
	public override AVGPageKey get_avgPage() { }
	// RVA: 0x2d3c688 VA: 0x7595354688
	public Void SetTopMenuActive(Boolean value) { }
	// RVA: 0x2d3c71c VA: 0x759535471c
	public ICharInfoHomeInitParam GetCharInitHomeParam() { }
	// RVA: 0x2d3c784 VA: 0x7595354784
	public Void ShowTokenInfoPanel(CharTokenViewModel charTokenViewModel) { }
	// RVA: 0x2d3c990 VA: 0x7595354990
	private Void _ReturnPage() { }
	// RVA: 0x2d3cac4 VA: 0x7595354ac4
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x2d3cd58 VA: 0x7595354d58
	protected override IEnumerator InitStateEngine() { }
	// RVA: 0x2d3ce2c VA: 0x7595354e2c
	protected override Void OnPageRouted() { }
	// RVA: 0x2d3ceb0 VA: 0x7595354eb0
	private Void _OnInitTopMenu(GameObject inst) { }
	// RVA: 0x2d3c87c VA: 0x759535487c
	private Void _InitTokenPanelIfNot() { }
	// RVA: 0x2d3cff8 VA: 0x7595354ff8
	public Void .ctor() { }
	// RVA: 0x2d3d068 VA: 0x7595355068
	private IEnumerator <>n__0() { }
	// RVA: 0x2d3d070 VA: 0x7595355070
	private Void <_OnInitTopMenu>b__21_0() { }
	// RVA: 0x2d3d074 VA: 0x7595355074
	private AVGPageKey <>xLuaBaseProxy_get_avgPage() { }
	// RVA: 0x2d3d07c VA: 0x759535507c
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x2d3d084 VA: 0x7595355084
	private IEnumerator <>xLuaBaseProxy_InitStateEngine() { }
	// RVA: 0x2d3d08c VA: 0x759535508c
	private Void <>xLuaBaseProxy_OnPageRouted() { }
}
```