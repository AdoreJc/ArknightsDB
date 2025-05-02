# RoguelikeMenuRelicLayout

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `RectTransform _bound`

- `RoguelikeMenuRelicItemView _itemPrefab`

- `Vector2 _gridSize`

- `Rect _padding`

- `Vector2 _spacing`

- `RoguelikeMenuRelicViewModel m_groupModel`

- `InnerLayouter m_layouter`

- `InnerAdapter m_adapter`

- `Boolean m_cachedShowTrap`

- `Int32 m_cachedNumLimit`

- `Boolean m_cachedIsInit`

- `Action onClickEvent`

- `Boolean m_isInited`


## Properties

- `RectTransform bound`


## Methods

- `RectTransform get_bound()`

- `Void _InitIfNot()`

- `Void Render(RoguelikeMenuRelicViewModel, Boolean, Int32, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeMenuRelicLayout : UICustomAdapterLayout`2
{
	private RectTransform _bound; // 0x78
	private RoguelikeMenuRelicItemView _itemPrefab; // 0x80
	private Vector2 _gridSize; // 0x88
	private Rect _padding; // 0x90
	private Vector2 _spacing; // 0xa0
	private RoguelikeMenuRelicViewModel m_groupModel; // 0xa8
	private InnerLayouter m_layouter; // 0xb0
	private InnerAdapter m_adapter; // 0xb8
	private Boolean m_cachedShowTrap; // 0xc0
	private Int32 m_cachedNumLimit; // 0xc4
	private Boolean m_cachedIsInit; // 0xc8
	public Action onClickEvent; // 0xd0
	private Boolean m_isInited; // 0xd8
	private static DelegateBridge __Hotfix0_get_bound; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public RectTransform bound { get; }

	// RVA: 0x2a40e14 VA: 0x7595058e14
	public RectTransform get_bound() { }
	// RVA: 0x2a41f4c VA: 0x7595059f4c
	private Void _InitIfNot() { }
	// RVA: 0x2a40f88 VA: 0x7595058f88
	public Void Render(RoguelikeMenuRelicViewModel groupModel, Boolean showTrap, Int32 numLimit, Boolean isInit) { }
	// RVA: 0x2a421c8 VA: 0x759505a1c8
	public Void .ctor() { }
}
```