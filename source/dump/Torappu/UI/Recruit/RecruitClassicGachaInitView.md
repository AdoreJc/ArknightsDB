# RecruitClassicGachaInitView

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `Text _txtDesc`

- `Text _txtSummary`

- `Action <onStartBtnClick>k__BackingField`

- `Action <onDetailBtnClick>k__BackingField`


## Properties

- `Action onStartBtnClick`

- `Action onDetailBtnClick`


## Methods

- `Action get_onStartBtnClick()`

- `Void set_onStartBtnClick(Action)`

- `Action get_onDetailBtnClick()`

- `Void set_onDetailBtnClick(Action)`

- `Void Render(GachaPoolClientData)`

- `Void EventOnStartBtnClick()`

- `Void EventOnDetailBtnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitClassicGachaInitView : MonoBehaviour, IHotfixable
{
	private const String CLASSIC_FES_HOME_DESC; // 0x0
	private Text _txtDesc; // 0x18
	private Text _txtSummary; // 0x20
	private Action <onStartBtnClick>k__BackingField; // 0x28
	private Action <onDetailBtnClick>k__BackingField; // 0x30
	private static DelegateBridge __Hotfix0_get_onStartBtnClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onStartBtnClick; // 0x8
	private static DelegateBridge __Hotfix0_get_onDetailBtnClick; // 0x10
	private static DelegateBridge __Hotfix0_set_onDetailBtnClick; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0_EventOnStartBtnClick; // 0x28
	private static DelegateBridge __Hotfix0_EventOnDetailBtnClick; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private Action onStartBtnClick { get; set; }
	private Action onDetailBtnClick { get; set; }

	// RVA: 0x2712e3c VA: 0x7594d2ae3c
	private Action get_onStartBtnClick() { }
	// RVA: 0x2712ea4 VA: 0x7594d2aea4
	public Void set_onStartBtnClick(Action value) { }
	// RVA: 0x2712f28 VA: 0x7594d2af28
	private Action get_onDetailBtnClick() { }
	// RVA: 0x2712f90 VA: 0x7594d2af90
	public Void set_onDetailBtnClick(Action value) { }
	// RVA: 0x2713014 VA: 0x7594d2b014
	public Void Render(GachaPoolClientData data) { }
	// RVA: 0x2713168 VA: 0x7594d2b168
	public Void EventOnStartBtnClick() { }
	// RVA: 0x2713204 VA: 0x7594d2b204
	public Void EventOnDetailBtnClick() { }
	// RVA: 0x27132a0 VA: 0x7594d2b2a0
	public Void .ctor() { }
}
```