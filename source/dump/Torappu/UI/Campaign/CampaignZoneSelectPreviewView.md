# CampaignZoneSelectPreviewView

**Namespace:** `Torappu.UI.Campaign`


## Fields

- `Text _stageTypeText`

- `Text _stageZoneText`

- `Text _stageNameText`

- `Text _stageDescText`

- `SimpleLayoutContent _rewardGrid`

- `Image _imageMapPreview`

- `GameObject _starTips`

- `GameObject _autoTips`

- `GameObject _mapTips`

- `Image _imageMapTips`

- `Text _textDangerDesc`

- `Image _backTips`

- `CanvasGroup _canvasGroup`

- `GameObject _bossIcon`

- `Button _btnStartBattleAp`

- `Text _apCostText`

- `RectTransform _containerStartBattleEt`

- `StagePreviewCampaignSummaryInfoView _campaignPreviewInfo`

- `StagePreviewCampaignBreakDetailPanel _campaignBreakDetailPanel`

- `GameObject _previewPage`

- `SpriteHub m_enemySpineImageHub`

- `SpriteHub m_itemIconHub`

- `RewardPreviewAdapter m_rewardAdapter`

- `StageStartBattleETButton m_btnStartBattleEt`

- `Sprite m_stagePreviewMap`

- `DirectAssetLoader m_stagePreviewMapLoader`

- `CampaignStateViewModel m_campViewModel`

- `Boolean m_isInited`

- `String m_selectedStageIdCache`

- `Boolean m_cacheState`

- `Tween m_cacheTween`

- `Boolean m_autoOpenBreaking`


## Methods

- `Void OnEnable()`

- `Void _InitIfNot()`

- `Void OnDestroy()`

- `Void OpenAutoTips()`

- `Void OpenStarTips()`

- `Void OpenMapTips()`

- `Void CloseTips()`

- `Void OnCampaignBreakDetailsClick()`

- `Void _ShotBlurredSprite()`

- `Void _ClearBlurSprite()`

- `Void RefreshView(CampaignStageMapViewModel, CampaignZoneMapViewModel)`

- `Void _RenderCampaign(CampaignStateViewModel)`

- `Boolean OnZoneViewChanged(CampaignStageMapViewModel, CampaignZoneMapViewModel)`

- `Boolean SelectStageViewModel(ZoneViewModel, out)`

- `Void OpenCampaignImmediate()`

- `Void UpdateAnimatorState(Boolean)`

- `Void _UnloadStagePreviewMap()`

- `Void _LoadStagePreviewMap(String)`

- `String _DisplayCostValueFormat(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Campaign
public class CampaignZoneSelectPreviewView : DataBinder`1
{
	private Text _stageTypeText; // 0x20
	private Text _stageZoneText; // 0x28
	private Text _stageNameText; // 0x30
	private Text _stageDescText; // 0x38
	private SimpleLayoutContent _rewardGrid; // 0x40
	private Image _imageMapPreview; // 0x48
	private GameObject _starTips; // 0x50
	private GameObject _autoTips; // 0x58
	private GameObject _mapTips; // 0x60
	private Image _imageMapTips; // 0x68
	private Text _textDangerDesc; // 0x70
	private Image _backTips; // 0x78
	private CanvasGroup _canvasGroup; // 0x80
	private GameObject _bossIcon; // 0x88
	private Button _btnStartBattleAp; // 0x90
	private Text _apCostText; // 0x98
	private RectTransform _containerStartBattleEt; // 0xa0
	private StagePreviewCampaignSummaryInfoView _campaignPreviewInfo; // 0xa8
	private StagePreviewCampaignBreakDetailPanel _campaignBreakDetailPanel; // 0xb0
	private GameObject _previewPage; // 0xb8
	private SpriteHub m_enemySpineImageHub; // 0xc0
	private SpriteHub m_itemIconHub; // 0xc8
	private RewardPreviewAdapter m_rewardAdapter; // 0xd0
	private StageStartBattleETButton m_btnStartBattleEt; // 0xd8
	private Sprite m_stagePreviewMap; // 0xe0
	private DirectAssetLoader m_stagePreviewMapLoader; // 0xe8
	private CampaignStateViewModel m_campViewModel; // 0xf0
	private Boolean m_isInited; // 0xf8
	protected String m_selectedStageIdCache; // 0x100
	protected Boolean m_cacheState; // 0x108
	private Tween m_cacheTween; // 0x110
	private Boolean m_autoOpenBreaking; // 0x118
	private static DelegateBridge __Hotfix0_OnEnable; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x10
	private static DelegateBridge __Hotfix0_OpenAutoTips; // 0x18
	private static DelegateBridge __Hotfix0_OpenStarTips; // 0x20
	private static DelegateBridge __Hotfix0_OpenMapTips; // 0x28
	private static DelegateBridge __Hotfix0_CloseTips; // 0x30
	private static DelegateBridge __Hotfix0_OnCampaignBreakDetailsClick; // 0x38
	private static DelegateBridge __Hotfix0__ShotBlurredSprite; // 0x40
	private static DelegateBridge __Hotfix0__ClearBlurSprite; // 0x48
	private static DelegateBridge __Hotfix0_RefreshView; // 0x50
	private static DelegateBridge __Hotfix0__RenderCampaign; // 0x58
	private static DelegateBridge __Hotfix0_OnZoneViewChanged; // 0x60
	private static DelegateBridge __Hotfix0_SelectStageViewModel; // 0x68
	private static DelegateBridge __Hotfix0_OpenCampaignImmediate; // 0x70
	private static DelegateBridge __Hotfix0_UpdateAnimatorState; // 0x78
	private static DelegateBridge __Hotfix0__LoadSprites; // 0x80
	private static DelegateBridge __Hotfix0__UnloadStagePreviewMap; // 0x88
	private static DelegateBridge __Hotfix0__LoadStagePreviewMap; // 0x90
	private static DelegateBridge __Hotfix0__DisplayCostValueFormat; // 0x98
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8


	// RVA: 0x2e52778 VA: 0x759546a778
	private Void OnEnable() { }
	// RVA: 0x2e52810 VA: 0x759546a810
	protected Void _InitIfNot() { }
	// RVA: 0x2e529e0 VA: 0x759546a9e0
	private Void OnDestroy() { }
	// RVA: 0x2e52b64 VA: 0x759546ab64
	public Void OpenAutoTips() { }
	// RVA: 0x2e52c70 VA: 0x759546ac70
	public Void OpenStarTips() { }
	// RVA: 0x2e52d08 VA: 0x759546ad08
	public Void OpenMapTips() { }
	// RVA: 0x2e52da0 VA: 0x759546ada0
	public Void CloseTips() { }
	// RVA: 0x2e52e58 VA: 0x759546ae58
	public Void OnCampaignBreakDetailsClick() { }
	// RVA: 0x2e52bfc VA: 0x759546abfc
	private Void _ShotBlurredSprite() { }
	// RVA: 0x2e52a60 VA: 0x759546aa60
	private Void _ClearBlurSprite() { }
	// RVA: 0x2e52ee0 VA: 0x759546aee0
	protected Void RefreshView(CampaignStageMapViewModel campStageViewModel, CampaignZoneMapViewModel zoneViewModel) { }
	// RVA: 0x2e53588 VA: 0x759546b588
	private Void _RenderCampaign(CampaignStateViewModel campViewModel) { }
	// RVA: 0x2e53610 VA: 0x759546b610
	protected Boolean OnZoneViewChanged(CampaignStageMapViewModel campViewModel, CampaignZoneMapViewModel zoneViewModel) { }
	// RVA: 0x2e539d8 VA: 0x759546b9d8
	protected Boolean SelectStageViewModel(ZoneViewModel zoneModel, out StageViewModel stageModel) { }
	// RVA: 0x2e53a98 VA: 0x759546ba98
	public Void OpenCampaignImmediate() { }
	// RVA: 0x2e53730 VA: 0x759546b730
	protected Void UpdateAnimatorState(Boolean active) { }
	// RVA: 0x2e53b38 VA: 0x759546bb38
	private Sprite[] _LoadSprites(String[] ids, SpriteHub spriteHub) { }
	// RVA: 0x2e53d50 VA: 0x759546bd50
	private Void _UnloadStagePreviewMap() { }
	// RVA: 0x2e534bc VA: 0x759546b4bc
	private Void _LoadStagePreviewMap(String stageId) { }
	// RVA: 0x2e532d4 VA: 0x759546b2d4
	private String _DisplayCostValueFormat(Int32 value) { }
	// RVA: 0x2e53e4c VA: 0x759546be4c
	public override Void OnValueChanged(CampaignSelectStageViewProperty property) { }
	// RVA: 0x2e53f34 VA: 0x759546bf34
	public Void .ctor() { }
}
```