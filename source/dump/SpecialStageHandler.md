# SpecialStageHandler

**Namespace:** ` `


## Fields

- `Boolean <hasHardToShow>k__BackingField`

- `Boolean <hasSixStarToShow>k__BackingField`


## Properties

- `Boolean hasHardToShow`

- `Boolean hasSixStarToShow`


## Methods

- `Boolean get_hasHardToShow()`

- `Void set_hasHardToShow(Boolean)`

- `Boolean get_hasSixStarToShow()`

- `Void set_hasSixStarToShow(Boolean)`

- `Boolean GetHasSpecialStageToShow(SpecialStageType)`

- `T GetSpecialStageInfo(SpecialStageType)`

- `Void RegisterSpecialStageInfo(SpecialStageType, StageData)`

- `Void UpdateHandler(StageViewModel)`

- `Void UpdatePlayerData(PlayerStage, StageViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class SpecialStageHandler : IHotfixable
{
	private EnumIntDictionary`2 m_specialStageInfoDict; // 0x10
	private Boolean <hasHardToShow>k__BackingField; // 0x18
	private Boolean <hasSixStarToShow>k__BackingField; // 0x19
	private static DelegateBridge __Hotfix0_get_hasHardToShow; // 0x0
	private static DelegateBridge __Hotfix0_set_hasHardToShow; // 0x8
	private static DelegateBridge __Hotfix0_get_hasSixStarToShow; // 0x10
	private static DelegateBridge __Hotfix0_set_hasSixStarToShow; // 0x18
	private static DelegateBridge __Hotfix0_GetHasSpecialStageToShow; // 0x20
	private static DelegateBridge __Hotfix0_GetSpecialStageInfo; // 0x28
	private static DelegateBridge __Hotfix0_RegisterSpecialStageInfo; // 0x30
	private static DelegateBridge __Hotfix0_UpdateHandler; // 0x38
	private static DelegateBridge __Hotfix0_UpdatePlayerData; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	private Boolean hasHardToShow { get; set; }
	private Boolean hasSixStarToShow { get; set; }

	// RVA: 0x2f7f54c VA: 0x759559754c
	private Boolean get_hasHardToShow() { }
	// RVA: 0x2f7f5b4 VA: 0x75955975b4
	private Void set_hasHardToShow(Boolean value) { }
	// RVA: 0x2f7f634 VA: 0x7595597634
	private Boolean get_hasSixStarToShow() { }
	// RVA: 0x2f7f69c VA: 0x759559769c
	private Void set_hasSixStarToShow(Boolean value) { }
	// RVA: 0x2f7e8d4 VA: 0x75955968d4
	public Boolean GetHasSpecialStageToShow(SpecialStageType specialStageType) { }
	// RVA: 0x VA: 0x0
	public T GetSpecialStageInfo(SpecialStageType specialStageType) { }
	// RVA: 0x2f7edd0 VA: 0x7595596dd0
	public Void RegisterSpecialStageInfo(SpecialStageType specialStageType, StageData stageData) { }
	// RVA: 0x2f7f03c VA: 0x759559703c
	public Void UpdateHandler(StageViewModel stageViewModel) { }
	// RVA: 0x2f7f2e8 VA: 0x75955972e8
	public Void UpdatePlayerData(PlayerStage playerStage, StageViewModel stageViewModel) { }
	// RVA: 0x2f7ed0c VA: 0x7595596d0c
	public Void .ctor() { }
}
```