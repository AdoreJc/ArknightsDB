# RoguelikeCharSelectUniEquipView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Image _equipIcon`

- `GameObject _panelSingleType`

- `GameObject _panelMultiType`

- `Text _uniEquipSingleTypeDesc`

- `Text _uniEquipMultiTypeDesc`

- `Image _uniEquipMultiTypeDescImg`

- `GameObject _selectedObj`

- `GameObject _originDesc`

- `Text _equipName`

- `GameObject _equipLevel`

- `GameObject _equipConstLevel`

- `GameObject _lockedObj`


## Methods

- `Void Render(UniEquipData, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeCharSelectUniEquipView : MonoBehaviour, IHotfixable
{
	private Image _equipIcon; // 0x18
	private GameObject _panelSingleType; // 0x20
	private GameObject _panelMultiType; // 0x28
	private Text _uniEquipSingleTypeDesc; // 0x30
	private Text _uniEquipMultiTypeDesc; // 0x38
	private Image _uniEquipMultiTypeDescImg; // 0x40
	private GameObject _selectedObj; // 0x48
	private GameObject _originDesc; // 0x50
	private Text _equipName; // 0x58
	private GameObject _equipLevel; // 0x60
	private GameObject _equipConstLevel; // 0x68
	private GameObject _lockedObj; // 0x70
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x2acdf1c VA: 0x75950e5f1c
	public Void Render(UniEquipData equipData, Boolean needUpgrade) { }
	// RVA: 0x2acf25c VA: 0x75950e725c
	public Void .ctor() { }
}
```