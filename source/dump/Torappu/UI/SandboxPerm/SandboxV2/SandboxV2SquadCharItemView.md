# SandboxV2SquadCharItemView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `GameObject _charPartGo`

- `GameObject _emptyPartGo`

- `GameObject _thresholdPartGo`

- `Text _textSlotIdxInEmpty`

- `Text _textCharMaxInEmpty`

- `Text _textSlotIdxInThreshold`

- `Text _textCharMaxInThreshold`

- `Image _imgAvatar`

- `Image _imgProfession`

- `Image _imgRarity`

- `Image _imgEvolve`

- `Image _imgPotential`

- `Text _textLv`

- `Text _textName`

- `UIAtlasImage _imgRarityBanner`

- `SimpleLayoutContent _skillList`

- `GameObject _emptyEquipGo`

- `GameObject _detailEquipGo`

- `Image _imgEquipIcon`

- `GameObject _haveFoodGo`

- `GameObject _noFoodGo`

- `GameObject _durationLastingPanel`

- `GameObject _durationNormalPanel`

- `UISlicedCircleBar _foodTotalCircleBar`

- `UISlicedCircleBar _foodCurrCircleBar`

- `Image _imgFood`

- `CanvasGroup _cookCanvasGroup`

- `Single _cookDisableAlpha`

- `GameObject _statusUsedGo`

- `GameObject _statusSupplyGo`

- `GameObject _statusExpedGo`

- `Text _textUsedCaption`

- `Text _textSupplyCaption`

- `Text _textExpedCaption`

- `UIPageFinder m_pageFinder`

- `SKillListAdapter m_skillListAdapter`

- `SandboxV2SquadCharModel m_squadCharModel`

- `Int32 m_position`


## Methods

- `Void set_onSkillSelect(Action`2)`

- `Void set_onCharDineClick(Action`1)`

- `Void set_onSlotClick(Action`1)`

- `Void RenderNextThreshold(Int32, Int32)`

- `Void RenderChar(Int32, Int32, SandboxV2SquadCharModel, SandboxV2CharFoodModel)`

- `Void _RenderFoodInfo(SandboxV2CharFoodModel, Boolean)`

- `Void EventOnDineClick()`

- `Void EventOnSlotClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2SquadCharItemView : MonoBehaviour, IHotfixable
{
	private GameObject _charPartGo; // 0x18
	private GameObject _emptyPartGo; // 0x20
	private GameObject _thresholdPartGo; // 0x28
	private Text _textSlotIdxInEmpty; // 0x30
	private Text _textCharMaxInEmpty; // 0x38
	private Text _textSlotIdxInThreshold; // 0x40
	private Text _textCharMaxInThreshold; // 0x48
	private Image _imgAvatar; // 0x50
	private Image _imgProfession; // 0x58
	private Image _imgRarity; // 0x60
	private Image _imgEvolve; // 0x68
	private Image _imgPotential; // 0x70
	private Text _textLv; // 0x78
	private Text _textName; // 0x80
	private UIAtlasImage _imgRarityBanner; // 0x88
	private SimpleLayoutContent _skillList; // 0x90
	private GameObject _emptyEquipGo; // 0x98
	private GameObject _detailEquipGo; // 0xa0
	private Image _imgEquipIcon; // 0xa8
	private GameObject _haveFoodGo; // 0xb0
	private GameObject _noFoodGo; // 0xb8
	private GameObject _durationLastingPanel; // 0xc0
	private GameObject _durationNormalPanel; // 0xc8
	private UISlicedCircleBar _foodTotalCircleBar; // 0xd0
	private UISlicedCircleBar _foodCurrCircleBar; // 0xd8
	private Image _imgFood; // 0xe0
	private CanvasGroup _cookCanvasGroup; // 0xe8
	private Single _cookDisableAlpha; // 0xf0
	private GameObject _statusUsedGo; // 0xf8
	private GameObject _statusSupplyGo; // 0x100
	private GameObject _statusExpedGo; // 0x108
	private Text _textUsedCaption; // 0x110
	private Text _textSupplyCaption; // 0x118
	private Text _textExpedCaption; // 0x120
	private UIPageFinder m_pageFinder; // 0x128
	private SKillListAdapter m_skillListAdapter; // 0x138
	private SandboxV2SquadCharModel m_squadCharModel; // 0x140
	private Int32 m_position; // 0x148
	private Action`2 <onSkillSelect>k__BackingField; // 0x150
	private Action`1 <onCharDineClick>k__BackingField; // 0x158
	private Action`1 <onSlotClick>k__BackingField; // 0x160
	private static DelegateBridge __Hotfix0_get_onSkillSelect; // 0x0
	private static DelegateBridge __Hotfix0_set_onSkillSelect; // 0x8
	private static DelegateBridge __Hotfix0_get_onCharDineClick; // 0x10
	private static DelegateBridge __Hotfix0_set_onCharDineClick; // 0x18
	private static DelegateBridge __Hotfix0_get_onSlotClick; // 0x20
	private static DelegateBridge __Hotfix0_set_onSlotClick; // 0x28
	private static DelegateBridge __Hotfix0_RenderNextThreshold; // 0x30
	private static DelegateBridge __Hotfix0_RenderChar; // 0x38
	private static DelegateBridge __Hotfix0__RenderFoodInfo; // 0x40
	private static DelegateBridge __Hotfix0_EventOnDineClick; // 0x48
	private static DelegateBridge __Hotfix0_EventOnSlotClick; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	private Action`2 onSkillSelect { get; set; }
	private Action`1 onCharDineClick { get; set; }
	private Action`1 onSlotClick { get; set; }

	// RVA: 0x260f1ec VA: 0x7594c271ec
	private Action`2 get_onSkillSelect() { }
	// RVA: 0x260f254 VA: 0x7594c27254
	public Void set_onSkillSelect(Action`2 value) { }
	// RVA: 0x260f2d8 VA: 0x7594c272d8
	private Action`1 get_onCharDineClick() { }
	// RVA: 0x260f340 VA: 0x7594c27340
	public Void set_onCharDineClick(Action`1 value) { }
	// RVA: 0x260f3c4 VA: 0x7594c273c4
	private Action`1 get_onSlotClick() { }
	// RVA: 0x260f42c VA: 0x7594c2742c
	public Void set_onSlotClick(Action`1 value) { }
	// RVA: 0x260f4b0 VA: 0x7594c274b0
	public Void RenderNextThreshold(Int32 position, Int32 nextCharLimit) { }
	// RVA: 0x260f63c VA: 0x7594c2763c
	public Void RenderChar(Int32 position, Int32 charLimit, SandboxV2SquadCharModel squadCharModel, SandboxV2CharFoodModel foodModel) { }
	// RVA: 0x260fee8 VA: 0x7594c27ee8
	private Void _RenderFoodInfo(SandboxV2CharFoodModel foodModel, Boolean isFoodDisabled) { }
	// RVA: 0x26100f4 VA: 0x7594c280f4
	public Void EventOnDineClick() { }
	// RVA: 0x261020c VA: 0x7594c2820c
	public Void EventOnSlotClick() { }
	// RVA: 0x26102ac VA: 0x7594c282ac
	public Void .ctor() { }
}
```