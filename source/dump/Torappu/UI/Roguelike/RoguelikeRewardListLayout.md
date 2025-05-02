# RoguelikeRewardListLayout

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Rect _padding`

- `Single _spacing`

- `Single _itemMoveDur`

- `Single _itemMoveDelay`

- `Single _itemFadeDur`

- `Single _itemFadeMoveBias`

- `RoguelikeRewardItemHolder itemPrefab`

- `Vector2 gridSize`

- `String m_topicId`

- `UIIntEvent m_onItemClicked`

- `InnerAdapter m_adapter`

- `InnerLayouter m_layouter`

- `Boolean m_showImmediately`

- `Boolean m_newAddItemWithDelay`

- `Boolean m_isInited`


## Methods

- `Void InitLayout(Options)`

- `Void UpdateData(IList`1, Boolean, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeRewardListLayout : UICustomAdapterLayout`2
{
	private const Single ADDITIONAL_ITEM_SHOW_DELAY; // 0x0
	private Rect _padding; // 0x78
	private Single _spacing; // 0x88
	private Single _itemMoveDur; // 0x8c
	private Single _itemMoveDelay; // 0x90
	private Single _itemFadeDur; // 0x94
	private Single _itemFadeMoveBias; // 0x98
	public RoguelikeRewardItemHolder itemPrefab; // 0xa0
	public Vector2 gridSize; // 0xa8
	private List`1 m_itemList; // 0xb0
	private Dictionary`2 m_gridIndexMap; // 0xb8
	private String m_topicId; // 0xc0
	private UIIntEvent m_onItemClicked; // 0xc8
	private InnerAdapter m_adapter; // 0xd0
	private InnerLayouter m_layouter; // 0xd8
	private Boolean m_showImmediately; // 0xe0
	private Boolean m_newAddItemWithDelay; // 0xe1
	private Boolean m_isInited; // 0xe2
	private static DelegateBridge __Hotfix0_InitLayout; // 0x0
	private static DelegateBridge __Hotfix0_UpdateData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2a9ba90 VA: 0x75950b3a90
	public Void InitLayout(Options options) { }
	// RVA: 0x2a9be04 VA: 0x75950b3e04
	public Void UpdateData(IList`1 itemList, Boolean showImmediately, Boolean newAddItemWithDelay) { }
	// RVA: 0x2a9c1bc VA: 0x75950b41bc
	public Void .ctor() { }
}
```