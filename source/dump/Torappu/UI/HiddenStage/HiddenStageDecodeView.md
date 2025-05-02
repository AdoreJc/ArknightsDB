# HiddenStageDecodeView

**Namespace:** `Torappu.UI.HiddenStage`


## Fields

- `GameObject _panelDecode`

- `GameObject _btnBack`

- `GameObject _btnExit`

- `GameObject _btnDecode`

- `Text _stageName`

- `SimpleLayoutContent _missionContainer`

- `GameObject _panelStagePreview`

- `Image _stageAvatar`

- `Text _stageInfoCode`

- `Text _stageInfoName`

- `Text _stageInfoDesc`

- `Image _stageInfoMap`

- `SimpleLayoutContent _rewardList`

- `Button _avgBtn`

- `Button _avgBtn2`

- `UIAnimationLocation _decodePanelAnim`

- `UIAnimationLocation _stagePreviewAnim`

- `AnimationWrapper _animationWrapper`

- `Action <onAvgClick>k__BackingField`

- `Action <onStageDetailClick>k__BackingField`

- `Action <onStegeDecodeClick>k__BackingField`

- `Action <onStageRewardClick>k__BackingField`

- `Action <onEnemyClick>k__BackingField`

- `Action <onBattleStart>k__BackingField`

- `Action <onUnlockHidden>k__BackingField`

- `Action <onExit>k__BackingField`

- `Image mapPreview`

- `GameObject mapTipsPanel`

- `Image bkImg`

- `HiddenStageMissionAdapter m_adapter`

- `HiddenStageRewardPreviewAdapter m_rewardAdapter`

- `Boolean m_inited`

- `Sprite m_stagePreviewMap`

- `DirectAssetLoader m_stagePreviewMapLoader`

- `HiddenStageViewModel m_cachedViewModel`

- `AnimationSwitchTween m_decodeSwitch`

- `AnimationSwitchTween m_previewSwitch`

- `StageViewModel m_cachedStageViewModel`


## Properties

- `Action onAvgClick`

- `Action onStageDetailClick`

- `Action onStegeDecodeClick`

- `Action onStageRewardClick`

- `Action onEnemyClick`

- `Action onBattleStart`

- `Action onUnlockHidden`

- `Action onExit`


## Methods

- `Void set_onJumpToStage(Action`1)`

- `Action get_onAvgClick()`

- `Void set_onAvgClick(Action)`

- `Action get_onStageDetailClick()`

- `Void set_onStageDetailClick(Action)`

- `Action get_onStegeDecodeClick()`

- `Void set_onStegeDecodeClick(Action)`

- `Action get_onStageRewardClick()`

- `Void set_onStageRewardClick(Action)`

- `Action get_onEnemyClick()`

- `Void set_onEnemyClick(Action)`

- `Action get_onBattleStart()`

- `Void set_onBattleStart(Action)`

- `Action get_onUnlockHidden()`

- `Void set_onUnlockHidden(Action)`

- `Action get_onExit()`

- `Void set_onExit(Action)`

- `Void _OnDecodeAnimEnd()`

- `Void _RenderView(HiddenStageViewModel)`

- `Void _InitIfNot()`

- `Void _RenderBaseInfo(HiddenStageViewModel)`

- `Void _RenderStagePreview()`

- `Void _LoadAvatar(String)`

- `Void _RenderDecodePanel()`

- `Void _SwitchPanel(Boolean)`

- `Void _LoadMapPreview(String)`

- `Void _RenderReward(StageViewModel)`

- `Void _UnloadStagePreviewMap()`

- `Void _ShotBlurredSprite()`

- `Void _ClearBlurSprite()`

- `AnimationSwitchTween _EnsureDecodeAnim()`

- `AnimationSwitchTween _EnsurePreviewAnim()`

- `Void EventOnDecodePanel()`

- `Void EventOnStageDetail()`

- `Void EventOnEnemyHandBook()`

- `Void EventOnMapPreview()`

- `Void EventOnReward()`

- `Void EventOnBattleStart()`

- `Void EventOnAvg()`

- `Void EventOnJumpStage(String)`

- `Void EventOnExit()`

- `Void EventOnUnlockHidden()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HiddenStage
public class HiddenStageDecodeView : DataBinder`1
{
	private GameObject _panelDecode; // 0x20
	private GameObject _btnBack; // 0x28
	private GameObject _btnExit; // 0x30
	private GameObject _btnDecode; // 0x38
	private Text _stageName; // 0x40
	private SimpleLayoutContent _missionContainer; // 0x48
	private GameObject _panelStagePreview; // 0x50
	private Image _stageAvatar; // 0x58
	private Text _stageInfoCode; // 0x60
	private Text _stageInfoName; // 0x68
	private Text _stageInfoDesc; // 0x70
	private Image _stageInfoMap; // 0x78
	private SimpleLayoutContent _rewardList; // 0x80
	private Button _avgBtn; // 0x88
	private Button _avgBtn2; // 0x90
	private UIAnimationLocation _decodePanelAnim; // 0x98
	private UIAnimationLocation _stagePreviewAnim; // 0xa8
	private AnimationWrapper _animationWrapper; // 0xb8
	private StageDecoAvatar[] _avatars; // 0xc0
	private Action`1 <onJumpToStage>k__BackingField; // 0xc8
	private Action <onAvgClick>k__BackingField; // 0xd0
	private Action <onStageDetailClick>k__BackingField; // 0xd8
	private Action <onStegeDecodeClick>k__BackingField; // 0xe0
	private Action <onStageRewardClick>k__BackingField; // 0xe8
	private Action <onEnemyClick>k__BackingField; // 0xf0
	private Action <onBattleStart>k__BackingField; // 0xf8
	private Action <onUnlockHidden>k__BackingField; // 0x100
	private Action <onExit>k__BackingField; // 0x108
	public Image mapPreview; // 0x110
	public GameObject mapTipsPanel; // 0x118
	public Image bkImg; // 0x120
	private const String DECODE_ANIMATION_ANME; // 0x0
	private HiddenStageMissionAdapter m_adapter; // 0x128
	private HiddenStageRewardPreviewAdapter m_rewardAdapter; // 0x130
	private Boolean m_inited; // 0x138
	private Sprite m_stagePreviewMap; // 0x140
	private DirectAssetLoader m_stagePreviewMapLoader; // 0x148
	private HiddenStageViewModel m_cachedViewModel; // 0x150
	private AnimationSwitchTween m_decodeSwitch; // 0x158
	private AnimationSwitchTween m_previewSwitch; // 0x160
	private StageViewModel m_cachedStageViewModel; // 0x168
	private static DelegateBridge __Hotfix0_get_onJumpToStage; // 0x0
	private static DelegateBridge __Hotfix0_set_onJumpToStage; // 0x8
	private static DelegateBridge __Hotfix0_get_onAvgClick; // 0x10
	private static DelegateBridge __Hotfix0_set_onAvgClick; // 0x18
	private static DelegateBridge __Hotfix0_get_onStageDetailClick; // 0x20
	private static DelegateBridge __Hotfix0_set_onStageDetailClick; // 0x28
	private static DelegateBridge __Hotfix0_get_onStegeDecodeClick; // 0x30
	private static DelegateBridge __Hotfix0_set_onStegeDecodeClick; // 0x38
	private static DelegateBridge __Hotfix0_get_onStageRewardClick; // 0x40
	private static DelegateBridge __Hotfix0_set_onStageRewardClick; // 0x48
	private static DelegateBridge __Hotfix0_get_onEnemyClick; // 0x50
	private static DelegateBridge __Hotfix0_set_onEnemyClick; // 0x58
	private static DelegateBridge __Hotfix0_get_onBattleStart; // 0x60
	private static DelegateBridge __Hotfix0_set_onBattleStart; // 0x68
	private static DelegateBridge __Hotfix0_get_onUnlockHidden; // 0x70
	private static DelegateBridge __Hotfix0_set_onUnlockHidden; // 0x78
	private static DelegateBridge __Hotfix0_get_onExit; // 0x80
	private static DelegateBridge __Hotfix0_set_onExit; // 0x88
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x90
	private static DelegateBridge __Hotfix0__OnDecodeAnimEnd; // 0x98
	private static DelegateBridge __Hotfix0__RenderView; // 0xa0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0xa8
	private static DelegateBridge __Hotfix0__RenderBaseInfo; // 0xb0
	private static DelegateBridge __Hotfix0__RenderStagePreview; // 0xb8
	private static DelegateBridge __Hotfix0__LoadAvatar; // 0xc0
	private static DelegateBridge __Hotfix0__RenderDecodePanel; // 0xc8
	private static DelegateBridge __Hotfix0__SwitchPanel; // 0xd0
	private static DelegateBridge __Hotfix0__LoadMapPreview; // 0xd8
	private static DelegateBridge __Hotfix0__RenderReward; // 0xe0
	private static DelegateBridge __Hotfix0__UnloadStagePreviewMap; // 0xe8
	private static DelegateBridge __Hotfix0__ShotBlurredSprite; // 0xf0
	private static DelegateBridge __Hotfix0__ClearBlurSprite; // 0xf8
	private static DelegateBridge __Hotfix0__EnsureDecodeAnim; // 0x100
	private static DelegateBridge __Hotfix0__EnsurePreviewAnim; // 0x108
	private static DelegateBridge __Hotfix0_EventOnDecodePanel; // 0x110
	private static DelegateBridge __Hotfix0_EventOnStageDetail; // 0x118
	private static DelegateBridge __Hotfix0_EventOnEnemyHandBook; // 0x120
	private static DelegateBridge __Hotfix0_EventOnMapPreview; // 0x128
	private static DelegateBridge __Hotfix0_EventOnReward; // 0x130
	private static DelegateBridge __Hotfix0_EventOnBattleStart; // 0x138
	private static DelegateBridge __Hotfix0_EventOnAvg; // 0x140
	private static DelegateBridge __Hotfix0_EventOnJumpStage; // 0x148
	private static DelegateBridge __Hotfix0_EventOnExit; // 0x150
	private static DelegateBridge __Hotfix0_EventOnUnlockHidden; // 0x158
	private static DelegateBridge _c__Hotfix0_ctor; // 0x160

	private Action`1 onJumpToStage { get; set; }
	private Action onAvgClick { get; set; }
	private Action onStageDetailClick { get; set; }
	private Action onStegeDecodeClick { get; set; }
	private Action onStageRewardClick { get; set; }
	private Action onEnemyClick { get; set; }
	private Action onBattleStart { get; set; }
	private Action onUnlockHidden { get; set; }
	private Action onExit { get; set; }

	// RVA: 0x2859790 VA: 0x7594e71790
	private Action`1 get_onJumpToStage() { }
	// RVA: 0x28597f8 VA: 0x7594e717f8
	public Void set_onJumpToStage(Action`1 value) { }
	// RVA: 0x285987c VA: 0x7594e7187c
	private Action get_onAvgClick() { }
	// RVA: 0x28598e4 VA: 0x7594e718e4
	public Void set_onAvgClick(Action value) { }
	// RVA: 0x2859968 VA: 0x7594e71968
	private Action get_onStageDetailClick() { }
	// RVA: 0x28599d0 VA: 0x7594e719d0
	public Void set_onStageDetailClick(Action value) { }
	// RVA: 0x2859a54 VA: 0x7594e71a54
	private Action get_onStegeDecodeClick() { }
	// RVA: 0x2859abc VA: 0x7594e71abc
	public Void set_onStegeDecodeClick(Action value) { }
	// RVA: 0x2859b40 VA: 0x7594e71b40
	private Action get_onStageRewardClick() { }
	// RVA: 0x2859ba8 VA: 0x7594e71ba8
	public Void set_onStageRewardClick(Action value) { }
	// RVA: 0x2859c2c VA: 0x7594e71c2c
	private Action get_onEnemyClick() { }
	// RVA: 0x2859c94 VA: 0x7594e71c94
	public Void set_onEnemyClick(Action value) { }
	// RVA: 0x2859d18 VA: 0x7594e71d18
	private Action get_onBattleStart() { }
	// RVA: 0x2859d80 VA: 0x7594e71d80
	public Void set_onBattleStart(Action value) { }
	// RVA: 0x2859e04 VA: 0x7594e71e04
	private Action get_onUnlockHidden() { }
	// RVA: 0x2859e6c VA: 0x7594e71e6c
	public Void set_onUnlockHidden(Action value) { }
	// RVA: 0x2859ef0 VA: 0x7594e71ef0
	private Action get_onExit() { }
	// RVA: 0x2859f58 VA: 0x7594e71f58
	public Void set_onExit(Action value) { }
	// RVA: 0x2859fdc VA: 0x7594e71fdc
	public override Void OnValueChanged(HiddenStageDecodeProperty property) { }
	// RVA: 0x285a27c VA: 0x7594e7227c
	private Void _OnDecodeAnimEnd() { }
	// RVA: 0x285a1ac VA: 0x7594e721ac
	private Void _RenderView(HiddenStageViewModel viewModel) { }
	// RVA: 0x285a314 VA: 0x7594e72314
	private Void _InitIfNot() { }
	// RVA: 0x285a914 VA: 0x7594e72914
	private Void _RenderBaseInfo(HiddenStageViewModel viewModel) { }
	// RVA: 0x285a454 VA: 0x7594e72454
	private Void _RenderStagePreview() { }
	// RVA: 0x285ab90 VA: 0x7594e72b90
	private Void _LoadAvatar(String stageId) { }
	// RVA: 0x285a680 VA: 0x7594e72680
	private Void _RenderDecodePanel() { }
	// RVA: 0x285a9f4 VA: 0x7594e729f4
	private Void _SwitchPanel(Boolean isDecode) { }
	// RVA: 0x285aac4 VA: 0x7594e72ac4
	private Void _LoadMapPreview(String stageId) { }
	// RVA: 0x285aca0 VA: 0x7594e72ca0
	private Void _RenderReward(StageViewModel viewModel) { }
	// RVA: 0x285b080 VA: 0x7594e73080
	private Void _UnloadStagePreviewMap() { }
	// RVA: 0x285b228 VA: 0x7594e73228
	private Void _ShotBlurredSprite() { }
	// RVA: 0x285b29c VA: 0x7594e7329c
	private Void _ClearBlurSprite() { }
	// RVA: 0x285ae88 VA: 0x7594e72e88
	private AnimationSwitchTween _EnsureDecodeAnim() { }
	// RVA: 0x285af84 VA: 0x7594e72f84
	private AnimationSwitchTween _EnsurePreviewAnim() { }
	// RVA: 0x285b3a0 VA: 0x7594e733a0
	public Void EventOnDecodePanel() { }
	// RVA: 0x285b43c VA: 0x7594e7343c
	public Void EventOnStageDetail() { }
	// RVA: 0x285b4d8 VA: 0x7594e734d8
	public Void EventOnEnemyHandBook() { }
	// RVA: 0x285b574 VA: 0x7594e73574
	public Void EventOnMapPreview() { }
	// RVA: 0x285b60c VA: 0x7594e7360c
	public Void EventOnReward() { }
	// RVA: 0x285b6a8 VA: 0x7594e736a8
	public Void EventOnBattleStart() { }
	// RVA: 0x285b744 VA: 0x7594e73744
	public Void EventOnAvg() { }
	// RVA: 0x285b7e0 VA: 0x7594e737e0
	public Void EventOnJumpStage(String stageId) { }
	// RVA: 0x285b898 VA: 0x7594e73898
	public Void EventOnExit() { }
	// RVA: 0x285b934 VA: 0x7594e73934
	public Void EventOnUnlockHidden() { }
	// RVA: 0x285b9d0 VA: 0x7594e739d0
	public Void .ctor() { }
}
```