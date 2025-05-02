# TemplateShopCommonItemView

**Namespace:** `Torappu.UI.TemplateShop`


## Fields

- `Text _priceText`

- `UIItemCard _itemCard`

- `Transform _itemContainer`

- `Single _itemScale`

- `GameObject _remainCountPart`

- `Text _remainCount`

- `Text _priceCount`

- `Image _priceIcon`

- `CanvasGroup _soldOutGroup`

- `GameObject _soldOutImg`

- `GameObject _alreadyGetObj`

- `GameObject _progressPart`

- `Text _progressText`

- `GameObject _charPart`

- `UIAtlasImage _charPortraitImg`

- `Image _charRarityImg`

- `Image _charProfessionImg`

- `Text _charName`

- `GameObject _skinPart`

- `UIAtlasImage _skinPortraitImg`

- `Image _skinBrandImage`

- `Text _skinCharName`

- `Text _skinName`

- `GameObject _normalPart`

- `Text _normalName`

- `GameObject _replicatePart`

- `AnimationWrapper _replicateObj`

- `Transform _replicateItemContainer`

- `UIItemCard m_itemCard`

- `UIItemCard m_replicateItemCard`

- `TemplateCommonShopGoodViewModel m_cacheViewModel`


## Methods

- `UIItemCard _EnsureItemCard()`

- `UIItemCard _EnsureReplicateItemCard()`

- `Void AsyncSetData(TemplateCommonShopGoodViewModel)`

- `Void RenderItem(TemplateCommonShopGoodViewModel)`

- `Void _RenderCommonPart(TemplateCommonShopGoodViewModel)`

- `Void _RenderChar(TemplateCommonShopGoodViewModel)`

- `Void _RenderSkin(TemplateCommonShopGoodViewModel)`

- `Void _RenderCommonItemType(TemplateCommonShopGoodViewModel)`

- `Void _RenderNormalGoodType(TemplateCommonShopGoodViewModel)`

- `Void _RenderProgressGoodType(TemplateCommonShopGoodViewModel)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateShop
public class TemplateShopCommonItemView : MonoBehaviour, IHotfixable, IAsyncDataView`1
{
	private Text _priceText; // 0x18
	private UIItemCard _itemCard; // 0x20
	private Transform _itemContainer; // 0x28
	private Single _itemScale; // 0x30
	private GameObject _remainCountPart; // 0x38
	private Text _remainCount; // 0x40
	private Text _priceCount; // 0x48
	private Image _priceIcon; // 0x50
	private CanvasGroup _soldOutGroup; // 0x58
	private GameObject _soldOutImg; // 0x60
	private GameObject _alreadyGetObj; // 0x68
	private GameObject _progressPart; // 0x70
	private Text _progressText; // 0x78
	private GameObject _charPart; // 0x80
	private UIAtlasImage _charPortraitImg; // 0x88
	private Image _charRarityImg; // 0x90
	private Image _charProfessionImg; // 0x98
	private Text _charName; // 0xa0
	private GameObject _skinPart; // 0xa8
	private UIAtlasImage _skinPortraitImg; // 0xb0
	private Image _skinBrandImage; // 0xb8
	private Text _skinCharName; // 0xc0
	private Text _skinName; // 0xc8
	private GameObject _normalPart; // 0xd0
	private Text _normalName; // 0xd8
	private GameObject _replicatePart; // 0xe0
	private AnimationWrapper _replicateObj; // 0xe8
	private Transform _replicateItemContainer; // 0xf0
	private const String REPLICATE_SHINING; // 0x0
	private UIItemCard m_itemCard; // 0xf8
	private UIItemCard m_replicateItemCard; // 0x100
	private TemplateCommonShopGoodViewModel m_cacheViewModel; // 0x108
	private static DelegateBridge __Hotfix0__EnsureItemCard; // 0x0
	private static DelegateBridge __Hotfix0__EnsureReplicateItemCard; // 0x8
	private static DelegateBridge __Hotfix0_AsyncSetData; // 0x10
	private static DelegateBridge __Hotfix0_RenderItem; // 0x18
	private static DelegateBridge __Hotfix0__RenderCommonPart; // 0x20
	private static DelegateBridge __Hotfix0__RenderChar; // 0x28
	private static DelegateBridge __Hotfix0__RenderSkin; // 0x30
	private static DelegateBridge __Hotfix0__RenderCommonItemType; // 0x38
	private static DelegateBridge __Hotfix0__RenderNormalGoodType; // 0x40
	private static DelegateBridge __Hotfix0__RenderProgressGoodType; // 0x48
	private static DelegateBridge __Hotfix0_OnClick; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x23597a8 VA: 0x75949717a8
	private UIItemCard _EnsureItemCard() { }
	// RVA: 0x2359940 VA: 0x7594971940
	private UIItemCard _EnsureReplicateItemCard() { }
	// RVA: 0x2359adc VA: 0x7594971adc
	public Void AsyncSetData(TemplateCommonShopGoodViewModel viewModel) { }
	// RVA: 0x2359b5c VA: 0x7594971b5c
	public Void RenderItem(TemplateCommonShopGoodViewModel viewModel) { }
	// RVA: 0x2359cbc VA: 0x7594971cbc
	private Void _RenderCommonPart(TemplateCommonShopGoodViewModel viewModel) { }
	// RVA: 0x235a20c VA: 0x759497220c
	private Void _RenderChar(TemplateCommonShopGoodViewModel viewModel) { }
	// RVA: 0x235a5e0 VA: 0x75949725e0
	private Void _RenderSkin(TemplateCommonShopGoodViewModel viewModel) { }
	// RVA: 0x235a890 VA: 0x7594972890
	private Void _RenderCommonItemType(TemplateCommonShopGoodViewModel viewModel) { }
	// RVA: 0x235a040 VA: 0x7594972040
	private Void _RenderNormalGoodType(TemplateCommonShopGoodViewModel viewModel) { }
	// RVA: 0x235a0c4 VA: 0x75949720c4
	private Void _RenderProgressGoodType(TemplateCommonShopGoodViewModel viewModel) { }
	// RVA: 0x235ab60 VA: 0x7594972b60
	public Void OnClick() { }
	// RVA: 0x235abc8 VA: 0x7594972bc8
	public Void .ctor() { }
}
```