# CharacterLvlupAttrInfoView

**Namespace:** ` `


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


## Methods

- `Void Render(CharacterLvlupVoucherViewModel)`

- `String _ParseTargetValueDesc(Int32, Int32)`

- `String _ParseTargetValueDesc(Single, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class CharacterLvlupAttrInfoView : IHotfixable
{
	private Text _txtCurMaxHp; // 0x10
	private Text _txtTarMaxHp; // 0x18
	private Text _txtCurAtk; // 0x20
	private Text _txtTarAtk; // 0x28
	private Text _txtCurDef; // 0x30
	private Text _txtTarDef; // 0x38
	private Text _txtCurRes; // 0x40
	private Text _txtTarRes; // 0x48
	private Color _highlightAttrColor; // 0x50
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__ParseTargetValueDesc; // 0x8
	private static DelegateBridge __Hotfix1__ParseTargetValueDesc; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2d78bc4 VA: 0x7595390bc4
	public Void Render(CharacterLvlupVoucherViewModel viewModel) { }
	// RVA: 0x2d78e40 VA: 0x7595390e40
	private String _ParseTargetValueDesc(Int32 target, Int32 current) { }
	// RVA: 0x2d78f2c VA: 0x7595390f2c
	private String _ParseTargetValueDesc(Single target, Single current) { }
	// RVA: 0x2d79034 VA: 0x7595391034
	public Void .ctor() { }
}
```