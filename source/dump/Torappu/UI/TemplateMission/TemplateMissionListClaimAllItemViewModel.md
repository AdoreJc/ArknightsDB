# TemplateMissionListClaimAllItemViewModel

**Namespace:** `Torappu.UI.TemplateMission`


## Fields

- `String <claimAllTips>k__BackingField`

- `String <btnColor>k__BackingField`

- `Boolean <checkIfCanClaim>k__BackingField`


## Properties

- `String claimAllTips`

- `String btnColor`

- `Boolean checkIfCanClaim`


## Methods

- `TemplateMissionListItemViewType GetItemViewType()`

- `String get_claimAllTips()`

- `Void set_claimAllTips(String)`

- `String get_btnColor()`

- `Void set_btnColor(String)`

- `Boolean get_checkIfCanClaim()`

- `Void set_checkIfCanClaim(Boolean)`

- `Void RefreshCanClaimState(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateMission
public class TemplateMissionListClaimAllItemViewModel : ITemplateMissionListItemViewModel, IHotfixable
{
	private String <claimAllTips>k__BackingField; // 0x10
	private String <btnColor>k__BackingField; // 0x18
	private Boolean <checkIfCanClaim>k__BackingField; // 0x20
	private static DelegateBridge __Hotfix0_GetItemViewType; // 0x0
	private static DelegateBridge __Hotfix0_get_claimAllTips; // 0x8
	private static DelegateBridge __Hotfix0_set_claimAllTips; // 0x10
	private static DelegateBridge __Hotfix0_get_btnColor; // 0x18
	private static DelegateBridge __Hotfix0_set_btnColor; // 0x20
	private static DelegateBridge __Hotfix0_get_checkIfCanClaim; // 0x28
	private static DelegateBridge __Hotfix0_set_checkIfCanClaim; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38
	private static DelegateBridge __Hotfix0_RefreshCanClaimState; // 0x40

	public String claimAllTips { get; set; }
	public String btnColor { get; set; }
	public Boolean checkIfCanClaim { get; set; }

	// RVA: 0x236e6f0 VA: 0x75949866f0
	public TemplateMissionListItemViewType GetItemViewType() { }
	// RVA: 0x236e758 VA: 0x7594986758
	public String get_claimAllTips() { }
	// RVA: 0x236e7c0 VA: 0x75949867c0
	private Void set_claimAllTips(String value) { }
	// RVA: 0x236e844 VA: 0x7594986844
	public String get_btnColor() { }
	// RVA: 0x236e8ac VA: 0x75949868ac
	private Void set_btnColor(String value) { }
	// RVA: 0x236e930 VA: 0x7594986930
	public Boolean get_checkIfCanClaim() { }
	// RVA: 0x236e998 VA: 0x7594986998
	private Void set_checkIfCanClaim(Boolean value) { }
	// RVA: 0x236ea18 VA: 0x7594986a18
	public Void .ctor(String tips, String btnCol, Boolean canClaim) { }
	// RVA: 0x236eae0 VA: 0x7594986ae0
	public Void RefreshCanClaimState(Boolean canClaim) { }
}
```