# TuningPage

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `String m_actId`


## Properties

- `String actId`


## Methods

- `String get_actId()`

- `IEnumerator <>n__0()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `IEnumerator <>xLuaBaseProxy_InitStateEngine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningPage : StateEnginePage, IHotfixable
{
	private String m_actId; // 0xe8
	private static DelegateBridge __Hotfix0_get_actId; // 0x0
	private static DelegateBridge __Hotfix0_OnCreate; // 0x8
	private static DelegateBridge __Hotfix0_InitStateEngine; // 0x10
	private static DelegateBridge __Hotfix0_CreateCommonTopMenu; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public String actId { get; }

	// RVA: 0x232ca2c VA: 0x7594944a2c
	public String get_actId() { }
	// RVA: 0x232ec74 VA: 0x7594946c74
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x232ed3c VA: 0x7594946d3c
	protected override IEnumerator InitStateEngine() { }
	// RVA: 0x232ee10 VA: 0x7594946e10
	public static CommonTopMenu CreateCommonTopMenu(Transform container, Action onBackClick) { }
	// RVA: 0x232ef88 VA: 0x7594946f88
	public Void .ctor() { }
	// RVA: 0x232eff8 VA: 0x7594946ff8
	private IEnumerator <>n__0() { }
	// RVA: 0x232f000 VA: 0x7594947000
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x232f008 VA: 0x7594947008
	private IEnumerator <>xLuaBaseProxy_InitStateEngine() { }
}
```