# ActMainSSActivityController

**Namespace:** `Torappu.Activity.ActMainSS`


## Methods

- `ActMainSSData _GetData()`

- `PlayerActMainSSActivity _GetPlayerData()`

- `ActMainSSEntryZoneViewModel _GenZoneViewModel()`

- `TemplateActivityMissionViewModel _GenTemplateMissionViewModel()`

- `TemplateActivityCoinViewModel _GenCoinViewModel()`

- `TemplateActivityFavorViewModel _GenFavorViewModel()`

- `TemplateActivityLifeCycleViewModel _GenLifeCycle()`

- `TemplateActivityMedalViewModel _GenMedalViewModel()`

- `Int32 _GetCoinCount()`

- `Void <>xLuaBaseProxy_OnStageTimeout()`

- `TemplateMissionInputParam <>xLuaBaseProxy_CreateTemplateMissionInputParam()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMainSS
public class ActMainSSActivityController : TemplateActivityController, IHotfixable
{
	public const String MAIN_SS_ZONE_PARAM; // 0x0
	private static DelegateBridge __Hotfix0_InitModelDict; // 0x0
	private static DelegateBridge __Hotfix0_OnStageTimeout; // 0x8
	private static DelegateBridge __Hotfix0__GetData; // 0x10
	private static DelegateBridge __Hotfix0__GetPlayerData; // 0x18
	private static DelegateBridge __Hotfix0__GenZoneViewModel; // 0x20
	private static DelegateBridge __Hotfix0__GenTemplateMissionViewModel; // 0x28
	private static DelegateBridge __Hotfix0_CreateTemplateMissionInputParam; // 0x30
	private static DelegateBridge __Hotfix0__GenCoinViewModel; // 0x38
	private static DelegateBridge __Hotfix0__GenFavorViewModel; // 0x40
	private static DelegateBridge __Hotfix0__GenLifeCycle; // 0x48
	private static DelegateBridge __Hotfix0__GenMedalViewModel; // 0x50
	private static DelegateBridge __Hotfix0__GetCoinCount; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x318b5ac VA: 0x75957a35ac
	public override Void InitModelDict(String actId) { }
	// RVA: 0x318bde0 VA: 0x75957a3de0
	protected override Void OnStageTimeout() { }
	// RVA: 0x318bfec VA: 0x75957a3fec
	private ActMainSSData _GetData() { }
	// RVA: 0x318c158 VA: 0x75957a4158
	private PlayerActMainSSActivity _GetPlayerData() { }
	// RVA: 0x318b74c VA: 0x75957a374c
	private ActMainSSEntryZoneViewModel _GenZoneViewModel() { }
	// RVA: 0x318b8cc VA: 0x75957a38cc
	private TemplateActivityMissionViewModel _GenTemplateMissionViewModel() { }
	// RVA: 0x318c624 VA: 0x75957a4624
	public override TemplateMissionInputParam CreateTemplateMissionInputParam() { }
	// RVA: 0x318b984 VA: 0x75957a3984
	private TemplateActivityCoinViewModel _GenCoinViewModel() { }
	// RVA: 0x318bab0 VA: 0x75957a3ab0
	private TemplateActivityFavorViewModel _GenFavorViewModel() { }
	// RVA: 0x318bbb8 VA: 0x75957a3bb8
	private TemplateActivityLifeCycleViewModel _GenLifeCycle() { }
	// RVA: 0x318bccc VA: 0x75957a3ccc
	private TemplateActivityMedalViewModel _GenMedalViewModel() { }
	// RVA: 0x318c850 VA: 0x75957a4850
	private Int32 _GetCoinCount() { }
	// RVA: 0x318c8c8 VA: 0x75957a48c8
	public Void .ctor() { }
	// RVA: 0x318c938 VA: 0x75957a4938
	private Void <>xLuaBaseProxy_OnStageTimeout() { }
	// RVA: 0x318c940 VA: 0x75957a4940
	private TemplateMissionInputParam <>xLuaBaseProxy_CreateTemplateMissionInputParam() { }
}
```