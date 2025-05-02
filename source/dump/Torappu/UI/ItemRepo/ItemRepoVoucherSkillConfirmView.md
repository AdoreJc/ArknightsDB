# ItemRepoVoucherSkillConfirmView

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `CharacterInfoSkillView _nowLevel`

- `Image _nowSpecialIcon`

- `CharacterInfoSkillView _maxLevel`

- `Image _maxSpecialIcon`

- `Image _specialLvl`

- `Image _specialLvlGlow`

- `Transform _itemCardContainer`

- `Single _itemCardScale`

- `Text _itemCountText`

- `Action onConfirmUpgrade`

- `Action onBackOrCancel`

- `UIItemCard m_itemCard`

- `UIPageFinder m_pageFinder`


## Methods

- `Void OnConfirmUpgrade()`

- `Void OnBackOrCancelClick()`

- `Void _RenderConfirmPart(SkillItemViewModel, ILoadAsset)`

- `SkillItemViewModel _GetSpecialMaxData(SkillItemViewModel)`

- `Void _RefreshItemCardView(UIItemViewModel)`

- `Void _OnItemClick(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoVoucherSkillConfirmView : DataBinder`1
{
	private const Int32 REQUIRE_ITEM_COUNT; // 0x0
	private const String ITEM_CNT_FORMAT_ENOUGH; // 0x0
	private const String ITEM_CNT_FORMAT_NOT_ENOUGH; // 0x0
	private CharacterInfoSkillView _nowLevel; // 0x20
	private Image _nowSpecialIcon; // 0x28
	private CharacterInfoSkillView _maxLevel; // 0x30
	private Image _maxSpecialIcon; // 0x38
	private Image _specialLvl; // 0x40
	private Image _specialLvlGlow; // 0x48
	private Transform _itemCardContainer; // 0x50
	private Single _itemCardScale; // 0x58
	private Text _itemCountText; // 0x60
	public Action onConfirmUpgrade; // 0x68
	public Action onBackOrCancel; // 0x70
	private UIItemCard m_itemCard; // 0x78
	private UIPageFinder m_pageFinder; // 0x80
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_OnConfirmUpgrade; // 0x8
	private static DelegateBridge __Hotfix0_OnBackOrCancelClick; // 0x10
	private static DelegateBridge __Hotfix0__RenderConfirmPart; // 0x18
	private static DelegateBridge __Hotfix0__GetSpecialMaxData; // 0x20
	private static DelegateBridge __Hotfix0__RefreshItemCardView; // 0x28
	private static DelegateBridge __Hotfix0__OnItemClick; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2d3b520 VA: 0x7595353520
	public override Void OnValueChanged(ItemRepoVoucherSkillViewProperty property) { }
	// RVA: 0x2d3bb38 VA: 0x7595353b38
	public Void OnConfirmUpgrade() { }
	// RVA: 0x2d3bbbc VA: 0x7595353bbc
	public Void OnBackOrCancelClick() { }
	// RVA: 0x2d3b640 VA: 0x7595353640
	private Void _RenderConfirmPart(SkillItemViewModel skillModel, ILoadAsset assetLoader) { }
	// RVA: 0x2d3bc40 VA: 0x7595353c40
	private SkillItemViewModel _GetSpecialMaxData(SkillItemViewModel skill) { }
	// RVA: 0x2d3b7d4 VA: 0x75953537d4
	private Void _RefreshItemCardView(UIItemViewModel itemModel) { }
	// RVA: 0x2d3bd4c VA: 0x7595353d4c
	private Void _OnItemClick(Int32 index) { }
	// RVA: 0x2d3be54 VA: 0x7595353e54
	public Void .ctor() { }
}
```