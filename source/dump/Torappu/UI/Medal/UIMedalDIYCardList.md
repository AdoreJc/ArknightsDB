# UIMedalDIYCardList

**Namespace:** `Torappu.UI.Medal`


## Fields

- `UIWrappedScrollRect _scroll`

- `UIMedalDIYCardView _cardPrefab`

- `Rect _padding`

- `Vector2 _spacing`

- `Vector2 _gridSize`

- `RectTransform _bkgTrans`

- `Single _bkgHideY`

- `IMedalDIYContext m_context`

- `MedalDIYViewModel m_viewModel`

- `Tween m_moveTween`

- `InnerLayouter m_layouter`

- `InnerAdapter m_adapter`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void Render(IMedalDIYContext, MedalDIYViewModel)`

- `Void _CancelScrollDrag()`

- `Void _OnDrag(PointerEventData)`

- `Void _OnBeginDrag(PointerEventData)`

- `Void _OnEndDrag(PointerEventData)`

- `Void _UpdateBkgTrans()`

- `Void <_UpdateBkgTrans>b__22_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Medal
public class UIMedalDIYCardList : UICustomAdapterLayout`2, IHotfixable
{
	private const Single BKG_MOVE_DUR; // 0x0
	private UIWrappedScrollRect _scroll; // 0x78
	private UIMedalDIYCardView _cardPrefab; // 0x80
	private Rect _padding; // 0x88
	private Vector2 _spacing; // 0x98
	private Vector2 _gridSize; // 0xa0
	private RectTransform _bkgTrans; // 0xa8
	private Single _bkgHideY; // 0xb0
	private IMedalDIYContext m_context; // 0xb8
	private MedalDIYViewModel m_viewModel; // 0xc0
	private Tween m_moveTween; // 0xc8
	private InnerLayouter m_layouter; // 0xd0
	private InnerAdapter m_adapter; // 0xd8
	private Boolean m_isInited; // 0xe0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__CancelScrollDrag; // 0x10
	private static DelegateBridge __Hotfix0__OnDrag; // 0x18
	private static DelegateBridge __Hotfix0__OnBeginDrag; // 0x20
	private static DelegateBridge __Hotfix0__OnEndDrag; // 0x28
	private static DelegateBridge __Hotfix0__UpdateBkgTrans; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x27668a4 VA: 0x7594d7e8a4
	private Void _InitIfNot() { }
	// RVA: 0x2766b28 VA: 0x7594d7eb28
	public Void Render(IMedalDIYContext context, MedalDIYViewModel viewModel) { }
	// RVA: 0x2766e44 VA: 0x7594d7ee44
	private Void _CancelScrollDrag() { }
	// RVA: 0x2766eb8 VA: 0x7594d7eeb8
	private Void _OnDrag(PointerEventData eventData) { }
	// RVA: 0x2766f4c VA: 0x7594d7ef4c
	private Void _OnBeginDrag(PointerEventData eventData) { }
	// RVA: 0x2766fe0 VA: 0x7594d7efe0
	private Void _OnEndDrag(PointerEventData eventData) { }
	// RVA: 0x2766c40 VA: 0x7594d7ec40
	private Void _UpdateBkgTrans() { }
	// RVA: 0x2767074 VA: 0x7594d7f074
	public Void .ctor() { }
	// RVA: 0x2767104 VA: 0x7594d7f104
	private Void <_UpdateBkgTrans>b__22_0() { }
}
```