# BattleFinishCard

**Namespace:** `Torappu.Activity.Act5D1`


## Fields

- `Image _bg`

- `Image _imageChrIcon`

- `GameObject _panelNoSkill`

- `Image _iconSkill`

- `GameObject _panelPotential`

- `Image _iconPotential`

- `Image _iconEvolve`

- `Text _textLevel`


## Methods

- `Void UpdateViewData(CharacterCardViewModel, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
public class BattleFinishCard : MonoBehaviour, IHotfixable
{
	private Image _bg; // 0x18
	private Image _imageChrIcon; // 0x20
	private GameObject _panelNoSkill; // 0x28
	private Image _iconSkill; // 0x30
	private GameObject _panelPotential; // 0x38
	private Image _iconPotential; // 0x40
	private Image _iconEvolve; // 0x48
	private Text _textLevel; // 0x50
	private static DelegateBridge __Hotfix0_UpdateViewData; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x31c8a10 VA: 0x75957e0a10
	public Void UpdateViewData(CharacterCardViewModel viewModel, Boolean isAssist) { }
	// RVA: 0x31c8c70 VA: 0x75957e0c70
	public Void .ctor() { }
}
```