# ClimbTowerTowerEntryView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Text _textTowerName`

- `Text _textTowerSubName`

- `GameObject _objHardModeTag`

- `VerticalLayoutGroup _layoutTowerTips`

- `Text _textHardModeTips`

- `Text _textTowerDesc`

- `Text _textDangerEffect`

- `Image _towerIcon`

- `Image _towerBkg`

- `ClimbTowerBackgroundController _bkgController`

- `GameObject _objRecord`

- `Text _textRecordLayer`

- `Text _textMaxLayer`

- `GameObject _pnlTrackpoint`

- `UIAtlasObject _atlasEntry`

- `RectTransform _rectTransLayerViewHolder`

- `ClimbTowerTowerLayerStack _layerViewPrefab`

- `UIColorGraphic _btnColorGraphic1`

- `UIColorGraphic _btnColorGraphic2`

- `ClimbTowerTowerLayerSelectArrowWithMode _selectArrowPrefab`

- `ClimbTowerTowerLayerGodCardTipsSimple _godCardTipsPrefab`

- `Image _medalImg`

- `GameObject _medalEmpty`

- `UIAtlasImage _imgNotInBattle`

- `UIAtlasImage _imgInBattle`

- `TwoStateToggle _btnEnter`

- `GameObject _enterBtnSweepPanel`

- `Text _enterSweepCostCnt`

- `GameObject _objSwitchToNormMode`

- `GameObject _objTrackPointSwitchToNorm`

- `GameObject _objSwitchToHardMode`

- `GameObject _objSwitchToHardModeBan`

- `GameObject _objSwitchToHardNew`

- `AnimationWrapper _animWrapper`

- `GameObject _sweepAble`

- `GameObject _sweepDisable`

- `GameObject _sweepLock`

- `UIAnimationLocation _sweepSwitchAnimLocation`

- `ClimbTowerSweepConfirmView _sweepConfirmView`

- `Action <eventOnSwitchModeClick>k__BackingField`

- `Action <eventOnClickSweep>k__BackingField`

- `String m_cachedTowerId`

- `String m_cachedMedalId`

- `ClimbTowerViewModel m_cachedModel`

- `Adapter m_adapter`

- `Boolean m_inited`

- `Tween m_switchModeTween`

- `MODE_TYPE m_cachedMode`

- `ClimbTowerTowerLayerStack m_towerLayerView`

- `Boolean m_cachedIsHardMode`

- `AnimationSwitchTween m_sweepSwitchTween`

- `Int32 m_switchHardModeSeqNum`

- `UIPage <page>k__BackingField`


## Properties

- `Action eventOnSwitchModeClick`

- `Action eventOnClickSweep`

- `UIPage page`


## Methods

- `Action get_eventOnSwitchModeClick()`

- `Void set_eventOnSwitchModeClick(Action)`

- `Action get_eventOnClickSweep()`

- `Void set_eventOnClickSweep(Action)`

- `UIPage get_page()`

- `Void set_page(UIPage)`

- `Void OnExit()`

- `Void _InitIfNot(ClimbTowerViewModel)`

- `Boolean _IsModeEqual(Boolean)`

- `Void _RenderLeftInfoPart(ClimbTowerViewModel)`

- `Void _RenderFirstRecordPart(ClimbTowerViewModel)`

- `Void _RenderBgPart(ClimbTowerViewModel)`

- `Void _RenderLayerPart(ClimbTowerViewModel)`

- `Void _RenderBtnEnterPart(ClimbTowerViewModel)`

- `Void _RenderSwitchBtnPart(ClimbTowerViewModel)`

- `Void _RenderSweep(ClimbTowerViewModel)`

- `Void _RenderMedal(ClimbTowerViewModel)`

- `String _TryGetMedalId(ClimbTowerViewModel)`

- `Void _TryPlaySwitchModeTween(Boolean)`

- `Void OnSwitchToHardBtnClick()`

- `Void OnSwitchToNormBtnClick()`

- `Void OnSelectSweep()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerTowerEntryView : DataBinder`1
{
	private const String MAX_LAYER_FORMAT; // 0x0
	private const String SWEEP_COST_FORMAT; // 0x0
	private static readonly Color COLOR_ALL_COMPLETED; // 0x0
	private static readonly Color COLOR_NORMAL; // 0x10
	private Text _textTowerName; // 0x20
	private Text _textTowerSubName; // 0x28
	private GameObject _objHardModeTag; // 0x30
	private VerticalLayoutGroup _layoutTowerTips; // 0x38
	private Text _textHardModeTips; // 0x40
	private Text _textTowerDesc; // 0x48
	private Text _textDangerEffect; // 0x50
	private Image _towerIcon; // 0x58
	private Image _towerBkg; // 0x60
	private ClimbTowerBackgroundController _bkgController; // 0x68
	private GameObject _objRecord; // 0x70
	private Text _textRecordLayer; // 0x78
	private Text _textMaxLayer; // 0x80
	private GameObject _pnlTrackpoint; // 0x88
	private UIAtlasObject _atlasEntry; // 0x90
	private RectTransform _rectTransLayerViewHolder; // 0x98
	private ClimbTowerTowerLayerStack _layerViewPrefab; // 0xa0
	private UIColorGraphic _btnColorGraphic1; // 0xa8
	private UIColorGraphic _btnColorGraphic2; // 0xb0
	private ClimbTowerTowerLayerSelectArrowWithMode _selectArrowPrefab; // 0xb8
	private ClimbTowerTowerLayerGodCardTipsSimple _godCardTipsPrefab; // 0xc0
	private Image _medalImg; // 0xc8
	private GameObject _medalEmpty; // 0xd0
	private UIAtlasImage _imgNotInBattle; // 0xd8
	private UIAtlasImage _imgInBattle; // 0xe0
	private TwoStateToggle _btnEnter; // 0xe8
	private GameObject _enterBtnSweepPanel; // 0xf0
	private Text _enterSweepCostCnt; // 0xf8
	private GameObject _objSwitchToNormMode; // 0x100
	private GameObject _objTrackPointSwitchToNorm; // 0x108
	private GameObject _objSwitchToHardMode; // 0x110
	private GameObject _objSwitchToHardModeBan; // 0x118
	private GameObject _objSwitchToHardNew; // 0x120
	private AnimationWrapper _animWrapper; // 0x128
	private GameObject _sweepAble; // 0x130
	private GameObject _sweepDisable; // 0x138
	private GameObject _sweepLock; // 0x140
	private UIAnimationLocation _sweepSwitchAnimLocation; // 0x148
	private ClimbTowerSweepConfirmView _sweepConfirmView; // 0x158
	private Action <eventOnSwitchModeClick>k__BackingField; // 0x160
	private Action <eventOnClickSweep>k__BackingField; // 0x168
	private String m_cachedTowerId; // 0x170
	private String m_cachedMedalId; // 0x178
	private ClimbTowerViewModel m_cachedModel; // 0x180
	private Adapter m_adapter; // 0x188
	private Boolean m_inited; // 0x190
	private const String SWITCH_MODE_ANIM; // 0x0
	private Tween m_switchModeTween; // 0x198
	private MODE_TYPE m_cachedMode; // 0x1a0
	private ClimbTowerTowerLayerStack m_towerLayerView; // 0x1a8
	private Boolean m_cachedIsHardMode; // 0x1b0
	private AnimationSwitchTween m_sweepSwitchTween; // 0x1b8
	private Int32 m_switchHardModeSeqNum; // 0x1c0
	private readonly Int32 LAYOUT_TOWER_TIPS_TOP_HARD; // 0x1c4
	private readonly Single ALPHA_TOWER_ICON; // 0x1c8
	private const String BTN_ENTER_PREFIX; // 0x0
	private UIPage <page>k__BackingField; // 0x1d0
	private static DelegateBridge __Hotfix0_get_eventOnSwitchModeClick; // 0x20
	private static DelegateBridge __Hotfix0_set_eventOnSwitchModeClick; // 0x28
	private static DelegateBridge __Hotfix0_get_eventOnClickSweep; // 0x30
	private static DelegateBridge __Hotfix0_set_eventOnClickSweep; // 0x38
	private static DelegateBridge __Hotfix0_get_page; // 0x40
	private static DelegateBridge __Hotfix0_set_page; // 0x48
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x50
	private static DelegateBridge __Hotfix0_OnExit; // 0x58
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x60
	private static DelegateBridge __Hotfix0__IsModeEqual; // 0x68
	private static DelegateBridge __Hotfix0__RenderLeftInfoPart; // 0x70
	private static DelegateBridge __Hotfix0__RenderFirstRecordPart; // 0x78
	private static DelegateBridge __Hotfix0__RenderBgPart; // 0x80
	private static DelegateBridge __Hotfix0__RenderLayerPart; // 0x88
	private static DelegateBridge __Hotfix0__RenderBtnEnterPart; // 0x90
	private static DelegateBridge __Hotfix0__RenderSwitchBtnPart; // 0x98
	private static DelegateBridge __Hotfix0__RenderSweep; // 0xa0
	private static DelegateBridge __Hotfix0__RenderMedal; // 0xa8
	private static DelegateBridge __Hotfix0__TryGetMedalId; // 0xb0
	private static DelegateBridge __Hotfix0__TryPlaySwitchModeTween; // 0xb8
	private static DelegateBridge __Hotfix0_OnSwitchToHardBtnClick; // 0xc0
	private static DelegateBridge __Hotfix0_OnSwitchToNormBtnClick; // 0xc8
	private static DelegateBridge __Hotfix0_OnSelectSweep; // 0xd0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd8

	public Action eventOnSwitchModeClick { get; set; }
	public Action eventOnClickSweep { get; set; }
	private UIPage page { get; set; }

	// RVA: 0x2c785fc VA: 0x75952905fc
	public Action get_eventOnSwitchModeClick() { }
	// RVA: 0x2c78674 VA: 0x7595290674
	public Void set_eventOnSwitchModeClick(Action value) { }
	// RVA: 0x2c78708 VA: 0x7595290708
	public Action get_eventOnClickSweep() { }
	// RVA: 0x2c78780 VA: 0x7595290780
	public Void set_eventOnClickSweep(Action value) { }
	// RVA: 0x2c78814 VA: 0x7595290814
	private UIPage get_page() { }
	// RVA: 0x2c7888c VA: 0x759529088c
	public Void set_page(UIPage value) { }
	// RVA: 0x2c78920 VA: 0x7595290920
	public override Void OnValueChanged(ClimbTowerProperty property) { }
	// RVA: 0x2c79c7c VA: 0x7595291c7c
	public Void OnExit() { }
	// RVA: 0x2c78aac VA: 0x7595290aac
	private Void _InitIfNot(ClimbTowerViewModel model) { }
	// RVA: 0x2c79bd0 VA: 0x7595291bd0
	private Boolean _IsModeEqual(Boolean isHardMode) { }
	// RVA: 0x2c78eb8 VA: 0x7595290eb8
	private Void _RenderLeftInfoPart(ClimbTowerViewModel model) { }
	// RVA: 0x2c79390 VA: 0x7595291390
	private Void _RenderFirstRecordPart(ClimbTowerViewModel model) { }
	// RVA: 0x2c78dd8 VA: 0x7595290dd8
	private Void _RenderBgPart(ClimbTowerViewModel model) { }
	// RVA: 0x2c791d8 VA: 0x75952911d8
	private Void _RenderLayerPart(ClimbTowerViewModel model) { }
	// RVA: 0x2c79708 VA: 0x7595291708
	private Void _RenderBtnEnterPart(ClimbTowerViewModel model) { }
	// RVA: 0x2c79934 VA: 0x7595291934
	private Void _RenderSwitchBtnPart(ClimbTowerViewModel model) { }
	// RVA: 0x2c79a60 VA: 0x7595291a60
	private Void _RenderSweep(ClimbTowerViewModel model) { }
	// RVA: 0x2c79594 VA: 0x7595291594
	private Void _RenderMedal(ClimbTowerViewModel model) { }
	// RVA: 0x2c7a214 VA: 0x7595292214
	private String _TryGetMedalId(ClimbTowerViewModel model) { }
	// RVA: 0x2c78ca4 VA: 0x7595290ca4
	private Void _TryPlaySwitchModeTween(Boolean isHardMode) { }
	// RVA: 0x2c7a32c VA: 0x759529232c
	public Void OnSwitchToHardBtnClick() { }
	// RVA: 0x2c7a500 VA: 0x7595292500
	public Void OnSwitchToNormBtnClick() { }
	// RVA: 0x2c7a5bc VA: 0x75952925bc
	public Void OnSelectSweep() { }
	// RVA: 0x2c7a668 VA: 0x7595292668
	public Void .ctor() { }
	// RVA: 0x2c7a718 VA: 0x7595292718
	private static Void .cctor() { }
}
```