# RecruitSpecialGachaInitView

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `Image _imgBkg`

- `Text _textIntro`

- `Text _textTime`

- `Action <onDetailBtnClicked>k__BackingField`

- `Action <onSelectCharBtnClicked>k__BackingField`

- `UIPageFinder m_pageFinder`


## Properties

- `Action onDetailBtnClicked`

- `Action onSelectCharBtnClicked`


## Methods

- `Action get_onDetailBtnClicked()`

- `Void set_onDetailBtnClicked(Action)`

- `Action get_onSelectCharBtnClicked()`

- `Void set_onSelectCharBtnClicked(Action)`

- `Void EventOnDetailBtnClicked()`

- `Void EventOnSelectCharBtnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitSpecialGachaInitView : DataBinder`1, IHotfixable
{
	private Image _imgBkg; // 0x20
	private Text _textIntro; // 0x28
	private Text _textTime; // 0x30
	private Action <onDetailBtnClicked>k__BackingField; // 0x38
	private Action <onSelectCharBtnClicked>k__BackingField; // 0x40
	private UIPageFinder m_pageFinder; // 0x48
	private static DelegateBridge __Hotfix0_get_onDetailBtnClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onDetailBtnClicked; // 0x8
	private static DelegateBridge __Hotfix0_get_onSelectCharBtnClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onSelectCharBtnClicked; // 0x18
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x20
	private static DelegateBridge __Hotfix0_EventOnDetailBtnClicked; // 0x28
	private static DelegateBridge __Hotfix0_EventOnSelectCharBtnClicked; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private Action onDetailBtnClicked { get; set; }
	private Action onSelectCharBtnClicked { get; set; }

	// RVA: 0x271c8e8 VA: 0x7594d348e8
	private Action get_onDetailBtnClicked() { }
	// RVA: 0x271c950 VA: 0x7594d34950
	public Void set_onDetailBtnClicked(Action value) { }
	// RVA: 0x271c9d4 VA: 0x7594d349d4
	private Action get_onSelectCharBtnClicked() { }
	// RVA: 0x271ca3c VA: 0x7594d34a3c
	public Void set_onSelectCharBtnClicked(Action value) { }
	// RVA: 0x271cac0 VA: 0x7594d34ac0
	public override Void OnValueChanged(RecruitSpecialGachaProperty property) { }
	// RVA: 0x271cc1c VA: 0x7594d34c1c
	public Void EventOnDetailBtnClicked() { }
	// RVA: 0x271ccb8 VA: 0x7594d34cb8
	public Void EventOnSelectCharBtnClicked() { }
	// RVA: 0x271cd54 VA: 0x7594d34d54
	public Void .ctor() { }
}
```