# ActMultiV3QuickMatchModeItemView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `GameObject _normalPartGO`

- `GameObject _lockPartGO`

- `Text _textNameInLock`

- `Image _imgTopIconInLock`

- `Image _imgBottomIconInLock`

- `Text _textModeUnlockTime`

- `Text _textName`

- `Image _imgTopIcon`

- `UIAtlasImage _imgTopIconBg`

- `UIAtlasImage _imgHeaderBg`

- `Text _captionHeader`

- `UIAtlasImage _imgHeaderIcon`

- `Image _imgBottomIcon`

- `GameObject _stageUnlockHintGO`

- `Text _textStageUnlockHint`

- `UIAnimationLocation _animSwitch`

- `GameObject _trainingLockGO`

- `Text _trainingTextName`

- `Text _textTrainingUnlockHint`

- `Image _trainingLockTopIcon`

- `Image _trainingLockSideIcon`

- `GameObject _trainingPartGO`

- `GameObject _btnTrainingPartGo`

- `Boolean m_inited`

- `UIPageFinder m_pageFinder`

- `ActMultiV3MatchModeGroupModel m_modeGroupModel`

- `AnimationSwitchTween m_switchTween`

- `UIStateFinder m_stateFinder`


## Methods

- `Void Render(ActMultiV3QuickMatchModel, ActMultiV3MatchModeGroupModel)`

- `Void _InitIfNot()`

- `Void _RegisterTutorialGo()`

- `Void _RenderNormalPart(ActMultiV3QuickMatchModel, ActMultiV3MatchModeGroupModel, Int64)`

- `Void _RenderLockPart(ActMultiV3MatchModeGroupModel, String)`

- `Void _RenderDiffItemViews(ActMultiV3QuickMatchModel, ActMultiV3MatchModeGroupModel)`

- `Void _InitDiffItemViewIfNeed(ActMultiV3MatchModeGroupModel)`

- `Void _UpdateDiffItemTrackGO(ActMultiV3QuickMatchModel, ActMultiV3MatchModeGroupModel)`

- `ActMultiV3QuickMatchDiffItemView _FindModeDiffPrefab(ActMultiV3MapModeType)`

- `ColorConfig _FindMatchConfig(ActMultiV3MapModeType)`

- `Void _ApplyColorConfig(ActMultiV3MatchModeGroupModel)`

- `Void EventOnBtnTraining()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3QuickMatchModeItemView : MonoBehaviour, IHotfixable
{
	private GameObject _normalPartGO; // 0x18
	private GameObject _lockPartGO; // 0x20
	private Text _textNameInLock; // 0x28
	private Image _imgTopIconInLock; // 0x30
	private Image _imgBottomIconInLock; // 0x38
	private Text _textModeUnlockTime; // 0x40
	private Text _textName; // 0x48
	private Image _imgTopIcon; // 0x50
	private UIAtlasImage _imgTopIconBg; // 0x58
	private UIAtlasImage _imgHeaderBg; // 0x60
	private Text _captionHeader; // 0x68
	private UIAtlasImage _imgHeaderIcon; // 0x70
	private Image _imgBottomIcon; // 0x78
	private GameObject _stageUnlockHintGO; // 0x80
	private Text _textStageUnlockHint; // 0x88
	private DiffItemContainer[] _diffItemContainers; // 0x90
	private ColorConfig[] _colorConfigs; // 0x98
	private ActMultiV3QuickMatchDiffItemView[] _diffItemPrefabs; // 0xa0
	private UIAnimationLocation _animSwitch; // 0xa8
	private GameObject _trainingLockGO; // 0xb8
	private Text _trainingTextName; // 0xc0
	private Text _textTrainingUnlockHint; // 0xc8
	private Image _trainingLockTopIcon; // 0xd0
	private Image _trainingLockSideIcon; // 0xd8
	private GameObject _trainingPartGO; // 0xe0
	private GameObject _btnTrainingPartGo; // 0xe8
	private Boolean m_inited; // 0xf0
	private UIPageFinder m_pageFinder; // 0xf8
	private ActMultiV3MatchModeGroupModel m_modeGroupModel; // 0x108
	private Dictionary`2 m_diffItemViewDict; // 0x110
	private AnimationSwitchTween m_switchTween; // 0x118
	private UIStateFinder m_stateFinder; // 0x120
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__RegisterTutorialGo; // 0x10
	private static DelegateBridge __Hotfix0__RenderNormalPart; // 0x18
	private static DelegateBridge __Hotfix0__RenderLockPart; // 0x20
	private static DelegateBridge __Hotfix0__RenderDiffItemViews; // 0x28
	private static DelegateBridge __Hotfix0__InitDiffItemViewIfNeed; // 0x30
	private static DelegateBridge __Hotfix0__UpdateDiffItemTrackGO; // 0x38
	private static DelegateBridge __Hotfix0__FindModeDiffPrefab; // 0x40
	private static DelegateBridge __Hotfix0__FindMatchConfig; // 0x48
	private static DelegateBridge __Hotfix0__ApplyColorConfig; // 0x50
	private static DelegateBridge __Hotfix0_EventOnBtnTraining; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60


	// RVA: 0x31284ac VA: 0x75957404ac
	public Void Render(ActMultiV3QuickMatchModel matchModel, ActMultiV3MatchModeGroupModel modeGroupModel) { }
	// RVA: 0x31285e8 VA: 0x75957405e8
	private Void _InitIfNot() { }
	// RVA: 0x3128b74 VA: 0x7595740b74
	private Void _RegisterTutorialGo() { }
	// RVA: 0x312866c VA: 0x759574066c
	private Void _RenderNormalPart(ActMultiV3QuickMatchModel matchModel, ActMultiV3MatchModeGroupModel modeGroupModel, Int64 currTs) { }
	// RVA: 0x3128a2c VA: 0x7595740a2c
	private Void _RenderLockPart(ActMultiV3MatchModeGroupModel modeGroupModel, String modeUnlockHint) { }
	// RVA: 0x3128e48 VA: 0x7595740e48
	private Void _RenderDiffItemViews(ActMultiV3QuickMatchModel matchModel, ActMultiV3MatchModeGroupModel modeGroupModel) { }
	// RVA: 0x3129110 VA: 0x7595741110
	private Void _InitDiffItemViewIfNeed(ActMultiV3MatchModeGroupModel modeGroupModel) { }
	// RVA: 0x3128f9c VA: 0x7595740f9c
	private Void _UpdateDiffItemTrackGO(ActMultiV3QuickMatchModel matchModel, ActMultiV3MatchModeGroupModel modeGroupModel) { }
	// RVA: 0x312933c VA: 0x759574133c
	private ActMultiV3QuickMatchDiffItemView _FindModeDiffPrefab(ActMultiV3MapModeType modeType) { }
	// RVA: 0x3129484 VA: 0x7595741484
	private ColorConfig _FindMatchConfig(ActMultiV3MapModeType modeType) { }
	// RVA: 0x3128c78 VA: 0x7595740c78
	private Void _ApplyColorConfig(ActMultiV3MatchModeGroupModel modeGroupModel) { }
	// RVA: 0x3129578 VA: 0x7595741578
	public Void EventOnBtnTraining() { }
	// RVA: 0x312969c VA: 0x759574169c
	public Void .ctor() { }
}
```