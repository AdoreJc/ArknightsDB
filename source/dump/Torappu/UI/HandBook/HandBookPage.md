# HandBookPage

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `TopMenuDynamicPrefabInstHolder _topMenuHolder`

- `GameObject _transObject`

- `HandBookJumpParam <jumpParam>k__BackingField`


## Properties

- `HandBookJumpParam jumpParam`


## Methods

- `HandBookJumpParam get_jumpParam()`

- `Void set_jumpParam(HandBookJumpParam)`

- `Void SetTopMenuActive(Boolean)`

- `Void SetTranObjectActive(Boolean)`

- `Void _ReturnPage()`

- `Void <OnCreate>b__11_0(GameObject)`

- `Void <OnCreate>b__11_1()`

- `IEnumerator <>n__0()`

- `AVGPageKey <>xLuaBaseProxy_get_avgPage()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `IEnumerator <>xLuaBaseProxy_InitStateEngine()`

- `IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookPage : StateEnginePage
{
	private TopMenuDynamicPrefabInstHolder _topMenuHolder; // 0xe8
	private GameObject _transObject; // 0xf0
	private HandBookJumpParam <jumpParam>k__BackingField; // 0xf8
	private static DelegateBridge __Hotfix0_get_jumpParam; // 0x0
	private static DelegateBridge __Hotfix0_set_jumpParam; // 0x8
	private static DelegateBridge __Hotfix0_get_avgPage; // 0x10
	private static DelegateBridge __Hotfix0_SetTopMenuActive; // 0x18
	private static DelegateBridge __Hotfix0_SetTranObjectActive; // 0x20
	private static DelegateBridge __Hotfix0__ReturnPage; // 0x28
	private static DelegateBridge __Hotfix0_OnCreate; // 0x30
	private static DelegateBridge __Hotfix0_HideTopMenu; // 0x38
	private static DelegateBridge __Hotfix0_ShowTopMenu; // 0x40
	private static DelegateBridge __Hotfix0_InitStateEngine; // 0x48
	private static DelegateBridge __Hotfix0_EffectsOnHide; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public HandBookJumpParam jumpParam { get; set; }
	public override AVGPageKey avgPage { get; }

	// RVA: 0x2e9a0f8 VA: 0x75954b20f8
	public HandBookJumpParam get_jumpParam() { }
	// RVA: 0x2e9a160 VA: 0x75954b2160
	public Void set_jumpParam(HandBookJumpParam value) { }
	// RVA: 0x2e9a1e4 VA: 0x75954b21e4
	public override AVGPageKey get_avgPage() { }
	// RVA: 0x2e9a24c VA: 0x75954b224c
	public Void SetTopMenuActive(Boolean activeFlag) { }
	// RVA: 0x2e9a2e0 VA: 0x75954b22e0
	public Void SetTranObjectActive(Boolean activeFlag) { }
	// RVA: 0x2e9a364 VA: 0x75954b2364
	private Void _ReturnPage() { }
	// RVA: 0x2e9a42c VA: 0x75954b242c
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x2e9a584 VA: 0x75954b2584
	public static Void HideTopMenu() { }
	// RVA: 0x2e9a674 VA: 0x75954b2674
	public static Void ShowTopMenu() { }
	// RVA: 0x2e9a764 VA: 0x75954b2764
	protected override IEnumerator InitStateEngine() { }
	// RVA: 0x2e9a838 VA: 0x75954b2838
	protected override IEnumerator EffectsOnHide(Boolean isIntoStack) { }
	// RVA: 0x2e9a928 VA: 0x75954b2928
	public Void .ctor() { }
	// RVA: 0x2e9a998 VA: 0x75954b2998
	private Void <OnCreate>b__11_0(GameObject inst) { }
	// RVA: 0x2e9aa50 VA: 0x75954b2a50
	private Void <OnCreate>b__11_1() { }
	// RVA: 0x2e9aa54 VA: 0x75954b2a54
	private IEnumerator <>n__0() { }
	// RVA: 0x2e9aa5c VA: 0x75954b2a5c
	private AVGPageKey <>xLuaBaseProxy_get_avgPage() { }
	// RVA: 0x2e9aa64 VA: 0x75954b2a64
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x2e9aa6c VA: 0x75954b2a6c
	private IEnumerator <>xLuaBaseProxy_InitStateEngine() { }
	// RVA: 0x2e9aa74 VA: 0x75954b2a74
	private IEnumerator <>xLuaBaseProxy_EffectsOnHide(Boolean P0) { }
}
```