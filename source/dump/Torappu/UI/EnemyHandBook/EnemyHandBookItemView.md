# EnemyHandBookItemView

**Namespace:** `Torappu.UI.EnemyHandBook`


## Fields

- `GameObject _selectPart`

- `GameObject _lockedPart`

- `Image _viewPart`

- `GameObject _newPart`

- `GameObject _bossLogo`

- `GameObject _idPart`

- `Text _idText`

- `EnemyHandBookEverViewModel m_viewModel`

- `Boolean m_disableNewFlag`


## Methods

- `Void set_onClick(Action`1)`

- `Void OnClick()`

- `Void SetSelectState(String)`

- `Void _UpdateNewFlag()`

- `Void Render(Int32, EnemyHandBookEverViewModel, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.EnemyHandBook
public class EnemyHandBookItemView : MonoBehaviour, IHotfixable
{
	private GameObject _selectPart; // 0x18
	private GameObject _lockedPart; // 0x20
	private Image _viewPart; // 0x28
	private GameObject _newPart; // 0x30
	private GameObject _bossLogo; // 0x38
	private GameObject _idPart; // 0x40
	private Text _idText; // 0x48
	private Action`1 <onClick>k__BackingField; // 0x50
	private EnemyHandBookEverViewModel m_viewModel; // 0x58
	private Boolean m_disableNewFlag; // 0x60
	private static DelegateBridge __Hotfix0_get_onClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onClick; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge __Hotfix0_SetSelectState; // 0x18
	private static DelegateBridge __Hotfix0__UpdateNewFlag; // 0x20
	private static DelegateBridge __Hotfix0_Render; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Action`1 onClick { get; set; }

	// RVA: 0x2936174 VA: 0x7594f4e174
	private Action`1 get_onClick() { }
	// RVA: 0x29361dc VA: 0x7594f4e1dc
	public Void set_onClick(Action`1 value) { }
	// RVA: 0x2936260 VA: 0x7594f4e260
	public Void OnClick() { }
	// RVA: 0x2936310 VA: 0x7594f4e310
	public Void SetSelectState(String enemyId) { }
	// RVA: 0x293641c VA: 0x7594f4e41c
	private Void _UpdateNewFlag() { }
	// RVA: 0x29364cc VA: 0x7594f4e4cc
	public Void Render(Int32 index, EnemyHandBookEverViewModel viewModel, Boolean disableNewFlag) { }
	// RVA: 0x2936698 VA: 0x7594f4e698
	public Void .ctor() { }
}
```