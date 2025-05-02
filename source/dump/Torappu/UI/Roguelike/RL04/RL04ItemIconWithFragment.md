# RL04ItemIconWithFragment

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `Image _itemIconImage`

- `RL04FragmentItemCard _fragmentItemPrefab`

- `UIColorGraphic _colorGraphic`

- `Single _fragmentItemScale`

- `RL04FragmentItemCard m_fragmentItem`


## Methods

- `RL04FragmentItemCard _EnsureFragmentItem()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04ItemIconWithFragment : RoguelikeCustomizableItemIcon
{
	private Image _itemIconImage; // 0x38
	private RL04FragmentItemCard _fragmentItemPrefab; // 0x40
	private UIColorGraphic _colorGraphic; // 0x48
	private Single _fragmentItemScale; // 0x50
	private RL04FragmentItemCard m_fragmentItem; // 0x58
	private static DelegateBridge __Hotfix0_get_graphic; // 0x0
	private static DelegateBridge __Hotfix0__EnsureFragmentItem; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override Graphic graphic { get; }

	// RVA: 0x2b12bdc VA: 0x759512abdc
	public override Graphic get_graphic() { }
	// RVA: 0x2b12c44 VA: 0x759512ac44
	private RL04FragmentItemCard _EnsureFragmentItem() { }
	// RVA: 0x2b1300c VA: 0x759512b00c
	public override Void Render(String topicId, String itemId, RoguelikeGameItemType itemType) { }
	// RVA: 0x2b138fc VA: 0x759512b8fc
	public Void .ctor() { }
}
```