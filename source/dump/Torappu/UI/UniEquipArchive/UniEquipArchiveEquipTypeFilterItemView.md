# UniEquipArchiveEquipTypeFilterItemView

**Namespace:** `Torappu.UI.UniEquipArchive`


## Fields

- `Text _txtType`

- `Image _imgType`

- `Color _selectedColor`

- `Color _unselectedColor`

- `GameObject _objSplitLine`

- `String m_filterType`


## Methods

- `Void Render(UniEquipArchiveModuleTYpeFilterItemInfoData, String)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.UniEquipArchive
public class UniEquipArchiveEquipTypeFilterItemView : MonoBehaviour, IHotfixable
{
	private Text _txtType; // 0x18
	private Image _imgType; // 0x20
	private Color _selectedColor; // 0x28
	private Color _unselectedColor; // 0x38
	private GameObject _objSplitLine; // 0x48
	private String m_filterType; // 0x50
	public Action`1 onFilterTypeItemClick; // 0x58
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_OnClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x22e395c VA: 0x75948fb95c
	public Void Render(UniEquipArchiveModuleTYpeFilterItemInfoData itemInfoData, String selectingFilterType) { }
	// RVA: 0x22e3b34 VA: 0x75948fbb34
	public Void OnClick() { }
	// RVA: 0x22e3bbc VA: 0x75948fbbbc
	public Void .ctor() { }
}
```