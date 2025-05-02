# ActivityCustomZoneMapPage

**Namespace:** `Torappu.UI.Stage`


## Fields

- `ActivityCustomZoneStateBean _stateBean`

- `TopMenuDynamicPrefabInstHolder _commonTopMenuHolder`

- `RectTransform _customTopMenuHolder`

- `Image _bgImage`

- `InputParam m_cachedParam`


## Properties

- `InputParam cachedParam`


## Methods

- `InputParam get_cachedParam()`

- `Void OnMessage(Int32, ValueBundle)`

- `Void _ShowRewardsGet(ShowRewardsGetInfo)`

- `IEnumerator _InitStateEngine()`

- `IEnumerator _RouteToCustomZoneMapState()`

- `IEnumerator _RouteToCustomZoneStagePreviewState()`

- `Void _OnInitTopMenu(GameObject)`

- `Void _LoadCustomTopMenu(String)`

- `Void ReturnPage()`

- `Void _SetBackgroundImg()`

- `IEnumerator <>n__0()`

- `Void <_OnInitTopMenu>b__19_0()`

- `Void <_LoadCustomTopMenu>b__20_0()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `IEnumerator <>xLuaBaseProxy_InitStateEngine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class ActivityCustomZoneMapPage : StateEnginePage, IValueMsgReceiver
{
	public const Int32 SHOW_REWARDS_GET; // 0x0
	public const Int32 PAGE_BACK; // 0x0
	private ActivityCustomZoneStateBean _stateBean; // 0xe8
	private TopMenuDynamicPrefabInstHolder _commonTopMenuHolder; // 0xf0
	private RectTransform _customTopMenuHolder; // 0xf8
	private Image _bgImage; // 0x100
	private InputParam m_cachedParam; // 0x108
	private static DelegateBridge __Hotfix0_get_cachedParam; // 0x0
	private static DelegateBridge __Hotfix0_OnCreate; // 0x8
	private static DelegateBridge __Hotfix0_InitStateEngine; // 0x10
	private static DelegateBridge __Hotfix0_OnMessage; // 0x18
	private static DelegateBridge __Hotfix0__ShowRewardsGet; // 0x20
	private static DelegateBridge __Hotfix0__InitStateEngine; // 0x28
	private static DelegateBridge __Hotfix0__RouteToCustomZoneMapState; // 0x30
	private static DelegateBridge __Hotfix0__RouteToCustomZoneStagePreviewState; // 0x38
	private static DelegateBridge __Hotfix0__OnInitTopMenu; // 0x40
	private static DelegateBridge __Hotfix0__LoadCustomTopMenu; // 0x48
	private static DelegateBridge __Hotfix0_ReturnPage; // 0x50
	private static DelegateBridge __Hotfix0__SetBackgroundImg; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public InputParam cachedParam { get; }

	// RVA: 0x2ef5278 VA: 0x759550d278
	public InputParam get_cachedParam() { }
	// RVA: 0x2ef52e0 VA: 0x759550d2e0
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x2ef57dc VA: 0x759550d7dc
	protected override IEnumerator InitStateEngine() { }
	// RVA: 0x2ef58b0 VA: 0x759550d8b0
	public Void OnMessage(Int32 key, ValueBundle msg) { }
	// RVA: 0x2ef59b4 VA: 0x759550d9b4
	private Void _ShowRewardsGet(ShowRewardsGetInfo info) { }
	// RVA: 0x2ef5c88 VA: 0x759550dc88
	private IEnumerator _InitStateEngine() { }
	// RVA: 0x2ef5d5c VA: 0x759550dd5c
	private IEnumerator _RouteToCustomZoneMapState() { }
	// RVA: 0x2ef5e30 VA: 0x759550de30
	private IEnumerator _RouteToCustomZoneStagePreviewState() { }
	// RVA: 0x2ef5f04 VA: 0x759550df04
	private Void _OnInitTopMenu(GameObject inst) { }
	// RVA: 0x2ef54b0 VA: 0x759550d4b0
	private Void _LoadCustomTopMenu(String topMenuPath) { }
	// RVA: 0x2ef5b60 VA: 0x759550db60
	public Void ReturnPage() { }
	// RVA: 0x2ef5644 VA: 0x759550d644
	private Void _SetBackgroundImg() { }
	// RVA: 0x2ef604c VA: 0x759550e04c
	public Void .ctor() { }
	// RVA: 0x2ef60bc VA: 0x759550e0bc
	private IEnumerator <>n__0() { }
	// RVA: 0x2ef60c4 VA: 0x759550e0c4
	private Void <_OnInitTopMenu>b__19_0() { }
	// RVA: 0x2ef60c8 VA: 0x759550e0c8
	private Void <_LoadCustomTopMenu>b__20_0() { }
	// RVA: 0x2ef60cc VA: 0x759550e0cc
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x2ef60d4 VA: 0x759550e0d4
	private IEnumerator <>xLuaBaseProxy_InitStateEngine() { }
}
```