# UniEquipArchiveCharacterEquipView

**Namespace:** `Torappu.UI.UniEquipArchive`


## Fields

- `Image _icon`

- `GameObject _panelSingleType`

- `GameObject _panelMultiType`

- `Text _uniEquipSingleTypeDesc`

- `Text _uniEquipMultiTypeDesc`

- `Image _uniEquipMultiTypeDescImg`

- `GameObject _backImg`

- `GameObject _haveIconPart`

- `GameObject _noIconPart`

- `GameObject _lockPart`

- `GameObject _panelLevel`

- `Text _level`

- `Color _initialIconColor`

- `Color _advancedIconColor`

- `Action onEquipClick`


## Methods

- `Void Render(UniEquipArchiveEquipTypeViewModel)`

- `Void _ActivateIcon(Boolean, Boolean)`

- `Void OnEquipClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquipArchive
public class UniEquipArchiveCharacterEquipView : MonoBehaviour, IHotfixable
{
	private Image _icon; // 0x18
	private GameObject _panelSingleType; // 0x20
	private GameObject _panelMultiType; // 0x28
	private Text _uniEquipSingleTypeDesc; // 0x30
	private Text _uniEquipMultiTypeDesc; // 0x38
	private Image _uniEquipMultiTypeDescImg; // 0x40
	private GameObject _backImg; // 0x48
	private GameObject _haveIconPart; // 0x50
	private GameObject _noIconPart; // 0x58
	private GameObject _lockPart; // 0x60
	private GameObject _panelLevel; // 0x68
	private Text _level; // 0x70
	private Color _initialIconColor; // 0x78
	private Color _advancedIconColor; // 0x88
	public Action onEquipClick; // 0x98
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__ActivateIcon; // 0x8
	private static DelegateBridge __Hotfix0_OnEquipClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x22eb480 VA: 0x7594903480
	public Void Render(UniEquipArchiveEquipTypeViewModel viewModel) { }
	// RVA: 0x22eb71c VA: 0x759490371c
	private Void _ActivateIcon(Boolean haveIcon, Boolean isLocked) { }
	// RVA: 0x22eb7d4 VA: 0x75949037d4
	public Void OnEquipClick() { }
	// RVA: 0x22eb858 VA: 0x7594903858
	public Void .ctor() { }
}
```