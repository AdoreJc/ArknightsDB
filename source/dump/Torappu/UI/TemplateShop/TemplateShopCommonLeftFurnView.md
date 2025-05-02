# TemplateShopCommonLeftFurnView

**Namespace:** `Torappu.UI.TemplateShop`


## Fields

- `Text _itemDetailName`

- `Text _addText`

- `Transform _itemContainer`

- `UIItemCard _itemCard`

- `Single _scaleCount`

- `UIItemCard m_itemCard`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void Render(TemplateCommonShopGoodViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateShop
public class TemplateShopCommonLeftFurnView : MonoBehaviour, IHotfixable
{
	private Text _itemDetailName; // 0x18
	private Text _addText; // 0x20
	private Transform _itemContainer; // 0x28
	private UIItemCard _itemCard; // 0x30
	private Single _scaleCount; // 0x38
	private UIItemCard m_itemCard; // 0x40
	private Boolean m_isInited; // 0x48
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x235ac44 VA: 0x7594972c44
	private Void _InitIfNot() { }
	// RVA: 0x235add0 VA: 0x7594972dd0
	public Void Render(TemplateCommonShopGoodViewModel shopViewModel) { }
	// RVA: 0x235b094 VA: 0x7594973094
	public Void .ctor() { }
}
```