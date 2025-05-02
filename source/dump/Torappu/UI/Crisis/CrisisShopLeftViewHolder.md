# CrisisShopLeftViewHolder

**Namespace:** `Torappu.UI.Crisis`


## Fields

- `Text _name`

- `Text _description`

- `Text _usage`

- `CrisisShopLeftCharView _charView`

- `CrisisShopLeftProgressView _progressView`

- `GameObject _normalView`

- `CrisisShopLeftFurnView _furnView`

- `ShopDetailItemPileView _pileView`

- `Transform _pileViewContainer`

- `ShopDetailItemPileView m_pileView`

- `Boolean m_isInited`


## Methods

- `Void _InitedIfNot()`

- `Void Render(CrisisShopWrapped)`

- `Void RenderNormalObj(CrisisShopWrapped)`

- `Void RenderCommonObj(CrisisShopWrapped)`

- `Void RenderCharAndSkin(CrisisShopWrapped)`

- `Void RenderFurn(CrisisShopWrapped)`

- `Void RenderProgressObj(CrisisShopWrapped)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Crisis
public class CrisisShopLeftViewHolder : MonoBehaviour, IHotfixable
{
	private Text _name; // 0x18
	private Text _description; // 0x20
	private Text _usage; // 0x28
	private CrisisShopLeftCharView _charView; // 0x30
	private CrisisShopLeftProgressView _progressView; // 0x38
	private GameObject _normalView; // 0x40
	private CrisisShopLeftFurnView _furnView; // 0x48
	private ShopDetailItemPileView _pileView; // 0x50
	private Transform _pileViewContainer; // 0x58
	private ShopDetailItemPileView m_pileView; // 0x60
	private Boolean m_isInited; // 0x68
	private static DelegateBridge __Hotfix0__InitedIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge __Hotfix0_RenderNormalObj; // 0x10
	private static DelegateBridge __Hotfix0_RenderCommonObj; // 0x18
	private static DelegateBridge __Hotfix0_RenderCharAndSkin; // 0x20
	private static DelegateBridge __Hotfix0_RenderFurn; // 0x28
	private static DelegateBridge __Hotfix0_RenderProgressObj; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2c396e8 VA: 0x75952516e8
	private Void _InitedIfNot() { }
	// RVA: 0x2c397d0 VA: 0x75952517d0
	public Void Render(CrisisShopWrapped shopViewModel) { }
	// RVA: 0x2c39a88 VA: 0x7595251a88
	public Void RenderNormalObj(CrisisShopWrapped shopViewModel) { }
	// RVA: 0x2c39e30 VA: 0x7595251e30
	public Void RenderCommonObj(CrisisShopWrapped shopViewModel) { }
	// RVA: 0x2c39c78 VA: 0x7595251c78
	public Void RenderCharAndSkin(CrisisShopWrapped shopViewModel) { }
	// RVA: 0x2c39d54 VA: 0x7595251d54
	public Void RenderFurn(CrisisShopWrapped shopViewModel) { }
	// RVA: 0x2c39894 VA: 0x7595251894
	public Void RenderProgressObj(CrisisShopWrapped shopViewModel) { }
	// RVA: 0x2c3a7f8 VA: 0x75952527f8
	public Void .ctor() { }
}
```