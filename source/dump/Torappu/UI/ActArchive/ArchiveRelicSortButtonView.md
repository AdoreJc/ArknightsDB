# ArchiveRelicSortButtonView

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `GameObject _panelSelected`

- `GameObject _panelUnselected`

- `Text _textRule`

- `Text _textNew`

- `GameObject _btnView`

- `Button _btn`

- `FilterRule _filterRule`

- `Color _selectedTextColor`

- `Color _unSelectedTextColor`

- `ArchiveRelicController <controller>k__BackingField`


## Properties

- `ArchiveRelicController controller`


## Methods

- `ArchiveRelicController get_controller()`

- `Void set_controller(ArchiveRelicController)`

- `Void OnBtnClicked()`

- `Void Render(ArchiveRelicController, FilterRule, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveRelicSortButtonView : MonoBehaviour, IHotfixable
{
	private GameObject _panelSelected; // 0x18
	private GameObject _panelUnselected; // 0x20
	private Text _textRule; // 0x28
	private Text _textNew; // 0x30
	private GameObject _btnView; // 0x38
	private Button _btn; // 0x40
	private FilterRule _filterRule; // 0x48
	private Color _selectedTextColor; // 0x4c
	private Color _unSelectedTextColor; // 0x5c
	private ArchiveRelicController <controller>k__BackingField; // 0x70
	private static DelegateBridge __Hotfix0_get_controller; // 0x0
	private static DelegateBridge __Hotfix0_set_controller; // 0x8
	private static DelegateBridge __Hotfix0_OnBtnClicked; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private ArchiveRelicController controller { get; set; }

	// RVA: 0x307dfa8 VA: 0x7595695fa8
	private ArchiveRelicController get_controller() { }
	// RVA: 0x307e010 VA: 0x7595696010
	public Void set_controller(ArchiveRelicController value) { }
	// RVA: 0x307e094 VA: 0x7595696094
	public Void OnBtnClicked() { }
	// RVA: 0x3078b60 VA: 0x7595690b60
	public Void Render(ArchiveRelicController controller, FilterRule selectedFilterRule, Int32 newNum) { }
	// RVA: 0x307e160 VA: 0x7595696160
	public Void .ctor() { }
}
```