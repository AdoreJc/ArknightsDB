# Act42D0BattleFinishCharItemView

**Namespace:** `Torappu.UI`


## Fields

- `GameObject _emptyPanel`

- `GameObject _charPanel`

- `GameObject _normalCharBgGo`

- `GameObject _assistCharBgGo`

- `UIAtlasImage _imgPortrait`

- `GameObject _panelSkill`

- `Image _imgSkill`

- `Text _textSkillLevel`

- `Image _imgSkillSpecializeLv`

- `Image _imgEvolve`

- `Image _imgProfession`

- `Text _txtLv`

- `Image _imgPotential`

- `GameObject _panelPotential`

- `GameObject _panelEquip`

- `GameObject _panelEquipEmpty`

- `Image _imgEquip`

- `GameObject _equipLvGo`

- `Text _textEquipLv`


## Methods

- `Void Render(SquadItemStruct, Boolean)`

- `Void _RenderSkill(CharacterCardViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class Act42D0BattleFinishCharItemView : MonoBehaviour, IHotfixable
{
	private GameObject _emptyPanel; // 0x18
	private GameObject _charPanel; // 0x20
	private GameObject _normalCharBgGo; // 0x28
	private GameObject _assistCharBgGo; // 0x30
	private UIAtlasImage _imgPortrait; // 0x38
	private GameObject _panelSkill; // 0x40
	private Image _imgSkill; // 0x48
	private Text _textSkillLevel; // 0x50
	private Image _imgSkillSpecializeLv; // 0x58
	private Image _imgEvolve; // 0x60
	private Image _imgProfession; // 0x68
	private Text _txtLv; // 0x70
	private Image _imgPotential; // 0x78
	private GameObject _panelPotential; // 0x80
	private GameObject _panelEquip; // 0x88
	private GameObject _panelEquipEmpty; // 0x90
	private Image _imgEquip; // 0x98
	private GameObject _equipLvGo; // 0xa0
	private Text _textEquipLv; // 0xa8
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__RenderSkill; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x20fb64c VA: 0x759471364c
	public Void Render(SquadItemStruct charStruct, Boolean isAssist) { }
	// RVA: 0x20fbb0c VA: 0x7594713b0c
	private Void _RenderSkill(CharacterCardViewModel cardModel) { }
	// RVA: 0x20fbd3c VA: 0x7594713d3c
	public Void .ctor() { }
}
```