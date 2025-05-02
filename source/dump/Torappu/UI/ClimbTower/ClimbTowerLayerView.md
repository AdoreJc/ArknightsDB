# ClimbTowerLayerView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Text _textLayerNum`

- `Text _textLastLayerNum`

- `Text _textLayerTotalNum`

- `Text _textLayerName`

- `Text _textLayerCode`

- `Text _textLayerDesc`

- `Text _txtHardDesc`

- `Text _txtDangerDesc`

- `Image _towerIcon`

- `Image _imgFlash`

- `GameObject _panelHardTag`

- `Image _towerBkg`

- `Image _imageLevelPreview`

- `Image _imageLevelMapTips`

- `Image _imageMapTipsBkg`

- `GameObject _pnlMapTips`

- `GameObject _panelCurrLayerDesc`

- `Single _cardScaleFactor`

- `GameObject _panelIconNormal`

- `GameObject _panelIconTraining`

- `GameObject _panelBtnUp`

- `GameObject _panelBtnDown`

- `GameObject _panelList`

- `RewardItemView _rewardItem1`

- `RewardItemView _rewardItem2`

- `GameObject _panelEmpty`

- `Text _textSettle`

- `CanvasGroup _canvasDanger`

- `Text _textEntranceDot`

- `GameObject _imgLight`

- `ClimbTowerBackgroundController _bkgController`

- `ClimbTowerTowerLayerStack _layerStackPrefab`

- `RectTransform _panelLayerStackViewHolder`

- `ClimbTowerTowerLayerSelectArrowSimple _selectArrowPrefab`

- `ClimbTowerTowerLayerGodCardTipsWithAttach _godCardTipsPrefab`

- `String m_cachedTowerId`

- `String m_cachedLevelId`

- `ClimbTowerLayerViewModel m_cachedModel`

- `Boolean m_cachedIsHardMode`

- `Sprite m_spriteMapTip`

- `Adapter m_adapter`

- `Boolean m_inited`

- `ClimbTowerLayerState m_bindState`

- `FadeSwitchTween m_dangerSwitchTween`

- `ClimbTowerTowerLayerStack m_towerLayerView`

- `UIPage <page>k__BackingField`


## Properties

- `ClimbTowerLayerState bindState`

- `UIPage page`


## Methods

- `Void set_bindState(ClimbTowerLayerState)`

- `UIPage get_page()`

- `Void set_page(UIPage)`

- `Void _InitIfNot(ClimbTowerLayerViewModel)`

- `Void _LoadPreviewMap(String)`

- `Void _UnloadPreviewMap()`

- `Void _ShotBlurredSprite()`

- `Void _ClearBlurSprite()`

- `Void _SetGraphicsColorWithMode(Boolean)`

- `Void OnBtnMapTipsClicked()`

- `Void OnBtnExitMapTipsClicked()`

- `Void AnimRefreshEntranceDot(Int32)`

- `Void AnimResetToBegin(EntranceConfig)`

- `Void AnimResetToEnd(EntranceConfig)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerLayerView : DataBinder`1
{
	private const String MAX_LAYER_FORMAT; // 0x0
	private const Char ENTRANCE_DOT; // 0x0
	private static readonly Color COLOR_NORMAL; // 0x0
	private static readonly Color COLOR_MAX; // 0x10
	private const Int32 DANGER_LAYER_COUNT; // 0x0
	private const Int32 MAX_ENTRANCE_DOT; // 0x0
	private static readonly Color COLOR_NORMAL_FLASH; // 0x20
	private static readonly Color COLOR_HARD_FLASH; // 0x30
	private Text _textLayerNum; // 0x20
	private Text _textLastLayerNum; // 0x28
	private Text _textLayerTotalNum; // 0x30
	private Text _textLayerName; // 0x38
	private Text _textLayerCode; // 0x40
	private Text _textLayerDesc; // 0x48
	private Text _txtHardDesc; // 0x50
	private Text _txtDangerDesc; // 0x58
	private Image _towerIcon; // 0x60
	private Image _imgFlash; // 0x68
	private GameObject _panelHardTag; // 0x70
	private Image _towerBkg; // 0x78
	private Image _imageLevelPreview; // 0x80
	private Image _imageLevelMapTips; // 0x88
	private Image _imageMapTipsBkg; // 0x90
	private GameObject _pnlMapTips; // 0x98
	private GameObject _panelCurrLayerDesc; // 0xa0
	private Single _cardScaleFactor; // 0xa8
	private GameObject _panelIconNormal; // 0xb0
	private GameObject _panelIconTraining; // 0xb8
	private GameObject _panelBtnUp; // 0xc0
	private GameObject _panelBtnDown; // 0xc8
	private GameObject _panelList; // 0xd0
	private RewardItemView _rewardItem1; // 0xd8
	private RewardItemView _rewardItem2; // 0xe0
	private GameObject _panelEmpty; // 0xe8
	private Text _textSettle; // 0xf0
	private CanvasGroup _canvasDanger; // 0xf8
	private Text _textEntranceDot; // 0x100
	private GameObject _imgLight; // 0x108
	private ClimbTowerBackgroundController _bkgController; // 0x110
	private ClimbTowerTowerLayerStack _layerStackPrefab; // 0x118
	private RectTransform _panelLayerStackViewHolder; // 0x120
	private ClimbTowerTowerLayerSelectArrowSimple _selectArrowPrefab; // 0x128
	private ClimbTowerTowerLayerGodCardTipsWithAttach _godCardTipsPrefab; // 0x130
	private Graphic[] _modeRelatedGraphics; // 0x138
	private String m_cachedTowerId; // 0x140
	private String m_cachedLevelId; // 0x148
	private ClimbTowerLayerViewModel m_cachedModel; // 0x150
	private List`1 m_cachedReward; // 0x158
	private Boolean m_cachedIsHardMode; // 0x160
	private Sprite m_spriteMapTip; // 0x168
	private Adapter m_adapter; // 0x170
	private Boolean m_inited; // 0x178
	private ClimbTowerLayerState m_bindState; // 0x180
	private FadeSwitchTween m_dangerSwitchTween; // 0x188
	private ClimbTowerTowerLayerStack m_towerLayerView; // 0x190
	private UIPage <page>k__BackingField; // 0x198
	private static DelegateBridge __Hotfix0_set_bindState; // 0x40
	private static DelegateBridge __Hotfix0_get_page; // 0x48
	private static DelegateBridge __Hotfix0_set_page; // 0x50
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x58
	private static DelegateBridge __Hotfix0__LoadPreviewMap; // 0x60
	private static DelegateBridge __Hotfix0__UnloadPreviewMap; // 0x68
	private static DelegateBridge __Hotfix0__ShotBlurredSprite; // 0x70
	private static DelegateBridge __Hotfix0__ClearBlurSprite; // 0x78
	private static DelegateBridge __Hotfix0__SetGraphicsColorWithMode; // 0x80
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x88
	private static DelegateBridge __Hotfix0_OnBtnMapTipsClicked; // 0x90
	private static DelegateBridge __Hotfix0_OnBtnExitMapTipsClicked; // 0x98
	private static DelegateBridge __Hotfix0_AnimRefreshEntranceDot; // 0xa0
	private static DelegateBridge __Hotfix0_AnimResetToBegin; // 0xa8
	private static DelegateBridge __Hotfix0_AnimResetToEnd; // 0xb0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb8

	public ClimbTowerLayerState bindState { set; }
	private UIPage page { get; set; }

	// RVA: 0x2c6d18c VA: 0x759528518c
	public Void set_bindState(ClimbTowerLayerState value) { }
	// RVA: 0x2c6d220 VA: 0x7595285220
	private UIPage get_page() { }
	// RVA: 0x2c6d298 VA: 0x7595285298
	public Void set_page(UIPage value) { }
	// RVA: 0x2c6d32c VA: 0x759528532c
	private Void _InitIfNot(ClimbTowerLayerViewModel model) { }
	// RVA: 0x2c6d900 VA: 0x7595285900
	private Void _LoadPreviewMap(String mapPreviewId) { }
	// RVA: 0x2c6daa8 VA: 0x7595285aa8
	private Void _UnloadPreviewMap() { }
	// RVA: 0x2c6dbd0 VA: 0x7595285bd0
	private Void _ShotBlurredSprite() { }
	// RVA: 0x2c6dc54 VA: 0x7595285c54
	private Void _ClearBlurSprite() { }
	// RVA: 0x2c6dd68 VA: 0x7595285d68
	private Void _SetGraphicsColorWithMode(Boolean isHardMode) { }
	// RVA: 0x2c6df50 VA: 0x7595285f50
	public override Void OnValueChanged(ClimbTowerLayerProperty property) { }
	// RVA: 0x2c6e80c VA: 0x759528680c
	public Void OnBtnMapTipsClicked() { }
	// RVA: 0x2c6e904 VA: 0x7595286904
	public Void OnBtnExitMapTipsClicked() { }
	// RVA: 0x2c6e9f4 VA: 0x75952869f4
	public Void AnimRefreshEntranceDot(Int32 count) { }
	// RVA: 0x2c6eaac VA: 0x7595286aac
	public Void AnimResetToBegin(EntranceConfig entranceConfig) { }
	// RVA: 0x2c6eb4c VA: 0x7595286b4c
	public Void AnimResetToEnd(EntranceConfig entranceConfig) { }
	// RVA: 0x2c6ebdc VA: 0x7595286bdc
	public Void .ctor() { }
	// RVA: 0x2c6ec88 VA: 0x7595286c88
	private static Void .cctor() { }
}
```