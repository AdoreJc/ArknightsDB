# RoguelikeTopicBattlePassPurchaseView

**Namespace:** `Torappu.UI.RoguelikeTopic`


## Fields

- `RoguelikeTopicBattlePassPurchaseWheelPickerView _wheelPickerView`

- `Text _textCurr`

- `Text _textTarget`

- `Text _textCount`

- `Text _tokenCount`

- `SimpleLayoutContent _grandPrizeGroup`

- `HorizontalLayoutGroup _layout`

- `ScrollRect _scrollView`

- `Single _focusOffsetLeft`

- `Single _focusOffsetRight`

- `Single _focusDuration`

- `Int32 _grandPrizeItemWidth`

- `UIAtlasImage _iconRight`

- `UIColorGraphic _styleColorGraphicDark`

- `UIColorGraphic _styleColorGraphic`

- `UIColorGraphic _styleBtnText`

- `Action onWheelBeginScroll`

- `Action onWheelBeginDrag`

- `Boolean m_isInited`

- `Adapter m_adapter`

- `Int64 m_cachedWidgetId`

- `Int32 m_cachedSelectedIndex`

- `RoguelikeTopicBattlePassPurchaseViewModel m_cachedModel`

- `UILayoutDimensionListener m_dimensionListener`

- `Boolean m_layoutCompleted`

- `Tween m_scrollTween`

- `RoguelikeTopicBattlePassStyle m_style`


## Methods

- `Void _InitIfNot()`

- `Void Init(RoguelikeTopicBattlePassStyle)`

- `Void _RenderOnSelectedIndexChanged(RoguelikeTopicBattlePassPurchaseViewModel)`

- `Void _OnWheelBeginScroll()`

- `Void _OnWheelBeginDrag()`

- `Void _OnWheelUpdateIndex(Int32)`

- `Void _OnWheelScrollEnd(Int32)`

- `Void _OnPostLayout()`

- `Void _FocusOnSelectedGrandPrize()`

- `Void <_FocusOnSelectedGrandPrize>b__40_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic
public class RoguelikeTopicBattlePassPurchaseView : DataBinder`1
{
	private RoguelikeTopicBattlePassPurchaseWheelPickerView _wheelPickerView; // 0x20
	private Text _textCurr; // 0x28
	private Text _textTarget; // 0x30
	private Text _textCount; // 0x38
	private Text _tokenCount; // 0x40
	private SimpleLayoutContent _grandPrizeGroup; // 0x48
	private HorizontalLayoutGroup _layout; // 0x50
	private ScrollRect _scrollView; // 0x58
	private Single _focusOffsetLeft; // 0x60
	private Single _focusOffsetRight; // 0x64
	private Single _focusDuration; // 0x68
	private Int32 _grandPrizeItemWidth; // 0x6c
	private UIAtlasImage _iconRight; // 0x70
	private UIColorGraphic _styleColorGraphicDark; // 0x78
	private UIColorGraphic _styleColorGraphic; // 0x80
	private UIColorGraphic _styleBtnText; // 0x88
	public Action onWheelBeginScroll; // 0x90
	public Action onWheelBeginDrag; // 0x98
	public Action`1 onWheelUpdateIndex; // 0xa0
	public Action`1 onWheelScrollEnd; // 0xa8
	public Action`1 onGrandPrizeBtnClicked; // 0xb0
	private Boolean m_isInited; // 0xb8
	private Adapter m_adapter; // 0xc0
	private Int64 m_cachedWidgetId; // 0xc8
	private Int32 m_cachedSelectedIndex; // 0xd0
	private RoguelikeTopicBattlePassPurchaseViewModel m_cachedModel; // 0xd8
	private UILayoutDimensionListener m_dimensionListener; // 0xe0
	private Boolean m_layoutCompleted; // 0xe8
	private Tween m_scrollTween; // 0xf0
	private RoguelikeTopicBattlePassStyle m_style; // 0xf8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge __Hotfix0__RenderOnSelectedIndexChanged; // 0x18
	private static DelegateBridge __Hotfix0__OnWheelBeginScroll; // 0x20
	private static DelegateBridge __Hotfix0__OnWheelBeginDrag; // 0x28
	private static DelegateBridge __Hotfix0__OnWheelUpdateIndex; // 0x30
	private static DelegateBridge __Hotfix0__OnWheelScrollEnd; // 0x38
	private static DelegateBridge __Hotfix0__OnPostLayout; // 0x40
	private static DelegateBridge __Hotfix0__FocusOnSelectedGrandPrize; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50


	// RVA: 0x263d5d0 VA: 0x7594c555d0
	private Void _InitIfNot() { }
	// RVA: 0x263be6c VA: 0x7594c53e6c
	public Void Init(RoguelikeTopicBattlePassStyle style) { }
	// RVA: 0x263da40 VA: 0x7594c55a40
	public override Void OnValueChanged(RoguelikeTopicBattlePassPurchaseProperty property) { }
	// RVA: 0x263dc8c VA: 0x7594c55c8c
	private Void _RenderOnSelectedIndexChanged(RoguelikeTopicBattlePassPurchaseViewModel viewModel) { }
	// RVA: 0x263e270 VA: 0x7594c56270
	private Void _OnWheelBeginScroll() { }
	// RVA: 0x263e2f4 VA: 0x7594c562f4
	private Void _OnWheelBeginDrag() { }
	// RVA: 0x263e378 VA: 0x7594c56378
	private Void _OnWheelUpdateIndex(Int32 index) { }
	// RVA: 0x263e418 VA: 0x7594c56418
	private Void _OnWheelScrollEnd(Int32 index) { }
	// RVA: 0x263e4b8 VA: 0x7594c564b8
	private Void _OnPostLayout() { }
	// RVA: 0x263de2c VA: 0x7594c55e2c
	private Void _FocusOnSelectedGrandPrize() { }
	// RVA: 0x263e600 VA: 0x7594c56600
	public Void .ctor() { }
	// RVA: 0x263e6b0 VA: 0x7594c566b0
	private Void <_FocusOnSelectedGrandPrize>b__40_0() { }
}
```