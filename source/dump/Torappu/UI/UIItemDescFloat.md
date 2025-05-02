# UIItemDescFloat

**Namespace:** `Torappu.UI`


## Fields

- `RectTransform _panelLocal`

- `RectTransform _panelDescText`

- `RectTransform _panelItemCardContainer`

- `GameObject _raycastBlocker`

- `Single _paddingX`

- `Text _textTitle`

- `Text _textUsage`

- `Text _textDesc`

- `GameObject _countPart`

- `Text _textCount`

- `RectTransform _content`

- `RectTransform _backGround`

- `Single _backGroundDeltaY`

- `Single _packInfoMaxY`

- `Single _dropInfoMaxY`

- `Transform _packInfoContainer`

- `Transform _dropInfoContainer`

- `RectTransform _secondaryInfoPanel`

- `CancelDragIfFits _cancelContentDrag`

- `CanvasGroup _contentAlphaHandler`

- `CanvasGroup _contentSwitch`

- `RectTransform m_panelDescTextBound`

- `Action m_closePanelRequestImpl`

- `Single m_itemCardScaling`

- `TargetPosCalculator m_calcTargetPos`

- `Boolean m_dropInfoInitFlag`

- `ItemRepoDropInfoView m_dropItemInfo`

- `ItemRepoItemPackContentView m_itemPackContent`

- `ContentAlphaHandler m_contentAlphaHandler`

- `Action <onRouteToDropInfo>k__BackingField`

- `GameObject m_itemCardCache`

- `UIItemViewModel m_itemModelCache`

- `GameObject m_itemCardShadow`

- `Vector2 m_itemInitPos`

- `UIItemDescViewModel m_pendDataChange`

- `Boolean m_isInited`

- `Boolean m_isTransiting`


## Properties

- `RectTransform panelDescTextBound`

- `Action onRouteToDropInfo`

- `GameObject itemCardShadow`


## Methods

- `ContentAlphaHandler _EnsureContentAlpha()`

- `Void set_panelDescTextBound(RectTransform)`

- `Void set_closePanelRequest(Action`1)`

- `Action get_onRouteToDropInfo()`

- `Void set_onRouteToDropInfo(Action)`

- `GameObject get_itemCardShadow()`

- `Void set_itemCardShadow(GameObject)`

- `Void Render(UIItemDescViewModel, Single)`

- `Void FixedUpdate()`

- `Boolean _CheckIfTargetInvalid()`

- `Void _OnPanelHide()`

- `Void _OnPanelShow()`

- `Void _RequestToClosePanel(Boolean)`

- `Void _OnRouteToStageDropInfo(RouteTarget)`

- `Void _OnRouteToRoomInfo(RoomType, ItemBundle)`

- `Void _OnRouteToVoucherRelationInfo(ConsumableInfo, ItemType, VoucherRouteFocus)`

- `Void EventOnBlankClick()`

- `Void RegisterFocusItem(GameObject, UIItemViewModel)`

- `CanvasGroup ExportAlphaHandler()`

- `Void _InitIfNot()`

- `Boolean _IsPanelShown()`

- `IEnumerator _UpdateTransitionCoroutine(UIItemDescViewModel)`

- `IEnumerator _ShowPanelCorotuine(UIItemDescViewModel)`

- `IEnumerator _HidePanelCoroutine()`

- `Void _UpdateContent(UIItemDescViewModel)`

- `Void _UpdateItemDropInfo(UIItemViewModel, UIItemDescViewModel)`

- `Void _DestroyViews(IDictionary`2)`

- `IEnumerator _UpdateLayout()`

- `Void _StartDataUpdateTransition(UIItemDescViewModel)`

- `Void RouteToVoucherRelationInfo(ConsumableInfo, ItemType, VoucherRouteFocus)`

- `Void OpenMaterialPage(Param)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIItemDescFloat : PageSingleComponent
{
	public const Single TWEEN_DURATION; // 0x0
	private const Single POS_CHANGE_DIS; // 0x0
	private static readonly ListSet`1 DONT_SHOW_COUNT_ITEM_TYPES; // 0x0
	private RectTransform _panelLocal; // 0x20
	private RectTransform _panelDescText; // 0x28
	private RectTransform _panelItemCardContainer; // 0x30
	private GameObject _raycastBlocker; // 0x38
	private Single _paddingX; // 0x40
	private Text _textTitle; // 0x48
	private Text _textUsage; // 0x50
	private Text _textDesc; // 0x58
	private GameObject _countPart; // 0x60
	private Text _textCount; // 0x68
	private RectTransform _content; // 0x70
	private RectTransform _backGround; // 0x78
	private Single _backGroundDeltaY; // 0x80
	private Single _packInfoMaxY; // 0x84
	private Single _dropInfoMaxY; // 0x88
	private Transform _packInfoContainer; // 0x90
	private Transform _dropInfoContainer; // 0x98
	private RectTransform _secondaryInfoPanel; // 0xa0
	private CancelDragIfFits _cancelContentDrag; // 0xa8
	private CanvasGroup _contentAlphaHandler; // 0xb0
	private CanvasGroup _contentSwitch; // 0xb8
	private RectTransform m_panelDescTextBound; // 0xc0
	private Action m_closePanelRequestImpl; // 0xc8
	private Action`1 m_closePanelRequest; // 0xd0
	private Single m_itemCardScaling; // 0xd8
	private TargetPosCalculator m_calcTargetPos; // 0xe0
	private ListDict`2 m_zoneDropList; // 0xe8
	private ListDict`2 m_stageDropList; // 0xf0
	private ListDict`2 m_buildingProductList; // 0xf8
	private List`1 m_campaignStages; // 0x100
	private Boolean m_dropInfoInitFlag; // 0x108
	private ItemRepoDropInfoView m_dropItemInfo; // 0x110
	private ItemRepoItemPackContentView m_itemPackContent; // 0x118
	private ContentAlphaHandler m_contentAlphaHandler; // 0x120
	private Action <onRouteToDropInfo>k__BackingField; // 0x128
	private GameObject m_itemCardCache; // 0x130
	private UIItemViewModel m_itemModelCache; // 0x138
	private GameObject m_itemCardShadow; // 0x140
	private Vector2 m_itemInitPos; // 0x148
	private UIItemDescViewModel m_pendDataChange; // 0x150
	private Boolean m_isInited; // 0x158
	private Boolean m_isTransiting; // 0x159
	private static DelegateBridge __Hotfix0__EnsureContentAlpha; // 0x8
	private static DelegateBridge __Hotfix0_set_panelDescTextBound; // 0x10
	private static DelegateBridge __Hotfix0_set_closePanelRequest; // 0x18
	private static DelegateBridge __Hotfix0_get_onRouteToDropInfo; // 0x20
	private static DelegateBridge __Hotfix0_set_onRouteToDropInfo; // 0x28
	private static DelegateBridge __Hotfix0_get_itemCardShadow; // 0x30
	private static DelegateBridge __Hotfix0_set_itemCardShadow; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x40
	private static DelegateBridge __Hotfix0_FixedUpdate; // 0x48
	private static DelegateBridge __Hotfix0__CheckIfTargetInvalid; // 0x50
	private static DelegateBridge __Hotfix0__OnPanelHide; // 0x58
	private static DelegateBridge __Hotfix0__OnPanelShow; // 0x60
	private static DelegateBridge __Hotfix0__RequestToClosePanel; // 0x68
	private static DelegateBridge __Hotfix0__OnRouteToStageDropInfo; // 0x70
	private static DelegateBridge __Hotfix0__OnRouteToRoomInfo; // 0x78
	private static DelegateBridge __Hotfix0__OnRouteToVoucherRelationInfo; // 0x80
	private static DelegateBridge __Hotfix0_EventOnBlankClick; // 0x88
	private static DelegateBridge __Hotfix0_RegisterFocusItemStatic; // 0x90
	private static DelegateBridge __Hotfix0_RegisterFocusItem; // 0x98
	private static DelegateBridge __Hotfix0_ExportAlphaHandler; // 0xa0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0xa8
	private static DelegateBridge __Hotfix0__IsPanelShown; // 0xb0
	private static DelegateBridge __Hotfix0__UpdateTransitionCoroutine; // 0xb8
	private static DelegateBridge __Hotfix0__ShowPanelCorotuine; // 0xc0
	private static DelegateBridge __Hotfix0__HidePanelCoroutine; // 0xc8
	private static DelegateBridge __Hotfix0__UpdateContent; // 0xd0
	private static DelegateBridge __Hotfix0_UpdateItemPackContent; // 0xd8
	private static DelegateBridge __Hotfix0__TryInstantiatePackContentView; // 0xe0
	private static DelegateBridge __Hotfix0__UpdateItemDropInfo; // 0xe8
	private static DelegateBridge __Hotfix0__DestroyViews; // 0xf0
	private static DelegateBridge __Hotfix0__UpdateLayout; // 0xf8
	private static DelegateBridge __Hotfix0__CheckIfTargetPosChanged; // 0x100
	private static DelegateBridge __Hotfix0__StartDataUpdateTransition; // 0x108
	private static DelegateBridge __Hotfix0_RouteToStageDropInfo; // 0x110
	private static DelegateBridge __Hotfix0_RouteToRoomInfo; // 0x118
	private static DelegateBridge __Hotfix0_RouteToVoucherRelationInfo; // 0x120
	private static DelegateBridge __Hotfix0_OpenMaterialPage; // 0x128
	private static DelegateBridge _c__Hotfix0_ctor; // 0x130

	public RectTransform panelDescTextBound { set; }
	public Action`1 closePanelRequest { set; }
	private Action onRouteToDropInfo { get; set; }
	protected GameObject itemCardShadow { get; set; }

	// RVA: 0x218cbc4 VA: 0x75947a4bc4
	private ContentAlphaHandler _EnsureContentAlpha() { }
	// RVA: 0x218c294 VA: 0x75947a4294
	public Void set_panelDescTextBound(RectTransform value) { }
	// RVA: 0x218c328 VA: 0x75947a4328
	public Void set_closePanelRequest(Action`1 value) { }
	// RVA: 0x218cd88 VA: 0x75947a4d88
	private Action get_onRouteToDropInfo() { }
	// RVA: 0x218c3bc VA: 0x75947a43bc
	public Void set_onRouteToDropInfo(Action value) { }
	// RVA: 0x218ce00 VA: 0x75947a4e00
	protected GameObject get_itemCardShadow() { }
	// RVA: 0x218ce78 VA: 0x75947a4e78
	protected Void set_itemCardShadow(GameObject value) { }
	// RVA: 0x218c7e0 VA: 0x75947a47e0
	public Void Render(UIItemDescViewModel viewModel, Single scaling) { }
	// RVA: 0x218d314 VA: 0x75947a5314
	private Void FixedUpdate() { }
	// RVA: 0x218d438 VA: 0x75947a5438
	private Boolean _CheckIfTargetInvalid() { }
	// RVA: 0x218d9d4 VA: 0x75947a59d4
	private Void _OnPanelHide() { }
	// RVA: 0x218db84 VA: 0x75947a5b84
	private Void _OnPanelShow() { }
	// RVA: 0x218d5a8 VA: 0x75947a55a8
	private Void _RequestToClosePanel(Boolean isTargetValid) { }
	// RVA: 0x218dc68 VA: 0x75947a5c68
	private Void _OnRouteToStageDropInfo(RouteTarget target) { }
	// RVA: 0x218de90 VA: 0x75947a5e90
	private Void _OnRouteToRoomInfo(RoomType roomType, ItemBundle item) { }
	// RVA: 0x218e078 VA: 0x75947a6078
	private Void _OnRouteToVoucherRelationInfo(ConsumableInfo voucherInfo, ItemType voucherType, VoucherRouteFocus focus) { }
	// RVA: 0x218e2c0 VA: 0x75947a62c0
	public Void EventOnBlankClick() { }
	// RVA: 0x218e33c VA: 0x75947a633c
	public static Void RegisterFocusItemStatic(GameObject itemCard, UIItemViewModel itemModel) { }
	// RVA: 0x218c734 VA: 0x75947a4734
	public Void RegisterFocusItem(GameObject itemCard, UIItemViewModel itemModel) { }
	// RVA: 0x218c590 VA: 0x75947a4590
	public CanvasGroup ExportAlphaHandler() { }
	// RVA: 0x218d140 VA: 0x75947a5140
	private Void _InitIfNot() { }
	// RVA: 0x218d3b4 VA: 0x75947a53b4
	private Boolean _IsPanelShown() { }
	// RVA: 0x218e4b0 VA: 0x75947a64b0
	private IEnumerator _UpdateTransitionCoroutine(UIItemDescViewModel viewModel) { }
	// RVA: 0x218e5b8 VA: 0x75947a65b8
	private IEnumerator _ShowPanelCorotuine(UIItemDescViewModel viewModel) { }
	// RVA: 0x218e6c0 VA: 0x75947a66c0
	private IEnumerator _HidePanelCoroutine() { }
	// RVA: 0x218e7a4 VA: 0x75947a67a4
	private Void _UpdateContent(UIItemDescViewModel descModel) { }
	// RVA: 0x218ea18 VA: 0x75947a6a18
	public static Void UpdateItemPackContent(UIItemViewModel itemModel, Transform packInfoContainer, ref ItemRepoItemPackContentView contentView) { }
	// RVA: 0x218ee90 VA: 0x75947a6e90
	private static Void _TryInstantiatePackContentView(Transform packInfoContainer, ref ItemRepoItemPackContentView contentView) { }
	// RVA: 0x218eb9c VA: 0x75947a6b9c
	private Void _UpdateItemDropInfo(UIItemViewModel itemModel, UIItemDescViewModel descModel) { }
	// RVA: 0x VA: 0x0
	private Void _DestroyViews(IDictionary`2 views) { }
	// RVA: 0x218f024 VA: 0x75947a7024
	private IEnumerator _UpdateLayout() { }
	// RVA: 0x218d8f8 VA: 0x75947a58f8
	private static Boolean _CheckIfTargetPosChanged(Vector2 initPos, Vector2 targetPos) { }
	// RVA: 0x218d1d4 VA: 0x75947a51d4
	private Void _StartDataUpdateTransition(UIItemDescViewModel viewModel) { }
	// RVA: 0x218dd68 VA: 0x75947a5d68
	public static Void RouteToStageDropInfo(RouteTarget target) { }
	// RVA: 0x218df68 VA: 0x75947a5f68
	public static Void RouteToRoomInfo(RoomType roomType, ItemBundle targetItem) { }
	// RVA: 0x218e188 VA: 0x75947a6188
	public Void RouteToVoucherRelationInfo(ConsumableInfo voucherInfo, ItemType voucherType, VoucherRouteFocus focus) { }
	// RVA: 0x218f108 VA: 0x75947a7108
	public Void OpenMaterialPage(Param param) { }
	// RVA: 0x218f1e0 VA: 0x75947a71e0
	public Void .ctor() { }
	// RVA: 0x218f454 VA: 0x75947a7454
	private static Void .cctor() { }
}
```