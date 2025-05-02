# CommonCharSelectCardView

**Namespace:** `Torappu.UI.TemplateCharSelect.Common`


## Fields

- `Image _imgProfession`

- `Image _imgEvolve`

- `Image _imgPotential`

- `GameObject _panelPotential`

- `Text _txtLv`

- `UIAtlasImage _imgChar`

- `Text _txtCharName`

- `Image _imgRarity`

- `GameObject _panelSkill`

- `Image _imgSkill`

- `Text _txtSkillLevel`

- `Image _imgSkillSpecializeLv`

- `GameObject _panelNoSkill`

- `GameObject _panelEquip`

- `GameObject _panelEquipEmpty`

- `Image _imgEquip`

- `GameObject _objEquipLv`

- `Text _txtEquipLv`

- `GameObject _selectedPanel`

- `GameObject _emptyPanel`

- `Text _selectedIndex`

- `UIPageFinder m_uiPageFinder`

- `String m_portraitCache`

- `String m_skillIdCache`

- `Int32 m_potentialCache`

- `String m_uniequipCache`


## Methods

- `Void _RenderInternal(CommonCharSelectCardViewModel)`

- `Void _RenderSelectPanel(Boolean, Int32)`

- `Void _RenderSkillInfo(String, Int32, Int32)`

- `Void _RenderEquipInfo(String, Int32)`

- `Sprite _LoadRarityIcon(RarityRank)`

- `Sprite _LoadProfessionIcon(ILoadAsset, ProfessionCategory)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateCharSelect.Common
public class CommonCharSelectCardView : TemplateCharSelectCardView
{
	private Image _imgProfession; // 0x38
	private Image _imgEvolve; // 0x40
	private Image _imgPotential; // 0x48
	private GameObject _panelPotential; // 0x50
	private Text _txtLv; // 0x58
	private UIAtlasImage _imgChar; // 0x60
	private Text _txtCharName; // 0x68
	private Image _imgRarity; // 0x70
	private GameObject _panelSkill; // 0x78
	private Image _imgSkill; // 0x80
	private Text _txtSkillLevel; // 0x88
	private Image _imgSkillSpecializeLv; // 0x90
	private GameObject _panelNoSkill; // 0x98
	private GameObject _panelEquip; // 0xa0
	private GameObject _panelEquipEmpty; // 0xa8
	private Image _imgEquip; // 0xb0
	private GameObject _objEquipLv; // 0xb8
	private Text _txtEquipLv; // 0xc0
	private GameObject _selectedPanel; // 0xc8
	private GameObject _emptyPanel; // 0xd0
	private Text _selectedIndex; // 0xd8
	private UIPageFinder m_uiPageFinder; // 0xe0
	private Action`1 m_clickListener; // 0xf0
	private String m_portraitCache; // 0xf8
	private String m_skillIdCache; // 0x100
	private Int32 m_potentialCache; // 0x108
	private String m_uniequipCache; // 0x110
	private static DelegateBridge __Hotfix0_DoRender; // 0x0
	private static DelegateBridge __Hotfix0_OnRender; // 0x8
	private static DelegateBridge __Hotfix0__RenderInternal; // 0x10
	private static DelegateBridge __Hotfix0__RenderSelectPanel; // 0x18
	private static DelegateBridge __Hotfix0__RenderSkillInfo; // 0x20
	private static DelegateBridge __Hotfix0__RenderEquipInfo; // 0x28
	private static DelegateBridge __Hotfix0__LoadRarityIcon; // 0x30
	private static DelegateBridge __Hotfix0__LoadProfessionIcon; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x2c575d4 VA: 0x759526f5d4
	protected sealed override Void DoRender(TemplateCharSelectCardViewModel viewModel) { }
	// RVA: 0x2c57a18 VA: 0x759526fa18
	protected virtual Void OnRender(TemplateCharSelectCardViewModel viewModel) { }
	// RVA: 0x2c576cc VA: 0x759526f6cc
	private Void _RenderInternal(CommonCharSelectCardViewModel viewModel) { }
	// RVA: 0x2c57bc4 VA: 0x759526fbc4
	private Void _RenderSelectPanel(Boolean selected, Int32 selectIndex) { }
	// RVA: 0x2c57dc8 VA: 0x759526fdc8
	private Void _RenderSkillInfo(String skillId, Int32 skillSpecLvl, Int32 skillAllLvl) { }
	// RVA: 0x2c580d8 VA: 0x75952700d8
	private Void _RenderEquipInfo(String equipId, Int32 equipLv) { }
	// RVA: 0x2c57b40 VA: 0x759526fb40
	private Sprite _LoadRarityIcon(RarityRank rarity) { }
	// RVA: 0x2c57a90 VA: 0x759526fa90
	private Sprite _LoadProfessionIcon(ILoadAsset loader, ProfessionCategory profession) { }
	// RVA: 0x2c5827c VA: 0x759527027c
	public Void .ctor() { }
}
```