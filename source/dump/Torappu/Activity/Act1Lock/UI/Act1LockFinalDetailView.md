# Act1LockFinalDetailView

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `Text _textHint`

- `Text _textType`

- `Text _textCode`

- `Text _textName`

- `Text _textDesc`

- `Text _textPlanCost`

- `Text _textApCost`

- `Text _textPt`

- `Image _imgApProtect`

- `Image _imgBlurBg`

- `Image _imgMapPreview`

- `GameObject _btnRuleGo`

- `GameObject _popupPanelsGo`

- `RectTransform _popupPanelRt`

- `GameObject _mapPreviewPanelGo`

- `GameObject _resReturnPanelGo`

- `SimpleLayoutContent _rewardList`

- `StagePreviewRankView _rankView`

- `GameObject _emptyPanel`

- `GameObject _interlockPanel`

- `SimpleLayoutContent _interlockList`

- `Act1LockAutoBattleView _autoBattleView`

- `StagePreviewApStatusBinder _apStatusView`

- `HorizontalLayoutGroup _interlockLayoutGroup`

- `ScrollRect _interlockScrollRect`

- `Single _scrollDuration`

- `Action <onBtnEnemy>k__BackingField`

- `Action <onBtnPractice>k__BackingField`

- `Action <onBtnBattle>k__BackingField`

- `Action <onAutoBattleToggle>k__BackingField`

- `Action <onBtnReward>k__BackingField`

- `Action <onInterlockUpdate>k__BackingField`

- `Act1LockDetailProperty m_property`

- `Act1LockFinalDetailModel m_detailModel`

- `Boolean m_hasInited`

- `RewardPreviewAdapter m_rewardAdapter`

- `InterlockItemAdapter m_interlockItemAdapter`

- `DirectAssetLoader m_stagePreviewMapLoader`

- `Sprite m_stagePreviewMap`

- `String m_stageId`


## Properties

- `Act1LockAutoBattleView autoBattleView`

- `Action onBtnEnemy`

- `Action onBtnPractice`

- `Action onBtnBattle`

- `Action onAutoBattleToggle`

- `Action onBtnReward`

- `Action onInterlockUpdate`


## Methods

- `Act1LockAutoBattleView get_autoBattleView()`

- `Action get_onBtnEnemy()`

- `Void set_onBtnEnemy(Action)`

- `Action get_onBtnPractice()`

- `Void set_onBtnPractice(Action)`

- `Action get_onBtnBattle()`

- `Void set_onBtnBattle(Action)`

- `Action get_onAutoBattleToggle()`

- `Void set_onAutoBattleToggle(Action)`

- `Action get_onBtnReward()`

- `Void set_onBtnReward(Action)`

- `Action get_onInterlockUpdate()`

- `Void set_onInterlockUpdate(Action)`

- `Void set_onCancelInterlock(Action`1)`

- `Void set_onSetTopMenuActive(Action`1)`

- `Void set_onJumpToDetailView(Action`1)`

- `Void _UpdateView(Act1LockFinalDetailModel)`

- `Void _UpdateInterlockView(Act1LockFinalDetailModel)`

- `Void _ClearBlurSprite()`

- `Void _ShotBlurredSprite()`

- `Void _LoadMapPreview()`

- `Void _UnloadStagePreviewMap()`

- `Void _UpdateRewardList(StageViewModel)`

- `Void _InitIfNot()`

- `Void _OnCancelInterlock(String, String)`

- `Void _ScrollToItem(Int32)`

- `Void OnBtnEnemyClick()`

- `Void OnBtnStartBattleClick()`

- `Void OnBtnStartPractiseClick()`

- `Void OnBtnAutoBattleClick()`

- `Void OnBtnRewardClick()`

- `Void OpenMapPreviewPanel()`

- `Void OpenResReturnRulePanel()`

- `Void ClosePopupPanels()`

- `Void _OnInterlockItemExpand(Int32, Boolean)`

- `Void _OnInterlockCancel(Int32)`

- `Void _OnJumpToDetailView(String)`

- `Single <_ScrollToItem>b__82_0()`

- `Void <_ScrollToItem>b__82_1(Single)`

- `Void <>xLuaBaseProxy_OnDataUpdated(Act1LockDetailProperty)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockFinalDetailView : Act1LockDetailViewBase
{
	private Text _textHint; // 0x48
	private Text _textType; // 0x50
	private Text _textCode; // 0x58
	private Text _textName; // 0x60
	private Text _textDesc; // 0x68
	private Text _textPlanCost; // 0x70
	private Text _textApCost; // 0x78
	private Text _textPt; // 0x80
	private Image _imgApProtect; // 0x88
	private Image _imgBlurBg; // 0x90
	private Image _imgMapPreview; // 0x98
	private GameObject _btnRuleGo; // 0xa0
	private GameObject _popupPanelsGo; // 0xa8
	private RectTransform _popupPanelRt; // 0xb0
	private GameObject _mapPreviewPanelGo; // 0xb8
	private GameObject _resReturnPanelGo; // 0xc0
	private SimpleLayoutContent _rewardList; // 0xc8
	private StagePreviewRankView _rankView; // 0xd0
	private GameObject _emptyPanel; // 0xd8
	private GameObject _interlockPanel; // 0xe0
	private SimpleLayoutContent _interlockList; // 0xe8
	private Act1LockAutoBattleView _autoBattleView; // 0xf0
	private StagePreviewApStatusBinder _apStatusView; // 0xf8
	private HorizontalLayoutGroup _interlockLayoutGroup; // 0x100
	private ScrollRect _interlockScrollRect; // 0x108
	private Single _scrollDuration; // 0x110
	private Action <onBtnEnemy>k__BackingField; // 0x118
	private Action <onBtnPractice>k__BackingField; // 0x120
	private Action <onBtnBattle>k__BackingField; // 0x128
	private Action <onAutoBattleToggle>k__BackingField; // 0x130
	private Action <onBtnReward>k__BackingField; // 0x138
	private Action <onInterlockUpdate>k__BackingField; // 0x140
	private Action`1 <onCancelInterlock>k__BackingField; // 0x148
	private Action`1 <onSetTopMenuActive>k__BackingField; // 0x150
	private Action`1 <onJumpToDetailView>k__BackingField; // 0x158
	private Act1LockDetailProperty m_property; // 0x160
	private Act1LockFinalDetailModel m_detailModel; // 0x168
	private Boolean m_hasInited; // 0x170
	private RewardPreviewAdapter m_rewardAdapter; // 0x178
	private InterlockItemAdapter m_interlockItemAdapter; // 0x180
	private DirectAssetLoader m_stagePreviewMapLoader; // 0x188
	private Sprite m_stagePreviewMap; // 0x190
	private String m_stageId; // 0x198
	private static DelegateBridge __Hotfix0_get_autoBattleView; // 0x0
	private static DelegateBridge __Hotfix0_get_onBtnEnemy; // 0x8
	private static DelegateBridge __Hotfix0_set_onBtnEnemy; // 0x10
	private static DelegateBridge __Hotfix0_get_onBtnPractice; // 0x18
	private static DelegateBridge __Hotfix0_set_onBtnPractice; // 0x20
	private static DelegateBridge __Hotfix0_get_onBtnBattle; // 0x28
	private static DelegateBridge __Hotfix0_set_onBtnBattle; // 0x30
	private static DelegateBridge __Hotfix0_get_onAutoBattleToggle; // 0x38
	private static DelegateBridge __Hotfix0_set_onAutoBattleToggle; // 0x40
	private static DelegateBridge __Hotfix0_get_onBtnReward; // 0x48
	private static DelegateBridge __Hotfix0_set_onBtnReward; // 0x50
	private static DelegateBridge __Hotfix0_get_onInterlockUpdate; // 0x58
	private static DelegateBridge __Hotfix0_set_onInterlockUpdate; // 0x60
	private static DelegateBridge __Hotfix0_get_onCancelInterlock; // 0x68
	private static DelegateBridge __Hotfix0_set_onCancelInterlock; // 0x70
	private static DelegateBridge __Hotfix0_get_onSetTopMenuActive; // 0x78
	private static DelegateBridge __Hotfix0_set_onSetTopMenuActive; // 0x80
	private static DelegateBridge __Hotfix0_get_onJumpToDetailView; // 0x88
	private static DelegateBridge __Hotfix0_set_onJumpToDetailView; // 0x90
	private static DelegateBridge __Hotfix0_OnDataUpdated; // 0x98
	private static DelegateBridge __Hotfix0__UpdateView; // 0xa0
	private static DelegateBridge __Hotfix0__UpdateInterlockView; // 0xa8
	private static DelegateBridge __Hotfix0__ClearBlurSprite; // 0xb0
	private static DelegateBridge __Hotfix0__ShotBlurredSprite; // 0xb8
	private static DelegateBridge __Hotfix0__LoadMapPreview; // 0xc0
	private static DelegateBridge __Hotfix0__UnloadStagePreviewMap; // 0xc8
	private static DelegateBridge __Hotfix0__UpdateRewardList; // 0xd0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0xd8
	private static DelegateBridge __Hotfix0__OnCancelInterlock; // 0xe0
	private static DelegateBridge __Hotfix0__ScrollToItem; // 0xe8
	private static DelegateBridge __Hotfix0_OnBtnEnemyClick; // 0xf0
	private static DelegateBridge __Hotfix0_OnBtnStartBattleClick; // 0xf8
	private static DelegateBridge __Hotfix0_OnBtnStartPractiseClick; // 0x100
	private static DelegateBridge __Hotfix0_OnBtnAutoBattleClick; // 0x108
	private static DelegateBridge __Hotfix0_OnBtnRewardClick; // 0x110
	private static DelegateBridge __Hotfix0_OpenMapPreviewPanel; // 0x118
	private static DelegateBridge __Hotfix0_OpenResReturnRulePanel; // 0x120
	private static DelegateBridge __Hotfix0_ClosePopupPanels; // 0x128
	private static DelegateBridge __Hotfix0__OnInterlockItemExpand; // 0x130
	private static DelegateBridge __Hotfix0__OnInterlockCancel; // 0x138
	private static DelegateBridge __Hotfix0__OnJumpToDetailView; // 0x140
	private static DelegateBridge _c__Hotfix0_ctor; // 0x148

	public Act1LockAutoBattleView autoBattleView { get; }
	private Action onBtnEnemy { get; set; }
	private Action onBtnPractice { get; set; }
	private Action onBtnBattle { get; set; }
	private Action onAutoBattleToggle { get; set; }
	private Action onBtnReward { get; set; }
	private Action onInterlockUpdate { get; set; }
	private Action`1 onCancelInterlock { get; set; }
	private Action`1 onSetTopMenuActive { get; set; }
	private Action`1 onJumpToDetailView { get; set; }

	// RVA: 0x339edd8 VA: 0x75959b6dd8
	public Act1LockAutoBattleView get_autoBattleView() { }
	// RVA: 0x33aa770 VA: 0x75959c2770
	private Action get_onBtnEnemy() { }
	// RVA: 0x339e934 VA: 0x75959b6934
	public Void set_onBtnEnemy(Action value) { }
	// RVA: 0x33aa7d8 VA: 0x75959c27d8
	private Action get_onBtnPractice() { }
	// RVA: 0x339eac0 VA: 0x75959b6ac0
	public Void set_onBtnPractice(Action value) { }
	// RVA: 0x33aa840 VA: 0x75959c2840
	private Action get_onBtnBattle() { }
	// RVA: 0x339eb44 VA: 0x75959b6b44
	public Void set_onBtnBattle(Action value) { }
	// RVA: 0x33aa8a8 VA: 0x75959c28a8
	private Action get_onAutoBattleToggle() { }
	// RVA: 0x339ea3c VA: 0x75959b6a3c
	public Void set_onAutoBattleToggle(Action value) { }
	// RVA: 0x33aa910 VA: 0x75959c2910
	private Action get_onBtnReward() { }
	// RVA: 0x339e9b8 VA: 0x75959b69b8
	public Void set_onBtnReward(Action value) { }
	// RVA: 0x33aa978 VA: 0x75959c2978
	private Action get_onInterlockUpdate() { }
	// RVA: 0x339ed54 VA: 0x75959b6d54
	public Void set_onInterlockUpdate(Action value) { }
	// RVA: 0x33aa9e0 VA: 0x75959c29e0
	private Action`1 get_onCancelInterlock() { }
	// RVA: 0x339ebc8 VA: 0x75959b6bc8
	public Void set_onCancelInterlock(Action`1 value) { }
	// RVA: 0x33aaa48 VA: 0x75959c2a48
	private Action`1 get_onSetTopMenuActive() { }
	// RVA: 0x339ec4c VA: 0x75959b6c4c
	public Void set_onSetTopMenuActive(Action`1 value) { }
	// RVA: 0x33aaab0 VA: 0x75959c2ab0
	private Action`1 get_onJumpToDetailView() { }
	// RVA: 0x339ecd0 VA: 0x75959b6cd0
	public Void set_onJumpToDetailView(Action`1 value) { }
	// RVA: 0x33aab18 VA: 0x75959c2b18
	protected override Void OnDataUpdated(Act1LockDetailProperty property) { }
	// RVA: 0x33ab038 VA: 0x75959c3038
	private Void _UpdateView(Act1LockFinalDetailModel detailModel) { }
	// RVA: 0x33aae74 VA: 0x75959c2e74
	private Void _UpdateInterlockView(Act1LockFinalDetailModel detailModel) { }
	// RVA: 0x33ab510 VA: 0x75959c3510
	private Void _ClearBlurSprite() { }
	// RVA: 0x33ab614 VA: 0x75959c3614
	private Void _ShotBlurredSprite() { }
	// RVA: 0x33ab688 VA: 0x75959c3688
	private Void _LoadMapPreview() { }
	// RVA: 0x33ab72c VA: 0x75959c372c
	private Void _UnloadStagePreviewMap() { }
	// RVA: 0x33ab2e8 VA: 0x75959c32e8
	private Void _UpdateRewardList(StageViewModel selectedStageModel) { }
	// RVA: 0x33aac58 VA: 0x75959c2c58
	private Void _InitIfNot() { }
	// RVA: 0x33ab9c4 VA: 0x75959c39c4
	private Void _OnCancelInterlock(String stageId, String stageKey) { }
	// RVA: 0x33abc5c VA: 0x75959c3c5c
	private Void _ScrollToItem(Int32 position) { }
	// RVA: 0x33abf54 VA: 0x75959c3f54
	public Void OnBtnEnemyClick() { }
	// RVA: 0x33abff0 VA: 0x75959c3ff0
	public Void OnBtnStartBattleClick() { }
	// RVA: 0x33ac08c VA: 0x75959c408c
	public Void OnBtnStartPractiseClick() { }
	// RVA: 0x33ac128 VA: 0x75959c4128
	public Void OnBtnAutoBattleClick() { }
	// RVA: 0x33ac1c4 VA: 0x75959c41c4
	public Void OnBtnRewardClick() { }
	// RVA: 0x33ac260 VA: 0x75959c4260
	public Void OpenMapPreviewPanel() { }
	// RVA: 0x33ac334 VA: 0x75959c4334
	public Void OpenResReturnRulePanel() { }
	// RVA: 0x33ac400 VA: 0x75959c4400
	public Void ClosePopupPanels() { }
	// RVA: 0x33ac4ac VA: 0x75959c44ac
	private Void _OnInterlockItemExpand(Int32 position, Boolean isExpand) { }
	// RVA: 0x33ac5b0 VA: 0x75959c45b0
	private Void _OnInterlockCancel(Int32 position) { }
	// RVA: 0x33ac688 VA: 0x75959c4688
	private Void _OnJumpToDetailView(String stageId) { }
	// RVA: 0x33ac740 VA: 0x75959c4740
	public Void .ctor() { }
	// RVA: 0x33ac7f4 VA: 0x75959c47f4
	private Single <_ScrollToItem>b__82_0() { }
	// RVA: 0x33ac810 VA: 0x75959c4810
	private Void <_ScrollToItem>b__82_1(Single val) { }
	// RVA: 0x33ac82c VA: 0x75959c482c
	private Void <>xLuaBaseProxy_OnDataUpdated(Act1LockDetailProperty P0) { }
}
```