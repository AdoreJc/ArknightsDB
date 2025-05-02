# CharacterLvlupAttrAndExpInfoView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Text _txtCurMaxHp`

- `Text _txtTarMaxHp`

- `Text _txtCurAtk`

- `Text _txtTarAtk`

- `Text _txtCurDef`

- `Text _txtTarDef`

- `Text _txtCurRes`

- `Text _txtTarRes`

- `Color _highlightAttrColor`

- `Text _txtTargetLevel`

- `Text _txtCurExp`

- `Text _txtTotalExp`

- `Text _txtAddExp`

- `GameObject _panelCounting`


## Methods

- `Void Render(CharacterLvlupViewModel)`

- `String _ParseTargetValueDesc(Int32, Int32)`

- `String _ParseTargetValueDesc(Single, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterLvlupAttrAndExpInfoView : MonoBehaviour, IHotfixable
{
	private const String CONST_LEVEL_FORMAT; // 0x0
	private const String CONST_MAX_EXP; // 0x0
	private const String CONST_ADD_EXP_FORMAT; // 0x0
	private Text _txtCurMaxHp; // 0x18
	private Text _txtTarMaxHp; // 0x20
	private Text _txtCurAtk; // 0x28
	private Text _txtTarAtk; // 0x30
	private Text _txtCurDef; // 0x38
	private Text _txtTarDef; // 0x40
	private Text _txtCurRes; // 0x48
	private Text _txtTarRes; // 0x50
	private Color _highlightAttrColor; // 0x58
	private Text _txtTargetLevel; // 0x68
	private Text _txtCurExp; // 0x70
	private Text _txtTotalExp; // 0x78
	private Text _txtAddExp; // 0x80
	private GameObject _panelCounting; // 0x88
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__ParseTargetValueDesc; // 0x8
	private static DelegateBridge __Hotfix1__ParseTargetValueDesc; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2d74620 VA: 0x759538c620
	public Void Render(CharacterLvlupViewModel viewModel) { }
	// RVA: 0x2d749a4 VA: 0x759538c9a4
	private String _ParseTargetValueDesc(Int32 target, Int32 current) { }
	// RVA: 0x2d74a90 VA: 0x759538ca90
	private String _ParseTargetValueDesc(Single target, Single current) { }
	// RVA: 0x2d74b98 VA: 0x759538cb98
	public Void .ctor() { }
}
```