# ItemRepoIssueVoucherItemView

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `RectTransform _itemCardContainer`

- `GameObject _selectedDownPanel`

- `GameObject _selectedUpPanel`

- `Text _selectedCountText`

- `UILongPressButtonEx _deselectButton`

- `GameObject _possessPanel`

- `Text _possessText`

- `GameObject _outputPanel`

- `Text _outputCountText`

- `Single m_itemCardScale`

- `Int32 m_longPressCount`

- `Boolean m_hasInited`

- `UIItemCard m_itemCard`

- `Int32 m_cachedIndex`

- `UIStateFinder m_finder`


## Methods

- `Void set_onSelectItem(Func`3)`

- `Void Render(Int32, ItemRepoIssueVoucherItemViewModel, Boolean)`

- `Void _InitIfNot()`

- `Void _SelectItem(Int32)`

- `Boolean _SelectItemLongPress(Int32)`

- `Void _DeselectItem()`

- `Boolean _DeselectItemLongPress()`

- `Void _ShowItemDesc(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoIssueVoucherItemView : MonoBehaviour, IHotfixable
{
	private RectTransform _itemCardContainer; // 0x18
	private GameObject _selectedDownPanel; // 0x20
	private GameObject _selectedUpPanel; // 0x28
	private Text _selectedCountText; // 0x30
	private UILongPressButtonEx _deselectButton; // 0x38
	private GameObject _possessPanel; // 0x40
	private Text _possessText; // 0x48
	private GameObject _outputPanel; // 0x50
	private Text _outputCountText; // 0x58
	private Single m_itemCardScale; // 0x60
	private Int32 m_longPressCount; // 0x64
	private Boolean m_hasInited; // 0x68
	private UIItemCard m_itemCard; // 0x70
	private Int32 m_cachedIndex; // 0x78
	private UIStateFinder m_finder; // 0x80
	private Func`3 <onSelectItem>k__BackingField; // 0x90
	private static DelegateBridge __Hotfix0_get_onSelectItem; // 0x0
	private static DelegateBridge __Hotfix0_set_onSelectItem; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__SelectItem; // 0x20
	private static DelegateBridge __Hotfix0__SelectItemLongPress; // 0x28
	private static DelegateBridge __Hotfix0__DeselectItem; // 0x30
	private static DelegateBridge __Hotfix0__DeselectItemLongPress; // 0x38
	private static DelegateBridge __Hotfix0__ShowItemDesc; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	private Func`3 onSelectItem { get; set; }

	// RVA: 0x2d33d94 VA: 0x759534bd94
	private Func`3 get_onSelectItem() { }
	// RVA: 0x2d33868 VA: 0x759534b868
	public Void set_onSelectItem(Func`3 value) { }
	// RVA: 0x2d338ec VA: 0x759534b8ec
	public Void Render(Int32 index, ItemRepoIssueVoucherItemViewModel viewModel, Boolean selectable) { }
	// RVA: 0x2d33dfc VA: 0x759534bdfc
	private Void _InitIfNot() { }
	// RVA: 0x2d3403c VA: 0x759534c03c
	private Void _SelectItem(Int32 index) { }
	// RVA: 0x2d34188 VA: 0x759534c188
	private Boolean _SelectItemLongPress(Int32 index) { }
	// RVA: 0x2d342d4 VA: 0x759534c2d4
	private Void _DeselectItem() { }
	// RVA: 0x2d34378 VA: 0x759534c378
	private Boolean _DeselectItemLongPress() { }
	// RVA: 0x2d34420 VA: 0x759534c420
	private Void _ShowItemDesc(Int32 _) { }
	// RVA: 0x2d34528 VA: 0x759534c528
	public Void .ctor() { }
}
```