# CommonCharSelectCardDefaultPanel

**Namespace:** `Torappu.UI.TemplateCharSelect.Common`


## Fields

- `UIAtlasImage _imageChrPortrait`

- `Image _iconProfession`

- `GameObject _panelSkill`

- `GameObject _panelNoSkill`

- `Image _iconSkill`

- `GameObject _panelPotential`

- `Image _iconPotential`

- `Image _iconEvolve`

- `GameObject _panelUniequip`

- `Image _iconUniequip`

- `Text _textLevel`

- `Image _imageLvlPercent`

- `Text _textRealName`

- `Image _imageStarMark`

- `Image _imgCustomMark`

- `UICharCardRankWidget _panelStars`

- `UICharRarityImage _panelUpperHub`

- `UICharRarityImage _panelLowerHub`

- `UICharRarityImage _panelRarityLight`

- `UICharRarityImage _panelBkg`

- `UIColorGraphic _graphic`

- `GameObject _selectedPanel`

- `Text _selectedIndex`

- `String m_skillIdCache`

- `String m_portraitCache`

- `String m_uniequipCache`

- `BasicCharInfoModel m_infoCache`

- `UIPageFinder m_pageFinder`


## Properties

- `Graphic graphic`


## Methods

- `Graphic get_graphic()`

- `Void DoRender(TemplateCharSelectCardViewModel)`

- `Void _UpdateViewData(CommonCharSelectCardDefaultViewModel, Options)`

- `Void _RenderSelectPanel(Boolean, Int32)`

- `Sprite _LoadProfessionIcon(ILoadAsset, ProfessionCategory)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateCharSelect.Common
public class CommonCharSelectCardDefaultPanel : MonoBehaviour, IHotfixable
{
	private UIAtlasImage _imageChrPortrait; // 0x18
	private Image _iconProfession; // 0x20
	private GameObject _panelSkill; // 0x28
	private GameObject _panelNoSkill; // 0x30
	private Image _iconSkill; // 0x38
	private GameObject _panelPotential; // 0x40
	private Image _iconPotential; // 0x48
	private Image _iconEvolve; // 0x50
	private GameObject _panelUniequip; // 0x58
	private Image _iconUniequip; // 0x60
	private Text _textLevel; // 0x68
	private Image _imageLvlPercent; // 0x70
	private Text _textRealName; // 0x78
	private Image _imageStarMark; // 0x80
	private Image _imgCustomMark; // 0x88
	private UICharCardRankWidget _panelStars; // 0x90
	private UICharRarityImage _panelUpperHub; // 0x98
	private UICharRarityImage _panelLowerHub; // 0xa0
	private UICharRarityImage _panelRarityLight; // 0xa8
	private UICharRarityImage _panelBkg; // 0xb0
	private UIColorGraphic _graphic; // 0xb8
	private GameObject _selectedPanel; // 0xc0
	private Text _selectedIndex; // 0xc8
	private String m_skillIdCache; // 0xd0
	private String m_portraitCache; // 0xd8
	private String m_uniequipCache; // 0xe0
	private BasicCharInfoModel m_infoCache; // 0xe8
	private UIPageFinder m_pageFinder; // 0xf0
	private static DelegateBridge __Hotfix0_get_graphic; // 0x0
	private static DelegateBridge __Hotfix0_DoRender; // 0x8
	private static DelegateBridge __Hotfix0__UpdateViewData; // 0x10
	private static DelegateBridge __Hotfix0__RenderSelectPanel; // 0x18
	private static DelegateBridge __Hotfix0__IsCharBasicChanged; // 0x20
	private static DelegateBridge __Hotfix0__LoadProfessionIcon; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Graphic graphic { get; }

	// RVA: 0x2c514a4 VA: 0x75952694a4
	public Graphic get_graphic() { }
	// RVA: 0x2c5150c VA: 0x759526950c
	public Void DoRender(TemplateCharSelectCardViewModel viewModel) { }
	// RVA: 0x2c51608 VA: 0x7595269608
	private Void _UpdateViewData(CommonCharSelectCardDefaultViewModel viewModel, Options options) { }
	// RVA: 0x2c524ac VA: 0x759526a4ac
	private Void _RenderSelectPanel(Boolean selected, Int32 selectIndex) { }
	// RVA: 0x2c51d88 VA: 0x7595269d88
	private static Boolean _IsCharBasicChanged(BasicCharInfoModel prevInfo, BasicCharInfoModel curInfo) { }
	// RVA: 0x2c51f30 VA: 0x7595269f30
	private Sprite _LoadProfessionIcon(ILoadAsset loader, ProfessionCategory profession) { }
	// RVA: 0x2c525d0 VA: 0x759526a5d0
	public Void .ctor() { }
}
```