# SandboxV2AdminCharSelectStateBean

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2SelectPluginLogic logic`

- `Boolean ensureFlag`

- `OpenOption <openOption>k__BackingField`

- `SandboxV2CharListProperty property`


## Properties

- `OpenOption openOption`


## Methods

- `Void OnCharSelect(Int32)`

- `OpenOption get_openOption()`

- `Void set_openOption(OpenOption)`

- `OutPut GenOutPut()`

- `Void SetOption(OpenOption)`

- `Void SetAttrSelect(Int32)`

- `Void RefreshWithPlayerData()`

- `Void _RefreshCurrentSelectPlayerData()`

- `Void _RefreshExpeditionDataIfNeed()`

- `Void _RefreshLogisticsDataIfNeed()`

- `Void SetSelectSkill(String)`

- `Void SetEquipId(String)`

- `Void SetShuffleProfPanelState(Boolean)`

- `Void SetShuffleStatePanelState(Boolean)`

- `Void SetShuffleState(Int32)`

- `Void SetShuffleProf(Int32)`

- `Void OnCharClear()`

- `Void OnSwitchPopViewFlag(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminCharSelectStateBean : IStateBean, IHotfixable
{
	public SandboxV2SelectPluginLogic logic; // 0x10
	public Boolean ensureFlag; // 0x18
	private OpenOption <openOption>k__BackingField; // 0x20
	public SandboxV2CharListProperty property; // 0x78
	private static DelegateBridge __Hotfix0_OnCharSelect; // 0x0
	private static DelegateBridge __Hotfix0_get_openOption; // 0x8
	private static DelegateBridge __Hotfix0_set_openOption; // 0x10
	private static DelegateBridge __Hotfix0_GenOutPut; // 0x18
	private static DelegateBridge __Hotfix0_SetOption; // 0x20
	private static DelegateBridge __Hotfix0_SetAttrSelect; // 0x28
	private static DelegateBridge __Hotfix0_RefreshWithPlayerData; // 0x30
	private static DelegateBridge __Hotfix0__RefreshCurrentSelectPlayerData; // 0x38
	private static DelegateBridge __Hotfix0__RefreshExpeditionDataIfNeed; // 0x40
	private static DelegateBridge __Hotfix0__RefreshLogisticsDataIfNeed; // 0x48
	private static DelegateBridge __Hotfix0_SetSelectSkill; // 0x50
	private static DelegateBridge __Hotfix0_SetEquipId; // 0x58
	private static DelegateBridge __Hotfix0_SetShuffleProfPanelState; // 0x60
	private static DelegateBridge __Hotfix0_SetShuffleStatePanelState; // 0x68
	private static DelegateBridge __Hotfix0_SetShuffleState; // 0x70
	private static DelegateBridge __Hotfix0_SetShuffleProf; // 0x78
	private static DelegateBridge __Hotfix0_OnCharClear; // 0x80
	private static DelegateBridge __Hotfix0_OnSwitchPopViewFlag; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	public OpenOption openOption { get; set; }

	// RVA: 0x24af800 VA: 0x7594ac7800
	public Void OnCharSelect(Int32 index) { }
	// RVA: 0x24aeb98 VA: 0x7594ac6b98
	public OpenOption get_openOption() { }
	// RVA: 0x24b2dd0 VA: 0x7594acadd0
	private Void set_openOption(OpenOption value) { }
	// RVA: 0x24b2e84 VA: 0x7594acae84
	public OutPut GenOutPut() { }
	// RVA: 0x24b32b4 VA: 0x7594acb2b4
	public Void SetOption(OpenOption option) { }
	// RVA: 0x24af738 VA: 0x7594ac7738
	public Void SetAttrSelect(Int32 attrEnum) { }
	// RVA: 0x24af150 VA: 0x7594ac7150
	public Void RefreshWithPlayerData() { }
	// RVA: 0x24b34fc VA: 0x7594acb4fc
	private Void _RefreshCurrentSelectPlayerData() { }
	// RVA: 0x24b35a8 VA: 0x7594acb5a8
	private Void _RefreshExpeditionDataIfNeed() { }
	// RVA: 0x24b3658 VA: 0x7594acb658
	private Void _RefreshLogisticsDataIfNeed() { }
	// RVA: 0x24af8fc VA: 0x7594ac78fc
	public Void SetSelectSkill(String skillIndex) { }
	// RVA: 0x24af9ec VA: 0x7594ac79ec
	public Void SetEquipId(String equipId) { }
	// RVA: 0x24afadc VA: 0x7594ac7adc
	public Void SetShuffleProfPanelState(Boolean state) { }
	// RVA: 0x24afbac VA: 0x7594ac7bac
	public Void SetShuffleStatePanelState(Boolean state) { }
	// RVA: 0x24afc7c VA: 0x7594ac7c7c
	public Void SetShuffleState(Int32 status) { }
	// RVA: 0x24afd54 VA: 0x7594ac7d54
	public Void SetShuffleProf(Int32 status) { }
	// RVA: 0x24b0040 VA: 0x7594ac8040
	public Void OnCharClear() { }
	// RVA: 0x24b064c VA: 0x7594ac864c
	public Void OnSwitchPopViewFlag(Boolean isShow) { }
	// RVA: 0x24b07c0 VA: 0x7594ac87c0
	public Void .ctor() { }
}
```