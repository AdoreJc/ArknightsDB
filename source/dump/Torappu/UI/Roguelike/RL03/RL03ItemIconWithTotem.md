# RL03ItemIconWithTotem

**Namespace:** `Torappu.UI.Roguelike.RL03`


## Fields

- `Image _itemIconImage`

- `RL03TotemItemView _totemIconPrefab`

- `UIColorGraphic _colorGraphic`

- `RL03TotemItemView m_totemIcon`


## Methods

- `RL03TotemItemView _EnsureTotemIcon()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL03
public class RL03ItemIconWithTotem : RoguelikeCustomizableItemIcon
{
	private Image _itemIconImage; // 0x38
	private RL03TotemItemView _totemIconPrefab; // 0x40
	private UIColorGraphic _colorGraphic; // 0x48
	private RL03TotemItemView m_totemIcon; // 0x50
	private static DelegateBridge __Hotfix0_get_graphic; // 0x0
	private static DelegateBridge __Hotfix0__EnsureTotemIcon; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public override Graphic graphic { get; }

	// RVA: 0x2b93994 VA: 0x75951ab994
	public override Graphic get_graphic() { }
	// RVA: 0x2b939fc VA: 0x75951ab9fc
	private RL03TotemItemView _EnsureTotemIcon() { }
	// RVA: 0x2b93ba0 VA: 0x75951abba0
	public override Void Render(String topicId, String itemId, RoguelikeGameItemType itemType) { }
	// RVA: 0x2b93d4c VA: 0x75951abd4c
	public Void .ctor() { }
}
```