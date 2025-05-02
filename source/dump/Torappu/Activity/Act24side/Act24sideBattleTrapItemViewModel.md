# Act24sideBattleTrapItemViewModel

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `UnlockState <unlockState>k__BackingField`

- `Boolean <isTempSelect>k__BackingField`

- `ToolState <trapStatus>k__BackingField`

- `ToolData <toolData>k__BackingField`

- `String <actId>k__BackingField`

- `String <toolId>k__BackingField`


## Properties

- `UnlockState unlockState`

- `Boolean isTempSelect`

- `ToolState trapStatus`

- `ToolData toolData`

- `String actId`

- `String toolId`


## Methods

- `UnlockState get_unlockState()`

- `Void set_unlockState(UnlockState)`

- `Boolean get_isTempSelect()`

- `Void set_isTempSelect(Boolean)`

- `ToolState get_trapStatus()`

- `Void set_trapStatus(ToolState)`

- `ToolData get_toolData()`

- `Void set_toolData(ToolData)`

- `String get_actId()`

- `Void set_actId(String)`

- `String get_toolId()`

- `Void set_toolId(String)`

- `Void LoadData(String, ToolData)`

- `Void UpdateData(ToolState)`

- `Void UpdateUnlockState()`

- `Void UpdateTempSelectState(Boolean)`

- `Void TryConsumeNewUnlockTrack()`

- `UnlockState _GetToolUnlockStateByToolState(ToolState)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideBattleTrapItemViewModel : IHotfixable
{
	private UnlockState <unlockState>k__BackingField; // 0x10
	private Boolean <isTempSelect>k__BackingField; // 0x14
	private ToolState <trapStatus>k__BackingField; // 0x18
	private ToolData <toolData>k__BackingField; // 0x20
	private String <actId>k__BackingField; // 0x28
	private String <toolId>k__BackingField; // 0x30
	private static DelegateBridge __Hotfix0_get_unlockState; // 0x0
	private static DelegateBridge __Hotfix0_set_unlockState; // 0x8
	private static DelegateBridge __Hotfix0_get_isTempSelect; // 0x10
	private static DelegateBridge __Hotfix0_set_isTempSelect; // 0x18
	private static DelegateBridge __Hotfix0_get_trapStatus; // 0x20
	private static DelegateBridge __Hotfix0_set_trapStatus; // 0x28
	private static DelegateBridge __Hotfix0_get_toolData; // 0x30
	private static DelegateBridge __Hotfix0_set_toolData; // 0x38
	private static DelegateBridge __Hotfix0_get_actId; // 0x40
	private static DelegateBridge __Hotfix0_set_actId; // 0x48
	private static DelegateBridge __Hotfix0_get_toolId; // 0x50
	private static DelegateBridge __Hotfix0_set_toolId; // 0x58
	private static DelegateBridge __Hotfix0_LoadData; // 0x60
	private static DelegateBridge __Hotfix0_UpdateData; // 0x68
	private static DelegateBridge __Hotfix0_UpdateUnlockState; // 0x70
	private static DelegateBridge __Hotfix0_UpdateTempSelectState; // 0x78
	private static DelegateBridge __Hotfix0_TryConsumeNewUnlockTrack; // 0x80
	private static DelegateBridge __Hotfix0__GetToolUnlockStateByToolState; // 0x88
	private static DelegateBridge _c__Hotfix0_ctor; // 0x90

	public UnlockState unlockState { get; set; }
	public Boolean isTempSelect { get; set; }
	public ToolState trapStatus { get; set; }
	public ToolData toolData { get; set; }
	public String actId { get; set; }
	public String toolId { get; set; }

	// RVA: 0x3293a28 VA: 0x75958aba28
	public UnlockState get_unlockState() { }
	// RVA: 0x3297948 VA: 0x75958af948
	private Void set_unlockState(UnlockState value) { }
	// RVA: 0x3293b8c VA: 0x75958abb8c
	public Boolean get_isTempSelect() { }
	// RVA: 0x32979c4 VA: 0x75958af9c4
	private Void set_isTempSelect(Boolean value) { }
	// RVA: 0x3297a44 VA: 0x75958afa44
	public ToolState get_trapStatus() { }
	// RVA: 0x3297aac VA: 0x75958afaac
	private Void set_trapStatus(ToolState value) { }
	// RVA: 0x32938f0 VA: 0x75958ab8f0
	public ToolData get_toolData() { }
	// RVA: 0x3297b28 VA: 0x75958afb28
	private Void set_toolData(ToolData value) { }
	// RVA: 0x3293958 VA: 0x75958ab958
	public String get_actId() { }
	// RVA: 0x3297bac VA: 0x75958afbac
	private Void set_actId(String value) { }
	// RVA: 0x32939c0 VA: 0x75958ab9c0
	public String get_toolId() { }
	// RVA: 0x3297c30 VA: 0x75958afc30
	private Void set_toolId(String value) { }
	// RVA: 0x3297cb4 VA: 0x75958afcb4
	public Void LoadData(String activityId, ToolData tool) { }
	// RVA: 0x3297d78 VA: 0x75958afd78
	public Void UpdateData(ToolState battleTrapStatus) { }
	// RVA: 0x3296db0 VA: 0x75958aedb0
	public Void UpdateUnlockState() { }
	// RVA: 0x3296bd0 VA: 0x75958aebd0
	public Void UpdateTempSelectState(Boolean isSelect) { }
	// RVA: 0x3296b34 VA: 0x75958aeb34
	public Void TryConsumeNewUnlockTrack() { }
	// RVA: 0x3297e10 VA: 0x75958afe10
	private UnlockState _GetToolUnlockStateByToolState(ToolState battleTrapStatus) { }
	// RVA: 0x3297ed0 VA: 0x75958afed0
	public Void .ctor() { }
}
```