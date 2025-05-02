# RoguelikeSacrificeListItem

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `CanvasGroup _canvasSelected`

- `RectTransform _itemIconHolder`

- `RoguelikeCustomizableItemIcon _itemIconPrefab`

- `Single _itemIconScale`

- `UIColorGraphic _colorGraphic`

- `Boolean m_inited`

- `UISwitchTween m_selectedTween`

- `String m_cachedInstId`

- `RoguelikeCustomizableItemIcon m_itemIcon`


## Methods

- `Void set_onItemClick(Action`1)`

- `Void _InitIfNot()`

- `Void Render(IRoguelikeSacrifice, String, Boolean)`

- `Void OnBtnClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeSacrificeListItem : MonoBehaviour, IHotfixable
{
	private CanvasGroup _canvasSelected; // 0x18
	private RectTransform _itemIconHolder; // 0x20
	private RoguelikeCustomizableItemIcon _itemIconPrefab; // 0x28
	private Single _itemIconScale; // 0x30
	private UIColorGraphic _colorGraphic; // 0x38
	private Boolean m_inited; // 0x40
	private UISwitchTween m_selectedTween; // 0x48
	private String m_cachedInstId; // 0x50
	private RoguelikeCustomizableItemIcon m_itemIcon; // 0x58
	private Action`1 <onItemClick>k__BackingField; // 0x60
	private static DelegateBridge __Hotfix0_get_onItemClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onItemClick; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0_OnBtnClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Action`1 onItemClick { get; set; }

	// RVA: 0x2abec24 VA: 0x75950d6c24
	public Action`1 get_onItemClick() { }
	// RVA: 0x2abec8c VA: 0x75950d6c8c
	public Void set_onItemClick(Action`1 value) { }
	// RVA: 0x2abed10 VA: 0x75950d6d10
	private Void _InitIfNot() { }
	// RVA: 0x2abee98 VA: 0x75950d6e98
	public Void Render(IRoguelikeSacrifice data, String selectedItem, Boolean fastMode) { }
	// RVA: 0x2abf1c0 VA: 0x75950d71c0
	public Void OnBtnClicked() { }
	// RVA: 0x2abf260 VA: 0x75950d7260
	public Void .ctor() { }
}
```