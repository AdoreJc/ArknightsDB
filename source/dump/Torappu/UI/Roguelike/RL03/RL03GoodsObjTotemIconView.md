# RL03GoodsObjTotemIconView

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `RectTransform _rectTotemItemContainer`

- `RL03TotemItemView _totemItemPrefab`

- `Single _itemScale`

- `RL03TotemItemView m_totemItem`

- `UIStateFinder m_finder`

- `String m_topicId`

- `String m_itemId`

- `RL03TotemViewModel m_totemViewModel`


## Methods

- `Boolean _IsTotem(RoguelikeGameItemType)`

- `Boolean _IsItemChange(String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03GoodsObjTotemIconView : RoguelikeGoodsObjIconView
{
	private RectTransform _rectTotemItemContainer; // 0x18
	private RL03TotemItemView _totemItemPrefab; // 0x20
	private Single _itemScale; // 0x28
	private RL03TotemItemView m_totemItem; // 0x30
	private UIStateFinder m_finder; // 0x38
	private String m_topicId; // 0x48
	private String m_itemId; // 0x50
	private RL03TotemViewModel m_totemViewModel; // 0x58
	private static DelegateBridge __Hotfix0_NeedShowPlugin; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0__IsTotem; // 0x10
	private static DelegateBridge __Hotfix0__IsItemChange; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2ba40c8 VA: 0x75951bc0c8
	public override Boolean NeedShowPlugin(RoguelikeGoodsViewModel viewModel) { }
	// RVA: 0x2ba41e0 VA: 0x75951bc1e0
	public override Void Render(RoguelikeGoodsViewModel viewModel) { }
	// RVA: 0x2ba4160 VA: 0x75951bc160
	private Boolean _IsTotem(RoguelikeGameItemType type) { }
	// RVA: 0x2ba4430 VA: 0x75951bc430
	private Boolean _IsItemChange(String topicId, String itemId) { }
	// RVA: 0x2ba4504 VA: 0x75951bc504
	public Void .ctor() { }
}
```