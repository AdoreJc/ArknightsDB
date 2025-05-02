# CrisisV2SettleCardView

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `UIAtlasImage _imagePortrait`

- `GameObject _panelGradientNoInfo`

- `GameObject _panelGradientNormal`

- `GameObject _panelInfo`

- `GameObject _objAssist`

- `GameObject _panelSkill`

- `Image _imgSkill`

- `Text _textSkillLevel`

- `Image _imgSkillSpecializeLv`

- `GameObject _panelNoSkill`

- `Image _imgEvolve`

- `Text _txtLv`

- `Image _imgPotential`

- `GameObject _panelPotential`

- `GameObject _panelEquip`

- `GameObject _panelEquipEmpty`

- `Image _imgEquip`

- `GameObject _equipLvGo`

- `Text _textEquipLv`


## Methods

- `Void Render(CharacterCardViewModel, Boolean)`

- `Void RenderNoDetailCharacter(SquadSkinInfo, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2SettleCardView : MonoBehaviour, IHotfixable
{
	private UIAtlasImage _imagePortrait; // 0x18
	private GameObject _panelGradientNoInfo; // 0x20
	private GameObject _panelGradientNormal; // 0x28
	private GameObject _panelInfo; // 0x30
	private GameObject _objAssist; // 0x38
	private GameObject _panelSkill; // 0x40
	private Image _imgSkill; // 0x48
	private Text _textSkillLevel; // 0x50
	private Image _imgSkillSpecializeLv; // 0x58
	private GameObject _panelNoSkill; // 0x60
	private Image _imgEvolve; // 0x68
	private Text _txtLv; // 0x70
	private Image _imgPotential; // 0x78
	private GameObject _panelPotential; // 0x80
	private GameObject _panelEquip; // 0x88
	private GameObject _panelEquipEmpty; // 0x90
	private Image _imgEquip; // 0x98
	private GameObject _equipLvGo; // 0xa0
	private Text _textEquipLv; // 0xa8
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_RenderNoDetailCharacter; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2bcf97c VA: 0x75951e797c
	public Void Render(CharacterCardViewModel viewModel, Boolean isAssist) { }
	// RVA: 0x2bcff68 VA: 0x75951e7f68
	public Void RenderNoDetailCharacter(SquadSkinInfo skinInfo, Boolean isAssist) { }
	// RVA: 0x2bd01c8 VA: 0x75951e81c8
	public Void .ctor() { }
}
```