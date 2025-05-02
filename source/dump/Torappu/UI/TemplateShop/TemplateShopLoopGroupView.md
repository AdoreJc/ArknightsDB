# TemplateShopLoopGroupView

**Namespace:** `Torappu.UI.TemplateShop`


## Fields

- `SimpleLayoutContent _content`

- `Text _slotId`

- `GameObject _lockedPart`

- `Text _lockedString`

- `GridLayoutGroup _layOutGroup`

- `ContentSizeFitter _sizeFitter`

- `Image _backImage`

- `ItemAdapter m_adapter`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void ApplyCellSizeAndSpacing(Vector2, Vector2)`

- `Void Render(TemplateShopGroupViewModel, TemplateShopResHolder, Int32, AsyncGameObjectLoader)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateShop
public class TemplateShopLoopGroupView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _content; // 0x18
	private Text _slotId; // 0x20
	private GameObject _lockedPart; // 0x28
	private Text _lockedString; // 0x30
	private GridLayoutGroup _layOutGroup; // 0x38
	private ContentSizeFitter _sizeFitter; // 0x40
	private Image _backImage; // 0x48
	private ItemAdapter m_adapter; // 0x50
	private Boolean m_isInited; // 0x58
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_ApplyCellSizeAndSpacing; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x235e334 VA: 0x7594976334
	public Void _InitIfNot() { }
	// RVA: 0x235e490 VA: 0x7594976490
	public Void ApplyCellSizeAndSpacing(Vector2 cellSize, Vector2 spacing) { }
	// RVA: 0x235e55c VA: 0x759497655c
	public Void Render(TemplateShopGroupViewModel groupViewModel, TemplateShopResHolder holder, Int32 constraint, AsyncGameObjectLoader loader) { }
	// RVA: 0x235e788 VA: 0x7594976788
	public Void .ctor() { }
}
```