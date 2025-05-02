# ItemRepoOptionalVoucherView

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `Image _imgDec`

- `CanvasGroup _canvasPartChoose`

- `Image _imgChooseConfirmBg`

- `Image _imgChooseConfirmIcon`

- `ItemRepoOptionalVoucherChooseListAdapter m_chooseListAdapter`

- `Text _txtChoseCount`

- `CanvasGroup _canvasPartOutput`

- `RectTransform _transOutputListParent`

- `SimpleLayoutContent _outputItemList`

- `Text _txtTips`

- `Transform _originItemCardContainer`

- `Single _originItemScale`

- `Action onOutputConfirmClickEvent`

- `Action onChooseConfirmClickEvent`

- `Action onOutputCancelClickEvent`

- `Boolean m_hasInited`

- `ItemRepoOptionalVoucherViewModel m_viewModel`

- `FadeSwitchTween m_tweenChoosePartShow`

- `FadeSwitchTween m_tweenOutputPartShow`

- `UIItemCard m_originItemCard`

- `OutputItemListAdapter m_outputListAdapter`

- `String m_cachedVoucherId`

- `Int32 m_cachedOutputItemCounts`


## Methods

- `Void _Render()`

- `Void OnChooseConfirmClick()`

- `Void OnOutputCancelClick()`

- `Void OnOutputConfirmClick()`

- `Void _RenderChoosePart()`

- `Void _RenderOutputPart(UIItemViewModel)`

- `Void _InitIfNot()`

- `Void _InitTweenPart()`

- `Void _InitOriginItemPart()`

- `Void _OnOriginItemClicked(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoOptionalVoucherView : DataBinder`1
{
	private Image _imgDec; // 0x20
	private CanvasGroup _canvasPartChoose; // 0x28
	private Image _imgChooseConfirmBg; // 0x30
	private Image _imgChooseConfirmIcon; // 0x38
	private ItemRepoOptionalVoucherChooseListAdapter m_chooseListAdapter; // 0x40
	private Text _txtChoseCount; // 0x48
	private CanvasGroup _canvasPartOutput; // 0x50
	private RectTransform _transOutputListParent; // 0x58
	private SimpleLayoutContent _outputItemList; // 0x60
	private Text _txtTips; // 0x68
	private Transform _originItemCardContainer; // 0x70
	private Single _originItemScale; // 0x78
	public Action onOutputConfirmClickEvent; // 0x80
	public Action onChooseConfirmClickEvent; // 0x88
	public Action onOutputCancelClickEvent; // 0x90
	private Boolean m_hasInited; // 0x98
	private ItemRepoOptionalVoucherViewModel m_viewModel; // 0xa0
	private FadeSwitchTween m_tweenChoosePartShow; // 0xa8
	private FadeSwitchTween m_tweenOutputPartShow; // 0xb0
	private UIItemCard m_originItemCard; // 0xb8
	private OutputItemListAdapter m_outputListAdapter; // 0xc0
	private String m_cachedVoucherId; // 0xc8
	private Int32 m_cachedOutputItemCounts; // 0xd0
	private const Single TWEEN_DUR; // 0x0
	private static readonly Color HALF_ALPHA_COL; // 0x0
	private const String STR_CHOOSE_COUNT; // 0x0
	private const Int32 OUT_PUT_LEFT_LIMIT_COUNT; // 0x0
	private static readonly Vector2 OUT_PUT_LEFT_VECTOR2; // 0x10
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x18
	private static DelegateBridge __Hotfix0__Render; // 0x20
	private static DelegateBridge __Hotfix0_OnChooseConfirmClick; // 0x28
	private static DelegateBridge __Hotfix0_OnOutputCancelClick; // 0x30
	private static DelegateBridge __Hotfix0_OnOutputConfirmClick; // 0x38
	private static DelegateBridge __Hotfix0__RenderChoosePart; // 0x40
	private static DelegateBridge __Hotfix0__RenderOutputPart; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x50
	private static DelegateBridge __Hotfix0__InitTweenPart; // 0x58
	private static DelegateBridge __Hotfix0__InitOriginItemPart; // 0x60
	private static DelegateBridge __Hotfix0__OnOriginItemClicked; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70


	// RVA: 0x2d36a1c VA: 0x759534ea1c
	public override Void OnValueChanged(ItemRepoOptionalVoucherViewProperty property) { }
	// RVA: 0x2d36ae8 VA: 0x759534eae8
	private Void _Render() { }
	// RVA: 0x2d372bc VA: 0x759534f2bc
	public Void OnChooseConfirmClick() { }
	// RVA: 0x2d373ac VA: 0x759534f3ac
	public Void OnOutputCancelClick() { }
	// RVA: 0x2d37440 VA: 0x759534f440
	public Void OnOutputConfirmClick() { }
	// RVA: 0x2d36df8 VA: 0x759534edf8
	private Void _RenderChoosePart() { }
	// RVA: 0x2d37030 VA: 0x759534f030
	private Void _RenderOutputPart(UIItemViewModel originItemModel) { }
	// RVA: 0x2d36d04 VA: 0x759534ed04
	private Void _InitIfNot() { }
	// RVA: 0x2d37574 VA: 0x759534f574
	private Void _InitTweenPart() { }
	// RVA: 0x2d376b8 VA: 0x759534f6b8
	private Void _InitOriginItemPart() { }
	// RVA: 0x2d378f4 VA: 0x759534f8f4
	private Void _OnOriginItemClicked(Int32 index) { }
	// RVA: 0x2d37a0c VA: 0x759534fa0c
	public Void .ctor() { }
	// RVA: 0x2d37ab8 VA: 0x759534fab8
	private static Void .cctor() { }
}
```