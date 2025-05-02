# GroceryPage

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `String m_actId`


## Properties

- `String activityId`


## Methods

- `String get_activityId()`

- `IEnumerator <>n__0()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `IEnumerator <>xLuaBaseProxy_InitStateEngine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GroceryPage : StateEnginePage, IHotfixable
{
	private String m_actId; // 0xe8
	private static DelegateBridge __Hotfix0_get_activityId; // 0x0
	private static DelegateBridge __Hotfix0_OnCreate; // 0x8
	private static DelegateBridge __Hotfix0_InitStateEngine; // 0x10
	private static DelegateBridge __Hotfix0_CreateCommonTopMenu; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public String activityId { get; }

	// RVA: 0x288a454 VA: 0x7594ea2454
	public String get_activityId() { }
	// RVA: 0x289839c VA: 0x7594eb039c
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x2898464 VA: 0x7594eb0464
	protected override IEnumerator InitStateEngine() { }
	// RVA: 0x2898538 VA: 0x7594eb0538
	public static CommonTopMenu CreateCommonTopMenu(Transform container, Action onBackClick) { }
	// RVA: 0x28986b0 VA: 0x7594eb06b0
	public Void .ctor() { }
	// RVA: 0x2898720 VA: 0x7594eb0720
	private IEnumerator <>n__0() { }
	// RVA: 0x2898728 VA: 0x7594eb0728
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x2898730 VA: 0x7594eb0730
	private IEnumerator <>xLuaBaseProxy_InitStateEngine() { }
}
```