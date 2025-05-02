# HomeCharRotationListSkinItem

**Namespace:** `Torappu.UI.Home`


## Fields

- `GameObject _notSelectedBg`

- `GameObject _selectedBg`

- `Image _charHeadIcon`

- `GameObject _assistDecor`

- `GameObject _selectedOutline`

- `String m_cachedSkinId`


## Methods

- `Void set_onClicked(Action`1)`

- `Void Render(HomeCharRotationPresetSkinItemViewModel, Boolean, Boolean)`

- `Void OnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeCharRotationListSkinItem : MonoBehaviour, IHotfixable
{
	private GameObject _notSelectedBg; // 0x18
	private GameObject _selectedBg; // 0x20
	private Image _charHeadIcon; // 0x28
	private GameObject _assistDecor; // 0x30
	private GameObject _selectedOutline; // 0x38
	private Action`1 <onClicked>k__BackingField; // 0x40
	private String m_cachedSkinId; // 0x48
	private static DelegateBridge __Hotfix0_get_onClicked; // 0x0
	private static DelegateBridge __Hotfix0_set_onClicked; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 onClicked { get; set; }

	// RVA: 0x282d284 VA: 0x7594e45284
	private Action`1 get_onClicked() { }
	// RVA: 0x282d070 VA: 0x7594e45070
	public Void set_onClicked(Action`1 value) { }
	// RVA: 0x282d0f4 VA: 0x7594e450f4
	public Void Render(HomeCharRotationPresetSkinItemViewModel model, Boolean isSelected, Boolean isAssist) { }
	// RVA: 0x282d2ec VA: 0x7594e452ec
	public Void OnClicked() { }
	// RVA: 0x282d38c VA: 0x7594e4538c
	public Void .ctor() { }
}
```