# Act1LockNormalDetailView

**Namespace:** `Torappu.Activity.Act1Lock.UI`


## Fields

- `Text _textType`

- `Text _textCode`

- `Text _textName`

- `Text _textDifficulty`

- `Text _textDesc`

- `Text _textPlanCost`

- `Text _textApCost`

- `Text _textPt`

- `Image _imgApProtect`

- `Image _imgMapPreview`

- `SimpleLayoutContent _rewardList`

- `StagePreviewRankView _rankView`

- `UIAnimationLocation _animation`

- `Act1LockAutoBattleView _autoBattleView`

- `StagePreviewApStatusBinder _apStatusView`

- `Action <onBtnEnemy>k__BackingField`

- `Action <onBtnPractice>k__BackingField`

- `Action <onBtnBattle>k__BackingField`

- `Action <onAutoBattleToggle>k__BackingField`

- `Action <onBtnReward>k__BackingField`

- `Act1LockDetailProperty m_property`

- `Act1LockNormalDetailModel m_detailModel`

- `Boolean m_hasInited`

- `RewardPreviewAdapter m_rewardAdapter`

- `DirectAssetLoader m_stagePreviewMapLoader`

- `Sprite m_stagePreviewMap`

- `String m_stageId`

- `Tween m_expandTween`

- `Boolean m_isAniming`


## Properties

- `Act1LockAutoBattleView autoBattleView`

- `Action onBtnEnemy`

- `Action onBtnPractice`

- `Action onBtnBattle`

- `Action onAutoBattleToggle`

- `Action onBtnReward`


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

- `Void _UpdateView(Act1LockNormalDetailModel)`

- `Void _CleanAnimTween()`

- `Void _LoadMapPreview(String)`

- `Void _UnloadStagePreviewMap()`

- `Void _UpdateRewardList(StageViewModel)`

- `Void _InitIfNot()`

- `Void _SwitchExpandStatus()`

- `Void OnBtnEnemyClick()`

- `Void OnBtnStartBattleClick()`

- `Void OnBtnStartPractiseClick()`

- `Void OnBtnExpandClick()`

- `Void OnBtnAutoBattleClick()`

- `Void OnBtnRewardClick()`

- `Void <>xLuaBaseProxy_OnDataUpdated(Act1LockDetailProperty)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1Lock.UI
public class Act1LockNormalDetailView : Act1LockDetailViewBase
{
	private Text _textType; // 0x48
	private Text _textCode; // 0x50
	private Text _textName; // 0x58
	private Text _textDifficulty; // 0x60
	private Text _textDesc; // 0x68
	private Text _textPlanCost; // 0x70
	private Text _textApCost; // 0x78
	private Text _textPt; // 0x80
	private Image _imgApProtect; // 0x88
	private Image _imgMapPreview; // 0x90
	private SimpleLayoutContent _rewardList; // 0x98
	private StagePreviewRankView _rankView; // 0xa0
	private UIAnimationLocation _animation; // 0xa8
	private Act1LockAutoBattleView _autoBattleView; // 0xb8
	private StagePreviewApStatusBinder _apStatusView; // 0xc0
	private Action <onBtnEnemy>k__BackingField; // 0xc8
	private Action <onBtnPractice>k__BackingField; // 0xd0
	private Action <onBtnBattle>k__BackingField; // 0xd8
	private Action <onAutoBattleToggle>k__BackingField; // 0xe0
	private Action <onBtnReward>k__BackingField; // 0xe8
	private Act1LockDetailProperty m_property; // 0xf0
	private Act1LockNormalDetailModel m_detailModel; // 0xf8
	private Boolean m_hasInited; // 0x100
	private RewardPreviewAdapter m_rewardAdapter; // 0x108
	private DirectAssetLoader m_stagePreviewMapLoader; // 0x110
	private Sprite m_stagePreviewMap; // 0x118
	private String m_stageId; // 0x120
	private Tween m_expandTween; // 0x128
	private Boolean m_isAniming; // 0x130
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
	private static DelegateBridge __Hotfix0_OnDataUpdated; // 0x58
	private static DelegateBridge __Hotfix0__UpdateView; // 0x60
	private static DelegateBridge __Hotfix0__CleanAnimTween; // 0x68
	private static DelegateBridge __Hotfix0__LoadMapPreview; // 0x70
	private static DelegateBridge __Hotfix0__UnloadStagePreviewMap; // 0x78
	private static DelegateBridge __Hotfix0__UpdateRewardList; // 0x80
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x88
	private static DelegateBridge __Hotfix0__SwitchExpandStatus; // 0x90
	private static DelegateBridge __Hotfix0_OnBtnEnemyClick; // 0x98
	private static DelegateBridge __Hotfix0_OnBtnStartBattleClick; // 0xa0
	private static DelegateBridge __Hotfix0_OnBtnStartPractiseClick; // 0xa8
	private static DelegateBridge __Hotfix0_OnBtnExpandClick; // 0xb0
	private static DelegateBridge __Hotfix0_OnBtnAutoBattleClick; // 0xb8
	private static DelegateBridge __Hotfix0_OnBtnRewardClick; // 0xc0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc8

	public Act1LockAutoBattleView autoBattleView { get; }
	private Action onBtnEnemy { get; set; }
	private Action onBtnPractice { get; set; }
	private Action onBtnBattle { get; set; }
	private Action onAutoBattleToggle { get; set; }
	private Action onBtnReward { get; set; }

	// RVA: 0x33d1324 VA: 0x75959e9324
	public Act1LockAutoBattleView get_autoBattleView() { }
	// RVA: 0x33d138c VA: 0x75959e938c
	private Action get_onBtnEnemy() { }
	// RVA: 0x33d13f4 VA: 0x75959e93f4
	public Void set_onBtnEnemy(Action value) { }
	// RVA: 0x33d1478 VA: 0x75959e9478
	private Action get_onBtnPractice() { }
	// RVA: 0x33d14e0 VA: 0x75959e94e0
	public Void set_onBtnPractice(Action value) { }
	// RVA: 0x33d1564 VA: 0x75959e9564
	private Action get_onBtnBattle() { }
	// RVA: 0x33d15cc VA: 0x75959e95cc
	public Void set_onBtnBattle(Action value) { }
	// RVA: 0x33d1650 VA: 0x75959e9650
	private Action get_onAutoBattleToggle() { }
	// RVA: 0x33d16b8 VA: 0x75959e96b8
	public Void set_onAutoBattleToggle(Action value) { }
	// RVA: 0x33d173c VA: 0x75959e973c
	private Action get_onBtnReward() { }
	// RVA: 0x33d17a4 VA: 0x75959e97a4
	public Void set_onBtnReward(Action value) { }
	// RVA: 0x33d1828 VA: 0x75959e9828
	protected override Void OnDataUpdated(Act1LockDetailProperty prop) { }
	// RVA: 0x33d1bf0 VA: 0x75959e9bf0
	private Void _UpdateView(Act1LockNormalDetailModel detailModel) { }
	// RVA: 0x33d1ae8 VA: 0x75959e9ae8
	private Void _CleanAnimTween() { }
	// RVA: 0x33d21dc VA: 0x75959ea1dc
	private Void _LoadMapPreview(String stageId) { }
	// RVA: 0x33d2294 VA: 0x75959ea294
	private Void _UnloadStagePreviewMap() { }
	// RVA: 0x33d1fb4 VA: 0x75959e9fb4
	private Void _UpdateRewardList(StageViewModel selectedStageModel) { }
	// RVA: 0x33d19a0 VA: 0x75959e99a0
	private Void _InitIfNot() { }
	// RVA: 0x33d2498 VA: 0x75959ea498
	private Void _SwitchExpandStatus() { }
	// RVA: 0x33d26e8 VA: 0x75959ea6e8
	public Void OnBtnEnemyClick() { }
	// RVA: 0x33d2784 VA: 0x75959ea784
	public Void OnBtnStartBattleClick() { }
	// RVA: 0x33d2820 VA: 0x75959ea820
	public Void OnBtnStartPractiseClick() { }
	// RVA: 0x33d28bc VA: 0x75959ea8bc
	public Void OnBtnExpandClick() { }
	// RVA: 0x33d2924 VA: 0x75959ea924
	public Void OnBtnAutoBattleClick() { }
	// RVA: 0x33d29c0 VA: 0x75959ea9c0
	public Void OnBtnRewardClick() { }
	// RVA: 0x33d2a5c VA: 0x75959eaa5c
	public Void .ctor() { }
	// RVA: 0x33d2b0c VA: 0x75959eab0c
	private Void <>xLuaBaseProxy_OnDataUpdated(Act1LockDetailProperty P0) { }
}
```