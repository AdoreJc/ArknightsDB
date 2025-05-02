# CharacterInfoRightProfUniEquipItem

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Transform _container`

- `UICommonEquipTypeIcon _equipItem`

- `UIColorGraphic _clickBtnColor`

- `GameObject _selectPart`

- `GameObject _cacheSelectPart`

- `GameObject _isLocked`

- `UICommonEquipTypeIcon m_equipItem`

- `Boolean m_isInited`

- `CharacterUniEquipViewModel m_cacheViewModel`


## Methods

- `Void _InitIfNot()`

- `Void Render(CharacterUniEquipViewModel, String)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoRightProfUniEquipItem : MonoBehaviour, IHotfixable
{
	private Transform _container; // 0x18
	private UICommonEquipTypeIcon _equipItem; // 0x20
	private UIColorGraphic _clickBtnColor; // 0x28
	private GameObject _selectPart; // 0x30
	private GameObject _cacheSelectPart; // 0x38
	private GameObject _isLocked; // 0x40
	public Action`1 onEquipClick; // 0x48
	private UICommonEquipTypeIcon m_equipItem; // 0x50
	private Boolean m_isInited; // 0x58
	private CharacterUniEquipViewModel m_cacheViewModel; // 0x60
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_OnClick; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2d86c00 VA: 0x759539ec00
	private Void _InitIfNot() { }
	// RVA: 0x2d8622c VA: 0x759539e22c
	public Void Render(CharacterUniEquipViewModel equipViewModel, String selectEquip) { }
	// RVA: 0x2d86d18 VA: 0x759539ed18
	public Void OnClick() { }
	// RVA: 0x2d86e00 VA: 0x759539ee00
	public Void .ctor() { }
}
```