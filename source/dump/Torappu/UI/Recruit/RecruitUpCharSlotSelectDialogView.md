# RecruitUpCharSlotSelectDialogView

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `Button _btnConfirm`


## Methods

- `Void set_onCardClick(Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitUpCharSlotSelectDialogView : DataBinder`1
{
	private List`1 _selectCards; // 0x20
	private Button _btnConfirm; // 0x28
	private Action`1 <onCardClick>k__BackingField; // 0x30
	private static DelegateBridge __Hotfix0_set_onCardClick; // 0x0
	private static DelegateBridge __Hotfix0_get_onCardClick; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	private Action`1 onCardClick { get; set; }

	// RVA: 0x26ff360 VA: 0x7594d17360
	public Void set_onCardClick(Action`1 value) { }
	// RVA: 0x2700980 VA: 0x7594d18980
	private Action`1 get_onCardClick() { }
	// RVA: 0x27009e8 VA: 0x7594d189e8
	public override Void OnValueChanged(RecruitUpCharSlotSelectViewProperty property) { }
	// RVA: 0x2700c30 VA: 0x7594d18c30
	public Void .ctor() { }
}
```