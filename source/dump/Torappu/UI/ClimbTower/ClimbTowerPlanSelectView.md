# ClimbTowerPlanSelectView

**Namespace:** `Torappu.UI.ClimbTower`


## Methods

- `Void set_onPlanClick(Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerPlanSelectView : DataBinder`1
{
	private ClimbTowerPlanItemView[] planItemViewList; // 0x20
	private Action`1 <onPlanClick>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_onPlanClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onPlanClick; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	private Action`1 onPlanClick { get; set; }

	// RVA: 0x2c8e02c VA: 0x75952a602c
	private Action`1 get_onPlanClick() { }
	// RVA: 0x2c8d90c VA: 0x75952a590c
	public Void set_onPlanClick(Action`1 value) { }
	// RVA: 0x2c8e094 VA: 0x75952a6094
	public override Void OnValueChanged(BoolProperty property) { }
	// RVA: 0x2c8e20c VA: 0x75952a620c
	public Void .ctor() { }
}
```