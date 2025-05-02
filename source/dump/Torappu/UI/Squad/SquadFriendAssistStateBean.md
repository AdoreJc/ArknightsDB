# SquadFriendAssistStateBean

**Namespace:** `Torappu.UI.Squad`


## Fields

- `SquadFriendData assistCharModel`

- `Boolean isFriend`

- `SquadViewModel currentSquad`

- `ProfessionCategory professionCache`

- `Boolean isSquadImmutable`

- `String tipDesc`

- `Boolean isCharShowMultipleSlot`

- `SquadAssistCharDetailProperty charDetailProperty`

- `Boolean usePlayerSelection`

- `Boolean showSpecMaxIcon`

- `ExtraInput <extraInput>k__BackingField`

- `IPlugin <statePlugin>k__BackingField`


## Properties

- `EvolvePhaseAndLevel maxPhaseAndLv`

- `ExtraInput extraInput`

- `IPlugin statePlugin`

- `RenderOptions renderOption`


## Methods

- `EvolvePhaseAndLevel get_maxPhaseAndLv()`

- `Void set_maxPhaseAndLv(EvolvePhaseAndLevel)`

- `ExtraInput get_extraInput()`

- `Void set_extraInput(ExtraInput)`

- `IPlugin get_statePlugin()`

- `Void set_statePlugin(IPlugin)`

- `RenderOptions get_renderOption()`

- `Void SetExtraInput(ExtraInput)`

- `Void ClearStatePlugin()`

- `Boolean CheckIfContainedInCurSquad(String)`

- `Boolean TryGetMutuallyExclusiveCharInfoInCurSquad(String, out)`

- `SquadFriendData ConvertAssistDataToFriendData(SquadAssistData)`

- `Void SetFriendDataCache(ProfessionCategory, GetFriendAssistCharListResponse)`

- `GetFriendAssistCharListResponse GetFriendDataCache(ProfessionCategory)`

- `Void SetFriendReqDisableById(String)`

- `Options GetAssistOption(String)`

- `Void CleanCache()`

- `IPlugin _GenerateStatePlugin(ExtraInput)`

- `Void _UpdateAssistOption(GetFriendAssistCharListResponse)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Squad
public class SquadFriendAssistStateBean : IStateBean, IHotfixable
{
	public static List`1 PROFESSION_LIST; // 0x0
	public SquadFriendData assistCharModel; // 0x10
	public Boolean isFriend; // 0x18
	public SquadViewModel currentSquad; // 0x20
	public ListDict`2 assistDataCacheDict; // 0x28
	public ProfessionCategory professionCache; // 0x30
	public ListDict`2 assistOptionDict; // 0x38
	public Boolean isSquadImmutable; // 0x40
	public String tipDesc; // 0x48
	public Boolean isCharShowMultipleSlot; // 0x50
	public SquadAssistCharDetailProperty charDetailProperty; // 0x58
	public Dictionary`2 cachedNameCardDict; // 0x60
	public Boolean usePlayerSelection; // 0x68
	public Boolean showSpecMaxIcon; // 0x69
	private Nullable`1 m_overridePhaseAndLv; // 0x6c
	private ExtraInput <extraInput>k__BackingField; // 0x78
	private IPlugin <statePlugin>k__BackingField; // 0x88
	private static DelegateBridge __Hotfix0_get_maxPhaseAndLv; // 0x8
	private static DelegateBridge __Hotfix0_set_maxPhaseAndLv; // 0x10
	private static DelegateBridge __Hotfix0_get_extraInput; // 0x18
	private static DelegateBridge __Hotfix0_set_extraInput; // 0x20
	private static DelegateBridge __Hotfix0_get_statePlugin; // 0x28
	private static DelegateBridge __Hotfix0_set_statePlugin; // 0x30
	private static DelegateBridge __Hotfix0_get_renderOption; // 0x38
	private static DelegateBridge __Hotfix0_SetExtraInput; // 0x40
	private static DelegateBridge __Hotfix0_ClearStatePlugin; // 0x48
	private static DelegateBridge __Hotfix0_CheckIfContainedInCurSquad; // 0x50
	private static DelegateBridge __Hotfix0_TryGetMutuallyExclusiveCharInfoInCurSquad; // 0x58
	private static DelegateBridge __Hotfix0_ConvertAssistDataToFriendData; // 0x60
	private static DelegateBridge __Hotfix0_SetFriendDataCache; // 0x68
	private static DelegateBridge __Hotfix0_GetFriendDataCache; // 0x70
	private static DelegateBridge __Hotfix0_SetFriendReqDisableById; // 0x78
	private static DelegateBridge __Hotfix0_GetAssistOption; // 0x80
	private static DelegateBridge __Hotfix0_CleanCache; // 0x88
	private static DelegateBridge __Hotfix0__GenerateStatePlugin; // 0x90
	private static DelegateBridge __Hotfix0__UpdateAssistOption; // 0x98
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa0

	public EvolvePhaseAndLevel maxPhaseAndLv { get; set; }
	public ExtraInput extraInput { get; set; }
	public IPlugin statePlugin { get; set; }
	public RenderOptions renderOption { get; }

	// RVA: 0x23928e4 VA: 0x75949aa8e4
	public EvolvePhaseAndLevel get_maxPhaseAndLv() { }
	// RVA: 0x23929ac VA: 0x75949aa9ac
	public Void set_maxPhaseAndLv(EvolvePhaseAndLevel value) { }
	// RVA: 0x2392a7c VA: 0x75949aaa7c
	public ExtraInput get_extraInput() { }
	// RVA: 0x2392af0 VA: 0x75949aaaf0
	private Void set_extraInput(ExtraInput value) { }
	// RVA: 0x2392b90 VA: 0x75949aab90
	public IPlugin get_statePlugin() { }
	// RVA: 0x2392c08 VA: 0x75949aac08
	private Void set_statePlugin(IPlugin value) { }
	// RVA: 0x2392c9c VA: 0x75949aac9c
	public RenderOptions get_renderOption() { }
	// RVA: 0x2388114 VA: 0x75949a0114
	public Void SetExtraInput(ExtraInput input) { }
	// RVA: 0x2392e80 VA: 0x75949aae80
	public Void ClearStatePlugin() { }
	// RVA: 0x2389214 VA: 0x75949a1214
	public Boolean CheckIfContainedInCurSquad(String charId) { }
	// RVA: 0x2389384 VA: 0x75949a1384
	public Boolean TryGetMutuallyExclusiveCharInfoInCurSquad(String charId, out String exclusiveInfo) { }
	// RVA: 0x2392efc VA: 0x75949aaefc
	public SquadFriendData ConvertAssistDataToFriendData(SquadAssistData assistData) { }
	// RVA: 0x23903a4 VA: 0x75949a83a4
	public Void SetFriendDataCache(ProfessionCategory profession, GetFriendAssistCharListResponse response) { }
	// RVA: 0x23931a8 VA: 0x75949ab1a8
	public GetFriendAssistCharListResponse GetFriendDataCache(ProfessionCategory profession) { }
	// RVA: 0x2393268 VA: 0x75949ab268
	public Void SetFriendReqDisableById(String id) { }
	// RVA: 0x239331c VA: 0x75949ab31c
	public Options GetAssistOption(String id) { }
	// RVA: 0x239340c VA: 0x75949ab40c
	public Void CleanCache() { }
	// RVA: 0x2392d1c VA: 0x75949aad1c
	private IPlugin _GenerateStatePlugin(ExtraInput input) { }
	// RVA: 0x2393054 VA: 0x75949ab054
	private Void _UpdateAssistOption(GetFriendAssistCharListResponse response) { }
	// RVA: 0x23934c0 VA: 0x75949ab4c0
	public Void .ctor() { }
	// RVA: 0x2393684 VA: 0x75949ab684
	private static Void .cctor() { }
}
```