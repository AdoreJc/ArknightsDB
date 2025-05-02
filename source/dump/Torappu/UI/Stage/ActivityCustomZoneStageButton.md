# ActivityCustomZoneStageButton

**Namespace:** `Torappu.UI.Stage`


## Fields

- `String _stageId`


## Properties

- `String stageId`


## Methods

- `String get_stageId()`

- `Void set_stageId(String)`

- `Void set_onStageBtnClicked(Action`1)`

- `Void Render(ActivityCustomZoneMapViewModel, StageViewModel, Boolean, Boolean)`

- `Void OnStageBtnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class ActivityCustomZoneStageButton : MonoBehaviour, IActivityCustomZoneStageButton, IHotfixable
{
	private String _stageId; // 0x18
	private ActivityCustomZoneBaseStageButtonPlugin[] _plugins; // 0x20
	private Action`1 <onStageBtnClicked>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_stageId; // 0x0
	private static DelegateBridge __Hotfix0_set_stageId; // 0x8
	private static DelegateBridge __Hotfix0_get_onStageBtnClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onStageBtnClicked; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0_OnStageBtnClicked; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public String stageId { get; set; }
	private Action`1 onStageBtnClicked { get; set; }

	// RVA: 0x2f804fc VA: 0x75955984fc
	public String get_stageId() { }
	// RVA: 0x2f810ac VA: 0x75955990ac
	public Void set_stageId(String value) { }
	// RVA: 0x2f81130 VA: 0x7595599130
	private Action`1 get_onStageBtnClicked() { }
	// RVA: 0x2f80f1c VA: 0x7595598f1c
	public Void set_onStageBtnClicked(Action`1 value) { }
	// RVA: 0x2f80564 VA: 0x7595598564
	public Void Render(ActivityCustomZoneMapViewModel zoneModel, StageViewModel stageViewModel, Boolean isSelected, Boolean isFastMode) { }
	// RVA: 0x2f81198 VA: 0x7595599198
	public Void OnStageBtnClicked() { }
	// RVA: 0x2f81240 VA: 0x7595599240
	public Void .ctor() { }
}
```