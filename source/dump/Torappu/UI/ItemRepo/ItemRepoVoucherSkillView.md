# ItemRepoVoucherSkillView

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `Action onBackOrCancel`

- `UIPageFinder m_pageFinder`


## Methods

- `Void OnChooseSkillClick(Int32)`

- `Void OnBackOrCancelClick()`

- `Void _RenderSelectPart(SkillGroupViewModel, ILoadAsset)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoVoucherSkillView : DataBinder`1
{
	private ItemRepoVoucherSkillSingleView[] _skillViews; // 0x20
	public Action`1 onChooseSkill; // 0x28
	public Action onBackOrCancel; // 0x30
	private UIPageFinder m_pageFinder; // 0x38
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_OnChooseSkillClick; // 0x8
	private static DelegateBridge __Hotfix0_OnBackOrCancelClick; // 0x10
	private static DelegateBridge __Hotfix0__RenderSelectPart; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2d3c0f4 VA: 0x75953540f4
	public override Void OnValueChanged(ItemRepoVoucherSkillViewProperty property) { }
	// RVA: 0x2d3c380 VA: 0x7595354380
	public Void OnChooseSkillClick(Int32 selectedIdx) { }
	// RVA: 0x2d3c420 VA: 0x7595354420
	public Void OnBackOrCancelClick() { }
	// RVA: 0x2d3c1c8 VA: 0x75953541c8
	private Void _RenderSelectPart(SkillGroupViewModel skillGroup, ILoadAsset assetLoader) { }
	// RVA: 0x2d3c4a4 VA: 0x75953544a4
	public Void .ctor() { }
}
```