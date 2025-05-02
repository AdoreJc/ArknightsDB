# CarvingHomePage

**Namespace:** `Torappu.UI.Carving`


## Fields

- `RectTransform _dialogContainer`

- `String m_actId`

- `UICompDialogMgr m_dialogMgr`


## Properties

- `String activityId`

- `UICompDialogMgr dialogMgr`


## Methods

- `String get_activityId()`

- `UICompDialogMgr get_dialogMgr()`

- `Void _TriggerBGMSignal()`

- `Void _ClearBGM()`

- `IEnumerator <>n__0()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `Void <>xLuaBaseProxy_OnDestroy()`

- `IEnumerator <>xLuaBaseProxy_InitStateEngine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingHomePage : StateEnginePage, IHotfixable
{
	private RectTransform _dialogContainer; // 0xe8
	private String m_actId; // 0xf0
	private UICompDialogMgr m_dialogMgr; // 0xf8
	private static DelegateBridge __Hotfix0_get_activityId; // 0x0
	private static DelegateBridge __Hotfix0_get_dialogMgr; // 0x8
	private static DelegateBridge __Hotfix0_OnCreate; // 0x10
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x18
	private static DelegateBridge __Hotfix0_InitStateEngine; // 0x20
	private static DelegateBridge __Hotfix0__TriggerBGMSignal; // 0x28
	private static DelegateBridge __Hotfix0__ClearBGM; // 0x30
	private static DelegateBridge __Hotfix0_CreateCommonTopMenu; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public String activityId { get; }
	public UICompDialogMgr dialogMgr { get; }

	// RVA: 0x2d95c58 VA: 0x75953adc58
	public String get_activityId() { }
	// RVA: 0x2d95e1c VA: 0x75953ade1c
	public UICompDialogMgr get_dialogMgr() { }
	// RVA: 0x2d967cc VA: 0x75953ae7cc
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x2d969f8 VA: 0x75953ae9f8
	protected override Void OnDestroy() { }
	// RVA: 0x2d96b18 VA: 0x75953aeb18
	protected override IEnumerator InitStateEngine() { }
	// RVA: 0x2d968c4 VA: 0x75953ae8c4
	private Void _TriggerBGMSignal() { }
	// RVA: 0x2d96a6c VA: 0x75953aea6c
	private Void _ClearBGM() { }
	// RVA: 0x2d95ae0 VA: 0x75953adae0
	public static CommonTopMenu CreateCommonTopMenu(Transform container, Action onBackClick) { }
	// RVA: 0x2d96bec VA: 0x75953aebec
	public Void .ctor() { }
	// RVA: 0x2d96c5c VA: 0x75953aec5c
	private IEnumerator <>n__0() { }
	// RVA: 0x2d96c64 VA: 0x75953aec64
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x2d96c6c VA: 0x75953aec6c
	private Void <>xLuaBaseProxy_OnDestroy() { }
	// RVA: 0x2d96c74 VA: 0x75953aec74
	private IEnumerator <>xLuaBaseProxy_InitStateEngine() { }
}
```