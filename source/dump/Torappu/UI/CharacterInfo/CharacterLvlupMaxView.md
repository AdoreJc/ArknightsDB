# CharacterLvlupMaxView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Image _imgCampLogo`

- `Text _txtLevel`

- `Image _imgEvolve`

- `Text _txtCurMaxHp`

- `Text _txtOriMaxHp`

- `Text _txtCurAtk`

- `Text _txtOriAtk`

- `Text _txtCurDef`

- `Text _txtOriDef`

- `Text _txtCurRes`

- `Text _txtOriRes`

- `Color _highlightAttrColor`

- `CharacterLvlupMaxStateBean _stateBean`


## Methods

- `Void Render()`

- `String _ParseCurrentValueDesc(Int32, Int32)`

- `String _ParseCurrentValueDesc(Single, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterLvlupMaxView : MonoBehaviour, IHotfixable
{
	private Image _imgCampLogo; // 0x18
	private Text _txtLevel; // 0x20
	private Image _imgEvolve; // 0x28
	private Text _txtCurMaxHp; // 0x30
	private Text _txtOriMaxHp; // 0x38
	private Text _txtCurAtk; // 0x40
	private Text _txtOriAtk; // 0x48
	private Text _txtCurDef; // 0x50
	private Text _txtOriDef; // 0x58
	private Text _txtCurRes; // 0x60
	private Text _txtOriRes; // 0x68
	private Color _highlightAttrColor; // 0x70
	private CharacterLvlupMaxStateBean _stateBean; // 0x80
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__ParseCurrentValueDesc; // 0x8
	private static DelegateBridge __Hotfix1__ParseCurrentValueDesc; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2d781f8 VA: 0x75953901f8
	public Void Render() { }
	// RVA: 0x2d78620 VA: 0x7595390620
	private String _ParseCurrentValueDesc(Int32 current, Int32 origin) { }
	// RVA: 0x2d7870c VA: 0x759539070c
	private String _ParseCurrentValueDesc(Single current, Single origin) { }
	// RVA: 0x2d78814 VA: 0x7595390814
	public Void .ctor() { }
}
```