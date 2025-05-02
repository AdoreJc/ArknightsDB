# UIGainItemFloatPanel

**Namespace:** `Torappu.UI`


## Fields

- `Text _titleText`

- `UIBlurFloatPanel _backImage`

- `SimpleLayoutContent _itemGridLayout`

- `Single _itemScaleFactor`

- `ScrollRect _itemScroll`

- `GridLayoutGroup _gridLayoutGroup`

- `VerticalLayoutGroup _verticalLayoutGroup`

- `RectTransform _topMask`

- `Transform _effectHolder`

- `Single _delayToShowEachItem`

- `Int32 _maxRowForEffect`

- `Int32 _maxRowForAnimation`

- `Int32 _topPaddingSingleRow`

- `Int32 _topPaddingMultiRows`

- `Boolean m_isInited`

- `Boolean m_isLayoutUpdating`

- `ItemAdapter m_itemAdapter`

- `Action <onHideRequested>k__BackingField`


## Properties

- `Action onHideRequested`

- `Boolean isRenderingFinished`

- `Int32 maxItemCntForEffect`

- `Int32 maxItemCntForAnimation`


## Methods

- `Action get_onHideRequested()`

- `Void set_onHideRequested(Action)`

- `Boolean get_isRenderingFinished()`

- `Void set_isRenderingFinished(Boolean)`

- `Int32 get_maxItemCntForEffect()`

- `Int32 get_maxItemCntForAnimation()`

- `Void EventOnConfirmClicked()`

- `Void EventOnBlankClicked()`

- `Void EventOnMaskClicked()`

- `Void Start()`

- `Void OnEnable()`

- `IEnumerator ShowCoroutine()`

- `Void RequestHide()`

- `IEnumerator HideCoroutine()`

- `Void Render(IList`1, Style)`

- `Void _InitIfNot()`

- `Void _UpdateAutoLayouts()`

- `IEnumerator _UpdateLayoutCoroutine()`

- `Void _OnItemListRenderFinished()`

- `Void _SetItemsModels(IList`1)`

- `Int32 _CompareItemModelWithSortId(UIItemViewModel, UIItemViewModel)`

- `Void _SetStyle(Style)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIGainItemFloatPanel : MonoBehaviour
{
	private Text _titleText; // 0x18
	private UIBlurFloatPanel _backImage; // 0x20
	private SimpleLayoutContent _itemGridLayout; // 0x28
	private Single _itemScaleFactor; // 0x30
	private RectTransform[] _autoLayouts; // 0x38
	private ScrollRect _itemScroll; // 0x40
	private GridLayoutGroup _gridLayoutGroup; // 0x48
	private VerticalLayoutGroup _verticalLayoutGroup; // 0x50
	private RectTransform _topMask; // 0x58
	private Transform _effectHolder; // 0x60
	private Single _delayToShowEachItem; // 0x68
	private Int32 _maxRowForEffect; // 0x6c
	private Int32 _maxRowForAnimation; // 0x70
	private Int32 _topPaddingSingleRow; // 0x74
	private Int32 _topPaddingMultiRows; // 0x78
	private List`1 m_itemModels; // 0x80
	private Boolean m_isInited; // 0x88
	private Boolean m_isLayoutUpdating; // 0x89
	private ItemAdapter m_itemAdapter; // 0x90
	private Action <onHideRequested>k__BackingField; // 0x98

	public Action onHideRequested { get; set; }
	private Boolean isRenderingFinished { get; set; }
	private Int32 maxItemCntForEffect { get; }
	private Int32 maxItemCntForAnimation { get; }

	// RVA: 0x221e500 VA: 0x7594836500
	public Action get_onHideRequested() { }
	// RVA: 0x221e508 VA: 0x7594836508
	public Void set_onHideRequested(Action value) { }
	// RVA: 0x221e510 VA: 0x7594836510
	private Boolean get_isRenderingFinished() { }
	// RVA: 0x221e544 VA: 0x7594836544
	private Void set_isRenderingFinished(Boolean value) { }
	// RVA: 0x221e574 VA: 0x7594836574
	private Int32 get_maxItemCntForEffect() { }
	// RVA: 0x221e5a4 VA: 0x75948365a4
	private Int32 get_maxItemCntForAnimation() { }
	// RVA: 0x221e5d4 VA: 0x75948365d4
	public Void EventOnConfirmClicked() { }
	// RVA: 0x221e614 VA: 0x7594836614
	public Void EventOnBlankClicked() { }
	// RVA: 0x221e618 VA: 0x7594836618
	public Void EventOnMaskClicked() { }
	// RVA: 0x221e734 VA: 0x7594836734
	protected Void Start() { }
	// RVA: 0x221e7f8 VA: 0x75948367f8
	protected Void OnEnable() { }
	// RVA: 0x221e8e4 VA: 0x75948368e4
	public IEnumerator ShowCoroutine() { }
	// RVA: 0x221e5d8 VA: 0x75948365d8
	public Void RequestHide() { }
	// RVA: 0x221e980 VA: 0x7594836980
	public IEnumerator HideCoroutine() { }
	// RVA: 0x221ea1c VA: 0x7594836a1c
	public Void Render(IList`1 itemModels, Style style) { }
	// RVA: 0x221eb48 VA: 0x7594836b48
	private Void _InitIfNot() { }
	// RVA: 0x221e808 VA: 0x7594836808
	private Void _UpdateAutoLayouts() { }
	// RVA: 0x221ef44 VA: 0x7594836f44
	private IEnumerator _UpdateLayoutCoroutine() { }
	// RVA: 0x221efe0 VA: 0x7594836fe0
	private Void _OnItemListRenderFinished() { }
	// RVA: 0x221ebe0 VA: 0x7594836be0
	private Void _SetItemsModels(IList`1 itemModels) { }
	// RVA: 0x221efe8 VA: 0x7594836fe8
	private Int32 _CompareItemModelWithSortId(UIItemViewModel lhs, UIItemViewModel rhs) { }
	// RVA: 0x221eaa8 VA: 0x7594836aa8
	private Void _SetStyle(Style style) { }
	// RVA: 0x221f040 VA: 0x7594837040
	public Void .ctor() { }
}
```