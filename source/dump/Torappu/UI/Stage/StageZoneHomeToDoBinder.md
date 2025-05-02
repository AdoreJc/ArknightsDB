# StageZoneHomeToDoBinder

**Namespace:** `Torappu.UI.Stage`


## Fields

- `StageZoneHomeToDoLayout _layout`


## Methods

- `Void set_onToDoClicked(Action`1)`

- `Void _OnToDoClicked(ZoneHomeToDoItemModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneHomeToDoBinder : DataBinder`1
{
	private StageZoneHomeToDoLayout _layout; // 0x20
	private Action`1 <onToDoClicked>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_onToDoClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onToDoClicked; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__OnToDoClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 onToDoClicked { get; set; }

	// RVA: 0x2f044d0 VA: 0x759551c4d0
	private Action`1 get_onToDoClicked() { }
	// RVA: 0x2f04538 VA: 0x759551c538
	public Void set_onToDoClicked(Action`1 value) { }
	// RVA: 0x2f045bc VA: 0x759551c5bc
	public override Void OnValueChanged(ZoneHomeToDoGroupProp property) { }
	// RVA: 0x2f04778 VA: 0x759551c778
	private Void _OnToDoClicked(ZoneHomeToDoItemModel todoModel) { }
	// RVA: 0x2f04830 VA: 0x759551c830
	public Void .ctor() { }
}
```