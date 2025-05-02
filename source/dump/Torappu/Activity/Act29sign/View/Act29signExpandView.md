# Act29signExpandView

**Namespace:** `Torappu.Activity.Act29sign.View`


## Fields

- `RectTransform _container`

- `GameObject _itemsContainer`

- `Single _containerMoveDistance`

- `Single _itemOccupyWidth`

- `Single _itemExpandWidth`

- `Single _duration`

- `Int32 m_expandItemIndex`

- `ExpandTween m_internalTween`

- `Boolean m_controlItemsVisible`

- `Boolean m_hasInited`

- `Model m_viewModel`

- `Single m_expansion`


## Properties

- `Single expansion`


## Methods

- `Single get_expansion()`

- `Void set_expansion(Single)`

- `Void Render(Model)`

- `Void _InitIfNot()`

- `Void _SetItemVisible(Boolean)`

- `Void _SetExpansionAndRender(Single)`

- `Void _SetX(RectTransform, Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act29sign.View
public class Act29signExpandView : MonoBehaviour, IHotfixable
{
	private RectTransform _container; // 0x18
	private RectTransform[] _itemList; // 0x20
	private GameObject _itemsContainer; // 0x28
	private Single _containerMoveDistance; // 0x30
	private Single _itemOccupyWidth; // 0x34
	private Single _itemExpandWidth; // 0x38
	private Single _duration; // 0x3c
	private Int32 m_expandItemIndex; // 0x40
	private ExpandTween m_internalTween; // 0x48
	private Boolean m_controlItemsVisible; // 0x50
	private Boolean m_hasInited; // 0x51
	private Model m_viewModel; // 0x54
	private Single m_expansion; // 0x64
	private static DelegateBridge __Hotfix0_get_expansion; // 0x0
	private static DelegateBridge __Hotfix0_set_expansion; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__SetItemVisible; // 0x20
	private static DelegateBridge __Hotfix0__SetExpansionAndRender; // 0x28
	private static DelegateBridge __Hotfix0__SetX; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	protected Single expansion { get; set; }

	// RVA: 0x325e714 VA: 0x7595876714
	protected Single get_expansion() { }
	// RVA: 0x325e77c VA: 0x759587677c
	protected Void set_expansion(Single value) { }
	// RVA: 0x325c074 VA: 0x7595874074
	public Void Render(Model model) { }
	// RVA: 0x325e9f0 VA: 0x75958769f0
	private Void _InitIfNot() { }
	// RVA: 0x325eb40 VA: 0x7595876b40
	private Void _SetItemVisible(Boolean visible) { }
	// RVA: 0x325e7fc VA: 0x75958767fc
	private Void _SetExpansionAndRender(Single expansion) { }
	// RVA: 0x325ebc4 VA: 0x7595876bc4
	private Void _SetX(RectTransform rectTransform, Single x) { }
	// RVA: 0x325ecbc VA: 0x7595876cbc
	public Void .ctor() { }
}
```