# Main11RecordNoteView

**Namespace:** `Torappu.UI.Stage.ZoneRecord.Main11`


## Fields

- `Main11RecordNoteContentView _contentView`

- `CanvasGroup _canvasContent`

- `SimpleLayoutContent _dotsLayout`

- `GameObject _objPrevBtn`

- `GameObject _objNextBtn`

- `CanvasGroup _canvasPrevBtn`

- `CanvasGroup _canvasNextBtn`

- `CanvasGroup _canvasBtnPrevGlow`

- `CanvasGroup _canvasBtnNextGlow`

- `RectTransform _rectRewardPartParent`

- `ZoneRecordRewardContentView _rewardContentPrefab`

- `CanvasGroup _canvasContentFade1`

- `CanvasGroup _canvasContentFade2`

- `Boolean m_hasInited`

- `Main11RecordNoteDotListAdapter m_dotListAdapter`

- `String m_selectingRecordId`

- `ZoneRecordGroupViewModel m_cachedViewModel`

- `Main11RecordNotePageBtnGlowTweenWrapper m_pagePrevBtnGlowTween`

- `Main11RecordNotePageBtnGlowTweenWrapper m_pageNextBtnGlowTween`

- `ZoneRecordRewardContentView m_rewardContentView`

- `FadeSwitchTween m_noteContentFadeTween`

- `FadeSwitchTween m_noteContentArrowFadeTween`

- `Int32 m_cachedIndex`

- `Action <onPrevBtnClick>k__BackingField`

- `Action <onNextBtnClick>k__BackingField`

- `Action <onClaimAllRewardClick>k__BackingField`

- `Main11ZoneRecordController <controller>k__BackingField`


## Properties

- `Action onPrevBtnClick`

- `Action onNextBtnClick`

- `Action onClaimAllRewardClick`

- `Main11ZoneRecordController controller`


## Methods

- `Action get_onPrevBtnClick()`

- `Void set_onPrevBtnClick(Action)`

- `Action get_onNextBtnClick()`

- `Void set_onNextBtnClick(Action)`

- `Action get_onClaimAllRewardClick()`

- `Void set_onClaimAllRewardClick(Action)`

- `Main11ZoneRecordController get_controller()`

- `Void set_controller(Main11ZoneRecordController)`

- `Void _InitIfNot()`

- `Void _Render()`

- `Void _RenderPreNextBtnPart()`

- `Single _UpdatePageBtnAlpha(ZoneRecordViewModel)`

- `Void _UpdatePageBtnGlow(Main11RecordNotePageBtnGlowTweenWrapper, ZoneRecordViewModel)`

- `Void _ResetBeforeCloseNote()`

- `Void EventOnPrevBtnClick()`

- `Void EventOnNextBtnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage.ZoneRecord.Main11
public class Main11RecordNoteView : DataBinder`1
{
	private Main11RecordNoteContentView _contentView; // 0x20
	private CanvasGroup _canvasContent; // 0x28
	private SimpleLayoutContent _dotsLayout; // 0x30
	private GameObject _objPrevBtn; // 0x38
	private GameObject _objNextBtn; // 0x40
	private CanvasGroup _canvasPrevBtn; // 0x48
	private CanvasGroup _canvasNextBtn; // 0x50
	private CanvasGroup _canvasBtnPrevGlow; // 0x58
	private CanvasGroup _canvasBtnNextGlow; // 0x60
	private RectTransform _rectRewardPartParent; // 0x68
	private ZoneRecordRewardContentView _rewardContentPrefab; // 0x70
	private CanvasGroup _canvasContentFade1; // 0x78
	private CanvasGroup _canvasContentFade2; // 0x80
	private Boolean m_hasInited; // 0x88
	private Main11RecordNoteDotListAdapter m_dotListAdapter; // 0x90
	private String m_selectingRecordId; // 0x98
	private ZoneRecordGroupViewModel m_cachedViewModel; // 0xa0
	private Main11RecordNotePageBtnGlowTweenWrapper m_pagePrevBtnGlowTween; // 0xa8
	private Main11RecordNotePageBtnGlowTweenWrapper m_pageNextBtnGlowTween; // 0xb0
	private ZoneRecordRewardContentView m_rewardContentView; // 0xb8
	private FadeSwitchTween m_noteContentFadeTween; // 0xc0
	private FadeSwitchTween m_noteContentArrowFadeTween; // 0xc8
	private Int32 m_cachedIndex; // 0xd0
	private const Single PAGE_BTN_CANT_CLICK_ALPHA; // 0x0
	private const Single PAGE_BTN_CAN_CLICK_ALPHA; // 0x0
	private const Single CONTENT_FADE_DUR; // 0x0
	private Action <onPrevBtnClick>k__BackingField; // 0xd8
	private Action <onNextBtnClick>k__BackingField; // 0xe0
	private Action <onClaimAllRewardClick>k__BackingField; // 0xe8
	private Main11ZoneRecordController <controller>k__BackingField; // 0xf0
	private static DelegateBridge __Hotfix0_get_onPrevBtnClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onPrevBtnClick; // 0x8
	private static DelegateBridge __Hotfix0_get_onNextBtnClick; // 0x10
	private static DelegateBridge __Hotfix0_set_onNextBtnClick; // 0x18
	private static DelegateBridge __Hotfix0_get_onClaimAllRewardClick; // 0x20
	private static DelegateBridge __Hotfix0_set_onClaimAllRewardClick; // 0x28
	private static DelegateBridge __Hotfix0_get_controller; // 0x30
	private static DelegateBridge __Hotfix0_set_controller; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge __Hotfix0__Render; // 0x48
	private static DelegateBridge __Hotfix0__RenderPreNextBtnPart; // 0x50
	private static DelegateBridge __Hotfix0__UpdatePageBtnAlpha; // 0x58
	private static DelegateBridge __Hotfix0__UpdatePageBtnGlow; // 0x60
	private static DelegateBridge __Hotfix0__ResetBeforeCloseNote; // 0x68
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x70
	private static DelegateBridge __Hotfix0_EventOnPrevBtnClick; // 0x78
	private static DelegateBridge __Hotfix0_EventOnNextBtnClick; // 0x80
	private static DelegateBridge _c__Hotfix0_ctor; // 0x88

	public Action onPrevBtnClick { get; set; }
	public Action onNextBtnClick { get; set; }
	public Action onClaimAllRewardClick { get; set; }
	public Main11ZoneRecordController controller { get; set; }

	// RVA: 0x2fd92e4 VA: 0x75955f12e4
	public Action get_onPrevBtnClick() { }
	// RVA: 0x2fd934c VA: 0x75955f134c
	public Void set_onPrevBtnClick(Action value) { }
	// RVA: 0x2fd93d0 VA: 0x75955f13d0
	public Action get_onNextBtnClick() { }
	// RVA: 0x2fd9438 VA: 0x75955f1438
	public Void set_onNextBtnClick(Action value) { }
	// RVA: 0x2fd94bc VA: 0x75955f14bc
	public Action get_onClaimAllRewardClick() { }
	// RVA: 0x2fd9524 VA: 0x75955f1524
	public Void set_onClaimAllRewardClick(Action value) { }
	// RVA: 0x2fd95a8 VA: 0x75955f15a8
	public Main11ZoneRecordController get_controller() { }
	// RVA: 0x2fd9610 VA: 0x75955f1610
	public Void set_controller(Main11ZoneRecordController value) { }
	// RVA: 0x2fd9694 VA: 0x75955f1694
	private Void _InitIfNot() { }
	// RVA: 0x2fd9b00 VA: 0x75955f1b00
	private Void _Render() { }
	// RVA: 0x2fd9c44 VA: 0x75955f1c44
	private Void _RenderPreNextBtnPart() { }
	// RVA: 0x2fd9e24 VA: 0x75955f1e24
	private Single _UpdatePageBtnAlpha(ZoneRecordViewModel viewModel) { }
	// RVA: 0x2fd9ec4 VA: 0x75955f1ec4
	private Void _UpdatePageBtnGlow(Main11RecordNotePageBtnGlowTweenWrapper tween, ZoneRecordViewModel viewModel) { }
	// RVA: 0x2fda2a8 VA: 0x75955f22a8
	private Void _ResetBeforeCloseNote() { }
	// RVA: 0x2fda3d0 VA: 0x75955f23d0
	public override Void OnValueChanged(Main11ZoneRecordViewProperty property) { }
	// RVA: 0x2fda584 VA: 0x75955f2584
	public Void EventOnPrevBtnClick() { }
	// RVA: 0x2fda620 VA: 0x75955f2620
	public Void EventOnNextBtnClick() { }
	// RVA: 0x2fda6bc VA: 0x75955f26bc
	public Void .ctor() { }
}
```