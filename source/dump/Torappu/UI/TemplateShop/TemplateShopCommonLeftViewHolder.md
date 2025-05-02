# TemplateShopCommonLeftViewHolder

**Namespace:** `Torappu.UI.TemplateShop`


## Fields

- `Text _name`

- `Text _description`

- `Text _usage`

- `GameObject _normalView`

- `TemplateShopLeftProgressView _progressView`

- `TemplateShopCommonLeftFurnView _furnView`

- `ShopDetailItemPileView _pileView`

- `Transform _pileViewContainer`

- `Transform _replicateItemContainer`

- `GameObject _replicateIcon`

- `AnimationWrapper _animationWrapper`

- `Single _scaleInfo`

- `ShopDetailItemPileView m_pileView`

- `UIItemCard m_replicateItemCard`

- `Boolean m_isInited`

- `Boolean m_isFirstTime`

- `Boolean m_cacheReplicated`


## Methods

- `Void _InitedIfNot()`

- `Void RenderFirstTime()`

- `Void Render(TemplateCommonShopGoodViewModel, Boolean, ItemBundle)`

- `Void RenderReplicate(Boolean, ItemBundle)`

- `Void _RenderReplicate(Boolean, ItemBundle)`

- `Void RenderNormalObj(TemplateCommonShopGoodViewModel)`

- `Void RenderProgressObj(TemplateCommonShopGoodViewModel)`

- `Void RenderCommonObj(TemplateCommonShopGoodViewModel)`

- `Void RenderFurn(TemplateCommonShopGoodViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateShop
public class TemplateShopCommonLeftViewHolder : MonoBehaviour, IHotfixable
{
	private Text _name; // 0x18
	private Text _description; // 0x20
	private Text _usage; // 0x28
	private GameObject _normalView; // 0x30
	private TemplateShopLeftProgressView _progressView; // 0x38
	private TemplateShopCommonLeftFurnView _furnView; // 0x40
	private ShopDetailItemPileView _pileView; // 0x48
	private Transform _pileViewContainer; // 0x50
	private Transform _replicateItemContainer; // 0x58
	private GameObject _replicateIcon; // 0x60
	private AnimationWrapper _animationWrapper; // 0x68
	private Single _scaleInfo; // 0x70
	private ShopDetailItemPileView m_pileView; // 0x78
	private UIItemCard m_replicateItemCard; // 0x80
	private Boolean m_isInited; // 0x88
	private Boolean m_isFirstTime; // 0x89
	private Boolean m_cacheReplicated; // 0x8a
	private const String ANIMATION_SHINING; // 0x0
	private static DelegateBridge __Hotfix0__InitedIfNot; // 0x0
	private static DelegateBridge __Hotfix0_RenderFirstTime; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_RenderReplicate; // 0x18
	private static DelegateBridge __Hotfix0__RenderReplicate; // 0x20
	private static DelegateBridge __Hotfix0_RenderNormalObj; // 0x28
	private static DelegateBridge __Hotfix0_RenderProgressObj; // 0x30
	private static DelegateBridge __Hotfix0_RenderCommonObj; // 0x38
	private static DelegateBridge __Hotfix0_RenderFurn; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x235b110 VA: 0x7594973110
	private Void _InitedIfNot() { }
	// RVA: 0x2353f80 VA: 0x759496bf80
	public Void RenderFirstTime() { }
	// RVA: 0x2354060 VA: 0x759496c060
	public Void Render(TemplateCommonShopGoodViewModel shopViewModel, Boolean isReplicate, ItemBundle item) { }
	// RVA: 0x235b89c VA: 0x759497389c
	public Void RenderReplicate(Boolean isReplicate, ItemBundle item) { }
	// RVA: 0x235b320 VA: 0x7594973320
	private Void _RenderReplicate(Boolean isReplicate, ItemBundle item) { }
	// RVA: 0x235b4cc VA: 0x75949734cc
	public Void RenderNormalObj(TemplateCommonShopGoodViewModel shopViewModel) { }
	// RVA: 0x235b68c VA: 0x759497368c
	public Void RenderProgressObj(TemplateCommonShopGoodViewModel shopViewModel) { }
	// RVA: 0x235ba18 VA: 0x7594973a18
	public Void RenderCommonObj(TemplateCommonShopGoodViewModel shopViewModel) { }
	// RVA: 0x235b958 VA: 0x7594973958
	public Void RenderFurn(TemplateCommonShopGoodViewModel shopViewModel) { }
	// RVA: 0x235bdc8 VA: 0x7594973dc8
	public Void .ctor() { }
}
```