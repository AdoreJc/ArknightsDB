# Act17sideActivityController

**Namespace:** `Torappu.Activity.Act17side`


## Methods

- `Void OpenRPPage(String, String)`

- `Act17sideData GetData()`

- `PlayerAct17SideActivity GetPlayerData()`

- `Act17sideButtonViewModel _GenButtonViewModel()`

- `Act17sideActivityZoneGroupViewModel _GenZoneViewModel()`

- `TemplateActivityLifeCycleViewModel _GenLifeCycle()`

- `TemplateActivityCoinViewModel _GenCoinStateViewModel()`

- `TemplateActivityFavorViewModel _GenFavorStateViewModel()`

- `Void OnZoneSelected(String)`

- `Int32 <_GenCoinStateViewModel>b__12_0()`

- `ActivityStageBridge <>xLuaBaseProxy_CreateBridge()`

- `Void <>xLuaBaseProxy_OnStageTimeout()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act17side
public class Act17sideActivityController : TemplateActivityController
{
	public const String BUTTON_STATE_VIEWMODEL; // 0x0
	public const String ZONE_VIEWMODEL; // 0x0
	private static DelegateBridge __Hotfix0_InitModelDict; // 0x0
	private static DelegateBridge __Hotfix0_OpenRPPage; // 0x8
	private static DelegateBridge __Hotfix0_CreateBridge; // 0x10
	private static DelegateBridge __Hotfix0_OnStageTimeout; // 0x18
	private static DelegateBridge __Hotfix0_GetData; // 0x20
	private static DelegateBridge __Hotfix0_GetPlayerData; // 0x28
	private static DelegateBridge __Hotfix0__GenButtonViewModel; // 0x30
	private static DelegateBridge __Hotfix0__GenZoneViewModel; // 0x38
	private static DelegateBridge __Hotfix0__GenLifeCycle; // 0x40
	private static DelegateBridge __Hotfix0__GenCoinStateViewModel; // 0x48
	private static DelegateBridge __Hotfix0__GenFavorStateViewModel; // 0x50
	private static DelegateBridge __Hotfix0_OnZoneSelected; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x3417c18 VA: 0x7595a2fc18
	public override Void InitModelDict(String actId) { }
	// RVA: 0x3418438 VA: 0x7595a30438
	public Void OpenRPPage(String zoneId, String stageId) { }
	// RVA: 0x3418568 VA: 0x7595a30568
	protected override ActivityStageBridge CreateBridge() { }
	// RVA: 0x3418608 VA: 0x7595a30608
	protected override Void OnStageTimeout() { }
	// RVA: 0x341870c VA: 0x7595a3070c
	public Act17sideData GetData() { }
	// RVA: 0x341885c VA: 0x7595a3085c
	public PlayerAct17SideActivity GetPlayerData() { }
	// RVA: 0x341804c VA: 0x7595a3004c
	private Act17sideButtonViewModel _GenButtonViewModel() { }
	// RVA: 0x3417d88 VA: 0x7595a2fd88
	private Act17sideActivityZoneGroupViewModel _GenZoneViewModel() { }
	// RVA: 0x34180e8 VA: 0x7595a300e8
	private TemplateActivityLifeCycleViewModel _GenLifeCycle() { }
	// RVA: 0x3418304 VA: 0x7595a30304
	private TemplateActivityCoinViewModel _GenCoinStateViewModel() { }
	// RVA: 0x34181fc VA: 0x7595a301fc
	private TemplateActivityFavorViewModel _GenFavorStateViewModel() { }
	// RVA: 0x341897c VA: 0x7595a3097c
	public Void OnZoneSelected(String zoneId) { }
	// RVA: 0x3418a9c VA: 0x7595a30a9c
	public Void .ctor() { }
	// RVA: 0x3418b0c VA: 0x7595a30b0c
	private Int32 <_GenCoinStateViewModel>b__12_0() { }
	// RVA: 0x3418b28 VA: 0x7595a30b28
	private ActivityStageBridge <>xLuaBaseProxy_CreateBridge() { }
	// RVA: 0x3418b30 VA: 0x7595a30b30
	private Void <>xLuaBaseProxy_OnStageTimeout() { }
}
```