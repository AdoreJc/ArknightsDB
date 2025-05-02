# UIMedalDIYCardView

**Namespace:** `Torappu.UI.Medal`


## Fields

- `Image _icon`

- `CanvasGroup _alphaHandler`

- `RectTransform _cardTrans`

- `Single _yBiasSelected`

- `Single _yBiasDefault`

- `CanvasGroup _cardCanvasGroup`

- `Single _selectedAlpha`

- `DragContext m_drag`

- `DIYMedalModel m_viewModel`

- `DragDelegate m_dragEvents`

- `IMedalDIYContext m_context`

- `Tween m_cardMoveTween`

- `Tween m_cardAlphaTween`


## Properties

- `CanvasGroup alphaHandler`


## Methods

- `CanvasGroup get_alphaHandler()`

- `Void Init(IMedalDIYContext, DragDelegate)`

- `Void Render(DIYMedalModel)`

- `Void _UpdateSelectedStatus()`

- `Void _SetCardPosWithTween(Vector2)`

- `Void _SetCardAlphaWithTween(Single)`

- `Void OnDisable()`

- `Void OnDrag(PointerEventData)`

- `Void OnBeginDrag(PointerEventData)`

- `Void OnEndDrag(PointerEventData)`

- `Void <_SetCardAlphaWithTween>b__23_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class UIMedalDIYCardView : MonoBehaviour, IHotfixable, IDragHandler, IEventSystemHandler, IBeginDragHandler, IEndDragHandler
{
	private static readonly Vector2 DRAG_DIR_DIS; // 0x0
	private const Single CARD_MOVE_DUR; // 0x0
	private Image _icon; // 0x18
	private CanvasGroup _alphaHandler; // 0x20
	private RectTransform _cardTrans; // 0x28
	private Single _yBiasSelected; // 0x30
	private Single _yBiasDefault; // 0x34
	private CanvasGroup _cardCanvasGroup; // 0x38
	private Single _selectedAlpha; // 0x40
	private DragContext m_drag; // 0x44
	private DIYMedalModel m_viewModel; // 0x50
	private DragDelegate m_dragEvents; // 0x58
	private IMedalDIYContext m_context; // 0x78
	private Tween m_cardMoveTween; // 0x80
	private Tween m_cardAlphaTween; // 0x88
	private static DelegateBridge __Hotfix0_get_alphaHandler; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0__UpdateSelectedStatus; // 0x20
	private static DelegateBridge __Hotfix0__SetCardPosWithTween; // 0x28
	private static DelegateBridge __Hotfix0__SetCardAlphaWithTween; // 0x30
	private static DelegateBridge __Hotfix0_OnDisable; // 0x38
	private static DelegateBridge __Hotfix0_OnDrag; // 0x40
	private static DelegateBridge __Hotfix0_OnBeginDrag; // 0x48
	private static DelegateBridge __Hotfix0_OnEndDrag; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public CanvasGroup alphaHandler { get; }

	// RVA: 0x2767ffc VA: 0x7594d7fffc
	public CanvasGroup get_alphaHandler() { }
	// RVA: 0x2768518 VA: 0x7594d80518
	public Void Init(IMedalDIYContext context, DragDelegate dragEvents) { }
	// RVA: 0x2768778 VA: 0x7594d80778
	public Void Render(DIYMedalModel viewModel) { }
	// RVA: 0x27688ec VA: 0x7594d808ec
	private Void _UpdateSelectedStatus() { }
	// RVA: 0x2768a4c VA: 0x7594d80a4c
	private Void _SetCardPosWithTween(Vector2 targetPos) { }
	// RVA: 0x2768dbc VA: 0x7594d80dbc
	private Void _SetCardAlphaWithTween(Single targetAlpha) { }
	// RVA: 0x2768f9c VA: 0x7594d80f9c
	private Void OnDisable() { }
	// RVA: 0x276904c VA: 0x7594d8104c
	public Void OnDrag(PointerEventData eventData) { }
	// RVA: 0x27693a8 VA: 0x7594d813a8
	public Void OnBeginDrag(PointerEventData eventData) { }
	// RVA: 0x27694d4 VA: 0x7594d814d4
	public Void OnEndDrag(PointerEventData eventData) { }
	// RVA: 0x27695d0 VA: 0x7594d815d0
	public Void .ctor() { }
	// RVA: 0x2769694 VA: 0x7594d81694
	private static Void .cctor() { }
	// RVA: 0x27696e4 VA: 0x7594d816e4
	private Void <_SetCardAlphaWithTween>b__23_0() { }
}
```