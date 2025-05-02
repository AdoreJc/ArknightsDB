# RoguelikeSacrificeSelectedView

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `CanvasGroup _canvasEmpty`

- `CanvasGroup _canvasItem`

- `Text _textItemName`

- `Text _textItemUsage`

- `GameObject _panelChosen`

- `RectTransform _itemIconHolder`

- `RoguelikeCustomizableItemIcon _itemIconPrefab`

- `Single _itemIconScale`

- `Boolean m_hasInited`

- `UISwitchTween m_showTweenEmpty`

- `UISwitchTween m_showTweenIcon`

- `String m_cachedSelectedItemId`

- `RoguelikeCustomizableItemIcon m_itemIcon`


## Methods

- `Void Render(RoguelikeSacrificeViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeSacrificeSelectedView : MonoBehaviour, IHotfixable
{
	private CanvasGroup _canvasEmpty; // 0x18
	private CanvasGroup _canvasItem; // 0x20
	private Text _textItemName; // 0x28
	private Text _textItemUsage; // 0x30
	private GameObject _panelChosen; // 0x38
	private RectTransform _itemIconHolder; // 0x40
	private RoguelikeCustomizableItemIcon _itemIconPrefab; // 0x48
	private Single _itemIconScale; // 0x50
	private Boolean m_hasInited; // 0x54
	private UISwitchTween m_showTweenEmpty; // 0x58
	private UISwitchTween m_showTweenIcon; // 0x60
	private String m_cachedSelectedItemId; // 0x68
	private RoguelikeCustomizableItemIcon m_itemIcon; // 0x70
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2abf8e8 VA: 0x75950d78e8
	public Void Render(RoguelikeSacrificeViewModel viewModel) { }
	// RVA: 0x2abfd58 VA: 0x75950d7d58
	private Void _InitIfNot() { }
	// RVA: 0x2ac0038 VA: 0x75950d8038
	public Void .ctor() { }
}
```