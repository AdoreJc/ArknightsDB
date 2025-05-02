# Act24sideMissionRewardView

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `UIBlurFloatPanel _floatPanel`

- `RectTransform _backBtn`

- `SimpleLayoutContent _itemGridLayout`

- `SimpleLayoutContent _actItemGridLayout`

- `Single _itemScaleFactor`

- `ScrollRect _itemScroll`

- `GridLayoutGroup _gridLayoutGroup`

- `VerticalLayoutGroup _verticalLayoutGroup`

- `RectTransform _topMask`

- `GameObject _normTitle`

- `GameObject _actTitle`

- `Transform _effectHolder`

- `Single _delayToShowEachItem`

- `Int32 _maxRowForEffect`

- `Int32 _maxRowForAnimation`

- `Int32 _topPaddingSingleRow`

- `Int32 _topPaddingMultiRows`

- `Int32 _topPaddingSingleNormItem`

- `Int32 _topPaddingSingleActItem`

- `Boolean m_isInited`

- `Boolean m_isLayoutUpdating`

- `NormalItemAdapter m_normalItemAdapter`

- `ActItemAdapter m_actItemAdapter`

- `ILoadAsset m_assetLoader`

- `String m_actId`

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

- `Void Render(Act24sideMissionRewardViewModel, ILoadAsset, String)`

- `Void _InitIfNot()`

- `Void _UpdateAutoLayouts()`

- `IEnumerator _UpdateLayoutCoroutine()`

- `Void _OnItemListRenderFinished()`

- `Void _SetItemsModels(IList`1, IList`1)`

- `Int32 _CompareItemModelWithSortId(UIItemViewModel, UIItemViewModel)`

- `Int32 _CompareItemModelWithSortId(Act24sideMeldingItemViewModel, Act24sideMeldingItemViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideMissionRewardView : MonoBehaviour, IHotfixable
{
	private UIBlurFloatPanel _floatPanel; // 0x18
	private RectTransform _backBtn; // 0x20
	private SimpleLayoutContent _itemGridLayout; // 0x28
	private SimpleLayoutContent _actItemGridLayout; // 0x30
	private Single _itemScaleFactor; // 0x38
	private RectTransform[] _autoLayouts; // 0x40
	private ScrollRect _itemScroll; // 0x48
	private GridLayoutGroup _gridLayoutGroup; // 0x50
	private VerticalLayoutGroup _verticalLayoutGroup; // 0x58
	private RectTransform _topMask; // 0x60
	private GameObject _normTitle; // 0x68
	private GameObject _actTitle; // 0x70
	private Transform _effectHolder; // 0x78
	private Single _delayToShowEachItem; // 0x80
	private Int32 _maxRowForEffect; // 0x84
	private Int32 _maxRowForAnimation; // 0x88
	private Int32 _topPaddingSingleRow; // 0x8c
	private Int32 _topPaddingMultiRows; // 0x90
	private Int32 _topPaddingSingleNormItem; // 0x94
	private Int32 _topPaddingSingleActItem; // 0x98
	private List`1 m_itemModels; // 0xa0
	private List`1 m_actItemModels; // 0xa8
	private Boolean m_isInited; // 0xb0
	private Boolean m_isLayoutUpdating; // 0xb1
	private NormalItemAdapter m_normalItemAdapter; // 0xb8
	private ActItemAdapter m_actItemAdapter; // 0xc0
	private ILoadAsset m_assetLoader; // 0xc8
	private String m_actId; // 0xd0
	private Action <onHideRequested>k__BackingField; // 0xd8
	private static DelegateBridge __Hotfix0_get_onHideRequested; // 0x0
	private static DelegateBridge __Hotfix0_set_onHideRequested; // 0x8
	private static DelegateBridge __Hotfix0_get_isRenderingFinished; // 0x10
	private static DelegateBridge __Hotfix0_set_isRenderingFinished; // 0x18
	private static DelegateBridge __Hotfix0_get_maxItemCntForEffect; // 0x20
	private static DelegateBridge __Hotfix0_get_maxItemCntForAnimation; // 0x28
	private static DelegateBridge __Hotfix0_EventOnConfirmClicked; // 0x30
	private static DelegateBridge __Hotfix0_EventOnBlankClicked; // 0x38
	private static DelegateBridge __Hotfix0_EventOnMaskClicked; // 0x40
	private static DelegateBridge __Hotfix0_Start; // 0x48
	private static DelegateBridge __Hotfix0_OnEnable; // 0x50
	private static DelegateBridge __Hotfix0_ShowCoroutine; // 0x58
	private static DelegateBridge __Hotfix0_RequestHide; // 0x60
	private static DelegateBridge __Hotfix0_HideCoroutine; // 0x68
	private static DelegateBridge __Hotfix0_Render; // 0x70
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x78
	private static DelegateBridge __Hotfix0__UpdateAutoLayouts; // 0x80
	private static DelegateBridge __Hotfix0__UpdateLayoutCoroutine; // 0x88
	private static DelegateBridge __Hotfix0__OnItemListRenderFinished; // 0x90
	private static DelegateBridge __Hotfix0__SetItemsModels; // 0x98
	private static DelegateBridge __Hotfix0__CompareItemModelWithSortId; // 0xa0
	private static DelegateBridge __Hotfix1__CompareItemModelWithSortId; // 0xa8
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb0

	public Action onHideRequested { get; set; }
	private Boolean isRenderingFinished { get; set; }
	private Int32 maxItemCntForEffect { get; }
	private Int32 maxItemCntForAnimation { get; }

	// RVA: 0x32bae04 VA: 0x75958d2e04
	public Action get_onHideRequested() { }
	// RVA: 0x32ba1fc VA: 0x75958d21fc
	public Void set_onHideRequested(Action value) { }
	// RVA: 0x32bae6c VA: 0x75958d2e6c
	private Boolean get_isRenderingFinished() { }
	// RVA: 0x32baef8 VA: 0x75958d2ef8
	private Void set_isRenderingFinished(Boolean value) { }
	// RVA: 0x32baf90 VA: 0x75958d2f90
	private Int32 get_maxItemCntForEffect() { }
	// RVA: 0x32bb018 VA: 0x75958d3018
	private Int32 get_maxItemCntForAnimation() { }
	// RVA: 0x32bb0a0 VA: 0x75958d30a0
	public Void EventOnConfirmClicked() { }
	// RVA: 0x32bb1b8 VA: 0x75958d31b8
	public Void EventOnBlankClicked() { }
	// RVA: 0x32bb220 VA: 0x75958d3220
	public Void EventOnMaskClicked() { }
	// RVA: 0x32bb3a0 VA: 0x75958d33a0
	protected Void Start() { }
	// RVA: 0x32bb4a0 VA: 0x75958d34a0
	protected Void OnEnable() { }
	// RVA: 0x32bab38 VA: 0x75958d2b38
	public IEnumerator ShowCoroutine() { }
	// RVA: 0x32bb108 VA: 0x75958d3108
	public Void RequestHide() { }
	// RVA: 0x32bad08 VA: 0x75958d2d08
	public IEnumerator HideCoroutine() { }
	// RVA: 0x32ba940 VA: 0x75958d2940
	public Void Render(Act24sideMissionRewardViewModel model, ILoadAsset assetLoader, String actId) { }
	// RVA: 0x32bb6d0 VA: 0x75958d36d0
	private Void _InitIfNot() { }
	// RVA: 0x32bb51c VA: 0x75958d351c
	private Void _UpdateAutoLayouts() { }
	// RVA: 0x32bbec0 VA: 0x75958d3ec0
	private IEnumerator _UpdateLayoutCoroutine() { }
	// RVA: 0x32bbf94 VA: 0x75958d3f94
	private Void _OnItemListRenderFinished() { }
	// RVA: 0x32bb7f4 VA: 0x75958d37f4
	private Void _SetItemsModels(IList`1 itemModels, IList`1 actItemModels) { }
	// RVA: 0x32bc000 VA: 0x75958d4000
	private Int32 _CompareItemModelWithSortId(UIItemViewModel lhs, UIItemViewModel rhs) { }
	// RVA: 0x32bc0c0 VA: 0x75958d40c0
	private Int32 _CompareItemModelWithSortId(Act24sideMeldingItemViewModel lhs, Act24sideMeldingItemViewModel rhs) { }
	// RVA: 0x32bc180 VA: 0x75958d4180
	public Void .ctor() { }
}
```