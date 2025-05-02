# Act25sideResearchPage

**Namespace:** `Torappu.Activity.Act25side`


## Fields

- `Boolean m_isInited`

- `Grain m_grain`

- `String m_activityId`


## Methods

- `Void _InitIfNot()`

- `Void OnHarvestRequest()`

- `Void <OnHarvestRequest>b__7_0(Act25sideDailyHarvestResponse)`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `Void <>xLuaBaseProxy_OnPageRouted()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class Act25sideResearchPage : StateEnginePage, IHotfixable
{
	private Boolean m_isInited; // 0xe8
	private Grain m_grain; // 0xf0
	private String m_activityId; // 0xf8
	private static DelegateBridge __Hotfix0_OnCreate; // 0x0
	private static DelegateBridge __Hotfix0_OnPageRouted; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_OnHarvestRequest; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x326ca08 VA: 0x7595884a08
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x326cb08 VA: 0x7595884b08
	protected override Void OnPageRouted() { }
	// RVA: 0x326ca94 VA: 0x7595884a94
	private Void _InitIfNot() { }
	// RVA: 0x326cc64 VA: 0x7595884c64
	public Void OnHarvestRequest() { }
	// RVA: 0x326ce84 VA: 0x7595884e84
	public Void .ctor() { }
	// RVA: 0x326cef4 VA: 0x7595884ef4
	private Void <OnHarvestRequest>b__7_0(Act25sideDailyHarvestResponse response) { }
	// RVA: 0x326d074 VA: 0x7595885074
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x326d07c VA: 0x759588507c
	private Void <>xLuaBaseProxy_OnPageRouted() { }
}
```