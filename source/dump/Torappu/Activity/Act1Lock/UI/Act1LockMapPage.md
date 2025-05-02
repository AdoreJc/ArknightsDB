# Act1LockMapPage

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `Act1LockAVGAdapter _avgAdapter`

- `Act1LockZoneMapStateBean m_mapStateBean`

- `DataBundle m_dataBundle4InitStateEngine`


## Methods

- `IEnumerator _LoadFromCache(String)`

- `Void _TriggerInterlockAVG()`

- `Void _OnAvgFinished(Story)`

- `Void AVGOnly_BackToMapView()`

- `IEnumerator <>n__0()`

- `Void <>xLuaBaseProxy_OnStart()`

- `Void <>xLuaBaseProxy_OnCreate(DataBundle)`

- `IEnumerator <>xLuaBaseProxy_InitStateEngine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockMapPage : StateEnginePage, IHotfixable
{
	private Act1LockAVGAdapter _avgAdapter; // 0xe8
	private Act1LockZoneMapStateBean m_mapStateBean; // 0xf0
	private DataBundle m_dataBundle4InitStateEngine; // 0xf8
	private static DelegateBridge __Hotfix0_OnStart; // 0x0
	private static DelegateBridge __Hotfix0_OnCreate; // 0x8
	private static DelegateBridge __Hotfix0_InitStateEngine; // 0x10
	private static DelegateBridge __Hotfix0__LoadFromCache; // 0x18
	private static DelegateBridge __Hotfix0__TriggerInterlockAVG; // 0x20
	private static DelegateBridge __Hotfix0__OnAvgFinished; // 0x28
	private static DelegateBridge __Hotfix0_AVGOnly_BackToMapView; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x339a6d4 VA: 0x75959b26d4
	protected override Void OnStart() { }
	// RVA: 0x339a79c VA: 0x75959b279c
	protected override Void OnCreate(DataBundle savedInst) { }
	// RVA: 0x339a830 VA: 0x75959b2830
	protected override IEnumerator InitStateEngine() { }
	// RVA: 0x339a904 VA: 0x75959b2904
	private IEnumerator _LoadFromCache(String stageId) { }
	// RVA: 0x339a9fc VA: 0x75959b29fc
	private Void _TriggerInterlockAVG() { }
	// RVA: 0x339aba0 VA: 0x75959b2ba0
	private Void _OnAvgFinished(Story story) { }
	// RVA: 0x339a36c VA: 0x75959b236c
	public Void AVGOnly_BackToMapView() { }
	// RVA: 0x339acb4 VA: 0x75959b2cb4
	public Void .ctor() { }
	// RVA: 0x339ad24 VA: 0x75959b2d24
	private IEnumerator <>n__0() { }
	// RVA: 0x339ad2c VA: 0x75959b2d2c
	private Void <>xLuaBaseProxy_OnStart() { }
	// RVA: 0x339ad34 VA: 0x75959b2d34
	private Void <>xLuaBaseProxy_OnCreate(DataBundle P0) { }
	// RVA: 0x339ad3c VA: 0x75959b2d3c
	private IEnumerator <>xLuaBaseProxy_InitStateEngine() { }
}
```