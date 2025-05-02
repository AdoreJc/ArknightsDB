# SandboxV2DineItemView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2ItemCard _itemCardPrefab`

- `Transform _itemCardHolder`

- `Single _itemCardScale`

- `Text _nameText`

- `Text _durationText`

- `Text _usageText`

- `Text _stockText`

- `SimpleLayoutContent _attributeContent`

- `GameObject _isLastDinedPanel`

- `CanvasGroup _selectedGroup`

- `Boolean m_hasInited`

- `SandboxV2ItemCard m_itemCard`

- `Adapter m_adapter`

- `UISwitchTween m_selectTween`

- `Int32 m_cachedIndex`


## Methods

- `Void set_itemSelectEvent(Action`1)`

- `Void OnItemSelectEvent()`

- `Void Render(Int32, SandboxV2DineItemModel, Boolean)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DineItemView : MonoBehaviour, IHotfixable
{
	private SandboxV2ItemCard _itemCardPrefab; // 0x18
	private Transform _itemCardHolder; // 0x20
	private Single _itemCardScale; // 0x28
	private Text _nameText; // 0x30
	private Text _durationText; // 0x38
	private Text _usageText; // 0x40
	private Text _stockText; // 0x48
	private SimpleLayoutContent _attributeContent; // 0x50
	private GameObject _isLastDinedPanel; // 0x58
	private CanvasGroup _selectedGroup; // 0x60
	private Boolean m_hasInited; // 0x68
	private SandboxV2ItemCard m_itemCard; // 0x70
	private Adapter m_adapter; // 0x78
	private UISwitchTween m_selectTween; // 0x80
	private Int32 m_cachedIndex; // 0x88
	private List`1 m_cachedAttributes; // 0x90
	private Action`1 <itemSelectEvent>k__BackingField; // 0x98
	private static DelegateBridge __Hotfix0_get_itemSelectEvent; // 0x0
	private static DelegateBridge __Hotfix0_set_itemSelectEvent; // 0x8
	private static DelegateBridge __Hotfix0_OnItemSelectEvent; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`1 itemSelectEvent { get; set; }

	// RVA: 0x250591c VA: 0x7594b1d91c
	private Action`1 get_itemSelectEvent() { }
	// RVA: 0x2505494 VA: 0x7594b1d494
	public Void set_itemSelectEvent(Action`1 value) { }
	// RVA: 0x2505984 VA: 0x7594b1d984
	public Void OnItemSelectEvent() { }
	// RVA: 0x2505518 VA: 0x7594b1d518
	public Void Render(Int32 index, SandboxV2DineItemModel model, Boolean initRender) { }
	// RVA: 0x2505a2c VA: 0x7594b1da2c
	private Void _InitIfNot() { }
	// RVA: 0x2505c78 VA: 0x7594b1dc78
	public Void .ctor() { }
}
```