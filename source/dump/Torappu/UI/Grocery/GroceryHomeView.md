# GroceryHomeView

**Namespace:** `Torappu.UI.Grocery`


## Fields

- `Text _textDay`

- `GameObject _panelTitleNormal`

- `GameObject _panelTitleRewardOnly`

- `GameObject _panelMileStoneSaling`

- `GameObject _panelMileStoneNextRewardNormal`

- `Text _textMileStoneNextPt`

- `GameObject _panelMileStoneNextRewardComplete`

- `GameObject _panelRewardOnlyMileStone`

- `UICommonTrackPoint _mileStoneTrackPoint`

- `Text _textMileStonePoint`

- `Text _textMileStonePointName`

- `RectTransform _itemCardContainer`

- `GameObject _panelDailyReward`

- `GameObject _panelDailyRewardComplete`

- `CanvasGroup _canvasGroupDailyReward`

- `Single _itemCardScale`

- `SimpleLayoutContent _shopIconContent`

- `SimpleLayoutContent _goodContent`

- `GameObject _panelCurrentGood`

- `GameObject _panelRewardOnlyGood`

- `GameObject _panelSaleBtn`

- `GameObject _panelSaleBtnStartImg`

- `GameObject _panelSaleBtnContinueImg`

- `GameObject _panelAfterSaleBtn`

- `GameObject _panelRewardOnlySaleBtn`

- `Text _textNextSaleRemainTimeDesc`

- `GameObject _panelNextSaleRemainTimeDesc`

- `UIStateFinder m_stateFinder`

- `TrackPointViewProperty m_mileStoneProperty`

- `UIItemCard m_rewardItemCard`

- `ShopIconAdapter m_shopIconAdapter`

- `GoodAdapter m_goodAdapter`

- `Boolean m_hasInited`


## Methods

- `Void OnLaunchBtnClicked()`

- `Void OnMileStoneBtnClicked()`

- `Void OnSaleBtnClicked()`

- `Void _InitIfNot()`

- `Void _OnDailyRewardItemCardClick(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Grocery
public class GroceryHomeView : DataBinder`1, IHotfixable
{
	private const Single ALPHA_DAILY_REWARD_COMPLETE; // 0x0
	private const Single ALPHA_DAILY_REWARD_UNCOMPLETE; // 0x0
	private Text _textDay; // 0x20
	private GameObject _panelTitleNormal; // 0x28
	private GameObject _panelTitleRewardOnly; // 0x30
	private GameObject _panelMileStoneSaling; // 0x38
	private GameObject _panelMileStoneNextRewardNormal; // 0x40
	private Text _textMileStoneNextPt; // 0x48
	private GameObject _panelMileStoneNextRewardComplete; // 0x50
	private GameObject _panelRewardOnlyMileStone; // 0x58
	private UICommonTrackPoint _mileStoneTrackPoint; // 0x60
	private Text _textMileStonePoint; // 0x68
	private Text _textMileStonePointName; // 0x70
	private RectTransform _itemCardContainer; // 0x78
	private GameObject _panelDailyReward; // 0x80
	private GameObject _panelDailyRewardComplete; // 0x88
	private CanvasGroup _canvasGroupDailyReward; // 0x90
	private Single _itemCardScale; // 0x98
	private SimpleLayoutContent _shopIconContent; // 0xa0
	private SimpleLayoutContent _goodContent; // 0xa8
	private GameObject _panelCurrentGood; // 0xb0
	private GameObject _panelRewardOnlyGood; // 0xb8
	private GameObject _panelSaleBtn; // 0xc0
	private GameObject _panelSaleBtnStartImg; // 0xc8
	private GameObject _panelSaleBtnContinueImg; // 0xd0
	private GameObject _panelAfterSaleBtn; // 0xd8
	private GameObject _panelRewardOnlySaleBtn; // 0xe0
	private Text _textNextSaleRemainTimeDesc; // 0xe8
	private GameObject _panelNextSaleRemainTimeDesc; // 0xf0
	private UIStateFinder m_stateFinder; // 0xf8
	private TrackPointViewProperty m_mileStoneProperty; // 0x108
	private UIItemCard m_rewardItemCard; // 0x110
	private List`1 m_cacheShopModel; // 0x118
	private List`1 m_cacheGoodModel; // 0x120
	private ShopIconAdapter m_shopIconAdapter; // 0x128
	private GoodAdapter m_goodAdapter; // 0x130
	private Boolean m_hasInited; // 0x138
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0_OnLaunchBtnClicked; // 0x8
	private static DelegateBridge __Hotfix0_OnMileStoneBtnClicked; // 0x10
	private static DelegateBridge __Hotfix0_OnSaleBtnClicked; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__OnDailyRewardItemCardClick; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2862f84 VA: 0x7594e7af84
	public override Void OnValueChanged(GroceryHomeProperty property) { }
	// RVA: 0x2863664 VA: 0x7594e7b664
	public Void OnLaunchBtnClicked() { }
	// RVA: 0x2863750 VA: 0x7594e7b750
	public Void OnMileStoneBtnClicked() { }
	// RVA: 0x28637f4 VA: 0x7594e7b7f4
	public Void OnSaleBtnClicked() { }
	// RVA: 0x2863384 VA: 0x7594e7b384
	private Void _InitIfNot() { }
	// RVA: 0x28639c0 VA: 0x7594e7b9c0
	private Void _OnDailyRewardItemCardClick(Int32 position) { }
	// RVA: 0x2863a7c VA: 0x7594e7ba7c
	public Void .ctor() { }
}
```