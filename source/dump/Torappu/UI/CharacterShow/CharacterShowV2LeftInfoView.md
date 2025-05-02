# CharacterShowV2LeftInfoView

**Namespace:** `Torappu.UI.CharacterShow`


## Fields

- `Text _maxHp`

- `Text _reviveTime`

- `Text _atk`

- `Text _cost`

- `Text _def`

- `Text _blockNum`

- `Text _res`

- `Text _atkSpeed`

- `Text _textLv`

- `Image _imgEvolve`

- `Image _imgPotential`

- `CharacterInfoIllustWrapper _illustWrapper`

- `Image _raritySprite`

- `Image _campSprite`

- `Text _name`

- `Text _appellation`

- `Text _textPosition`

- `Text _textTags`

- `Image _imgProfession`

- `UICharacterAttackRangeWidget _attackRange`

- `Text _textFavorPoint`

- `Slider _sliderFavorPoint`

- `UIPageFinder m_pageFinder`

- `CharacterShowV2Model m_charShowModel`


## Methods

- `Void _UpdateAttackRange()`

- `Void _UpdateCharInfo()`

- `Void _UpdateAttrs()`

- `Void _LoadCharIllust()`

- `String _GetAttrValWithFavor(Int32, Int32)`

- `String _GetAttrValWithFavor(Single, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterShow
public class CharacterShowV2LeftInfoView : DataBinder`1
{
	private Text _maxHp; // 0x20
	private Text _reviveTime; // 0x28
	private Text _atk; // 0x30
	private Text _cost; // 0x38
	private Text _def; // 0x40
	private Text _blockNum; // 0x48
	private Text _res; // 0x50
	private Text _atkSpeed; // 0x58
	private Text _textLv; // 0x60
	private Image _imgEvolve; // 0x68
	private Image _imgPotential; // 0x70
	private CharacterInfoIllustWrapper _illustWrapper; // 0x78
	private Image _raritySprite; // 0x80
	private Image _campSprite; // 0x88
	private Text _name; // 0x90
	private Text _appellation; // 0x98
	private Text _textPosition; // 0xa0
	private Text _textTags; // 0xa8
	private Image _imgProfession; // 0xb0
	private UICharacterAttackRangeWidget _attackRange; // 0xb8
	private Text _textFavorPoint; // 0xc0
	private Slider _sliderFavorPoint; // 0xc8
	private UIPageFinder m_pageFinder; // 0xd0
	private CharacterShowV2Model m_charShowModel; // 0xe0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__UpdateAttackRange; // 0x8
	private static DelegateBridge __Hotfix0__UpdateCharInfo; // 0x10
	private static DelegateBridge __Hotfix0__UpdateAttrs; // 0x18
	private static DelegateBridge __Hotfix0__LoadCharIllust; // 0x20
	private static DelegateBridge __Hotfix0__GetAttrValWithFavor; // 0x28
	private static DelegateBridge __Hotfix1__GetAttrValWithFavor; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2ce8340 VA: 0x7595300340
	public override Void OnValueChanged(CharacterShowProp property) { }
	// RVA: 0x2ce8c40 VA: 0x7595300c40
	private Void _UpdateAttackRange() { }
	// RVA: 0x2ce84d0 VA: 0x75953004d0
	private Void _UpdateCharInfo() { }
	// RVA: 0x2ce85e4 VA: 0x75953005e4
	private Void _UpdateAttrs() { }
	// RVA: 0x2ce8a74 VA: 0x7595300a74
	private Void _LoadCharIllust() { }
	// RVA: 0x2ce8ccc VA: 0x7595300ccc
	private String _GetAttrValWithFavor(Int32 totalVal, Int32 favorVal) { }
	// RVA: 0x2ce8df0 VA: 0x7595300df0
	private String _GetAttrValWithFavor(Single totalVal, Single favorVal) { }
	// RVA: 0x2ce8f14 VA: 0x7595300f14
	public Void .ctor() { }
}
```