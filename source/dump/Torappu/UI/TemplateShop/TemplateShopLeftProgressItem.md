# TemplateShopLeftProgressItem

**Namespace:** `Torappu.UI.TemplateShop`


## Fields

- `Image _itemSprite`

- `Image _itemSpriteReplicate`

- `AnimationWrapper _animationWrapper`

- `Text _index`

- `Text _count`

- `Image _backImage`

- `GameObject _charPart`

- `GameObject _isSoldOut`

- `Single _itemScale`

- `UIItemViewModel m_cacheViewModel`

- `UIItemCard m_itemCard`


## Methods

- `Void _EnsureItemCard()`

- `Void InitCommonPart(Int32, ProgessGoodItem)`

- `Void InitActiveData(Int32, Int32, ProgessGoodItem)`

- `Void InitUnActiveData(Int32, Int32, ProgessGoodItem, Boolean)`

- `Single GetWidth(Int32, Boolean)`

- `Void OpenCharacterShow()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateShop
public class TemplateShopLeftProgressItem : MonoBehaviour, IHotfixable
{
	private Image _itemSprite; // 0x18
	private Image _itemSpriteReplicate; // 0x20
	private AnimationWrapper _animationWrapper; // 0x28
	private Text _index; // 0x30
	private Text _count; // 0x38
	private Image _backImage; // 0x40
	private GameObject _charPart; // 0x48
	private GameObject _isSoldOut; // 0x50
	private Single _itemScale; // 0x58
	private UIItemViewModel m_cacheViewModel; // 0x60
	private UIItemCard m_itemCard; // 0x68
	private static readonly Single[] BACKIMAGEBLACKTYPE; // 0x0
	private const Single ACTIVE_SCALE; // 0x0
	private const Single TOTAL_WIDTH; // 0x0
	private static DelegateBridge __Hotfix0__EnsureItemCard; // 0x8
	private static DelegateBridge __Hotfix0_InitCommonPart; // 0x10
	private static DelegateBridge __Hotfix0_InitActiveData; // 0x18
	private static DelegateBridge __Hotfix0_InitUnActiveData; // 0x20
	private static DelegateBridge __Hotfix0_GetWidth; // 0x28
	private static DelegateBridge __Hotfix0_OpenCharacterShow; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x235d850 VA: 0x7594975850
	private Void _EnsureItemCard() { }
	// RVA: 0x235da0c VA: 0x7594975a0c
	private Void InitCommonPart(Int32 index, ProgessGoodItem item) { }
	// RVA: 0x235dce0 VA: 0x7594975ce0
	public Void InitActiveData(Int32 index, Int32 totalCount, ProgessGoodItem viewModel) { }
	// RVA: 0x235deb0 VA: 0x7594975eb0
	public Void InitUnActiveData(Int32 index, Int32 totalCount, ProgessGoodItem viewModel, Boolean isSoldOut) { }
	// RVA: 0x235ddf0 VA: 0x7594975df0
	public Single GetWidth(Int32 totalCount, Boolean isActive) { }
	// RVA: 0x235e03c VA: 0x759497603c
	public Void OpenCharacterShow() { }
	// RVA: 0x235e144 VA: 0x7594976144
	public Void .ctor() { }
	// RVA: 0x235e1d0 VA: 0x75949761d0
	private static Void .cctor() { }
}
```