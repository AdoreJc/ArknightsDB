# BuildingWorkshopWholeView

**Namespace:** `Torappu.Building.UI.Workshop`


## Fields

- `UIAtlasImage _charPortrait`

- `Text _characterName`

- `GameObject _distractedLabel`

- `Transform _mpBarContainer`

- `Text _moodTextLabel`

- `GameObject _characterEmptyHint`

- `BuildingBuffDescView _buffView`

- `Transform _buffHintLabel`

- `Text _goldCostLabel`

- `Text _moodCostLabel`

- `Text _workCountLabel`

- `GameObject _moodOverloadHint`

- `GameObject _moodOverloadBG`

- `Image _workCountBG`

- `Button _confirmButton`

- `Color _characterMoodOverloadColor`

- `Image _characterMoodBG`

- `Text _extraProbLabel`

- `Text _extraProbPlusLabel`

- `FormulaItemGroup _outcomeItemCard`

- `FormulaItemGroup _ingredient1ItemCard`

- `FormulaItemGroup _ingredient2ItemCard`

- `FormulaItemGroup _ingredient3ItemCard`

- `Transform _switchHandler`

- `Transform _switchOnPos`

- `Transform _switchOffPos`

- `GameObject _switchOnGroup`

- `GameObject _switchOffGroup`

- `GameObject _switchPanel`

- `Button _switchButton`

- `String _itemStorageLackFormat`

- `String _itemStorageNormFormat`

- `WorkshopMotionEffect _motionEffect`

- `GameObject _screenBlocker`

- `Single _outcomePanelDisplayDelay`

- `Transform _hintPanelTransform`

- `CanvasGroup _hintPanelCanvasGroup`

- `Transform _hintControlPoint0`

- `Transform _hintControlPoint1`

- `AnimationCurve _hintAnimationCurve`

- `Single _hintTransferTime`

- `BuildingRoomLevelView _roomLevel`

- `Text _roomTitle`

- `Single _switchProcessingSpeed`

- `Transform _recoverPanelTransform`

- `Text _recoverMoodLabel`

- `BuildingWorkshopBonusView _bonusView`

- `UIAnimationLocation _animEnter`

- `PrevItemPart _prevItemPart`

- `TargetAmountPart _targetAmountPart`

- `BuildingUIResMenu resMenu`

- `Action onClickFormulaButton`

- `BuildingCharMPStateBar m_mpBar`

- `Single m_switchPositionValue`

- `Single m_switchPositionValueTarget`

- `Sequence m_recoverTweenSequence`

- `Boolean m_isInited`

- `BuildingWorkshopWholeViewModel m_cachedViewModel`

- `Int32 m_cachedMood`

- `UIItemCard m_prevItemCard`


## Properties

- `WorkshopMotionEffect motionEffect`


## Methods

- `WorkshopMotionEffect get_motionEffect()`

- `Void _SaveSetupIngredientStorage(IFormulaItem, Text, Int32)`

- `Void _SaveSetupIngredient(IFormulaItem, FormulaItemGroup, Int32)`

- `Void _SaveSetupIngredientJumpBtn(IFormulaItem, FormulaItemGroup, Int32)`

- `Void _RenderAllIngredient(IWorkshopFormula, Int32)`

- `Void _SetupFormulaItemGroup(FormulaItemGroup, Boolean, Boolean)`

- `Void _SetWorkOverload(Boolean)`

- `Void _SetMoodValue(Int32, IWorkshopStationaryCharacter)`

- `Void _RefreshView(BuildingWorkshopWholeViewModel)`

- `Void _SetProtect(Boolean)`

- `Void _SetWorkCount(BuildingWorkshopModel, Int32)`

- `Void _SetPrevItemPanel(BuildingWorkshopModel)`

- `Void _SetTargetAmountPanel(BuildingWorkshopModel)`

- `Void _HintCallback(Single)`

- `IEnumerator _MotionAndMoodEffectWithCallback()`

- `IEnumerator OutcomeEffectCoroutine(WorkResult, Action)`

- `Void _ToastBySideProduct(BuildingWorkshopBySideNotify, String, Int64, Int32)`

- `Void _ShowRecoverMood(Int64)`

- `Void StopRecoverTweens()`

- `Void BlockScreen()`

- `Void _InitIfNot()`

- `Void Update()`

- `Void <OutcomeEffectCoroutine>b__84_1()`

- `Void <_ShowRecoverMood>b__86_2()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Workshop
public class BuildingWorkshopWholeView : DataBinder`1, IHotfixable
{
	private const Single BY_SIDE_NOTIFY_DELAY; // 0x0
	private const Single RECOVER_MOOD_DELAY; // 0x0
	private const Single RECOVER_MOOD_HOLD_TIME; // 0x0
	private const Single DURATION_SWITCH; // 0x0
	private UIAtlasImage _charPortrait; // 0x20
	private Text _characterName; // 0x28
	private GameObject _distractedLabel; // 0x30
	private Transform _mpBarContainer; // 0x38
	private Text _moodTextLabel; // 0x40
	private GameObject _characterEmptyHint; // 0x48
	private BuildingBuffDescView _buffView; // 0x50
	private Transform _buffHintLabel; // 0x58
	private Text _goldCostLabel; // 0x60
	private Text _moodCostLabel; // 0x68
	private Text _workCountLabel; // 0x70
	private GameObject _moodOverloadHint; // 0x78
	private GameObject _moodOverloadBG; // 0x80
	private Image _workCountBG; // 0x88
	private Button _confirmButton; // 0x90
	private Color _characterMoodOverloadColor; // 0x98
	private Image _characterMoodBG; // 0xa8
	private Text _extraProbLabel; // 0xb0
	private Text _extraProbPlusLabel; // 0xb8
	private FormulaItemGroup _outcomeItemCard; // 0xc0
	private FormulaItemGroup _ingredient1ItemCard; // 0xc8
	private FormulaItemGroup _ingredient2ItemCard; // 0xd0
	private FormulaItemGroup _ingredient3ItemCard; // 0xd8
	private Transform _switchHandler; // 0xe0
	private Transform _switchOnPos; // 0xe8
	private Transform _switchOffPos; // 0xf0
	private GameObject _switchOnGroup; // 0xf8
	private GameObject _switchOffGroup; // 0x100
	private GameObject _switchPanel; // 0x108
	private Button _switchButton; // 0x110
	private String _itemStorageLackFormat; // 0x118
	private String _itemStorageNormFormat; // 0x120
	private WorkshopMotionEffect _motionEffect; // 0x128
	private GameObject _screenBlocker; // 0x130
	private Single _outcomePanelDisplayDelay; // 0x138
	private Transform _hintPanelTransform; // 0x140
	private CanvasGroup _hintPanelCanvasGroup; // 0x148
	private Transform _hintControlPoint0; // 0x150
	private Transform _hintControlPoint1; // 0x158
	private AnimationCurve _hintAnimationCurve; // 0x160
	private Single _hintTransferTime; // 0x168
	private BuildingRoomLevelView _roomLevel; // 0x170
	private Text _roomTitle; // 0x178
	private Single _switchProcessingSpeed; // 0x180
	private Transform _recoverPanelTransform; // 0x188
	private Text _recoverMoodLabel; // 0x190
	private BuildingWorkshopBonusView _bonusView; // 0x198
	private UIAnimationLocation _animEnter; // 0x1a0
	private PrevItemPart _prevItemPart; // 0x1b0
	private TargetAmountPart _targetAmountPart; // 0x1b8
	public BuildingUIResMenu resMenu; // 0x1c0
	public Action onClickFormulaButton; // 0x1c8
	private BuildingCharMPStateBar m_mpBar; // 0x1d0
	private Single m_switchPositionValue; // 0x1d8
	private Single m_switchPositionValueTarget; // 0x1dc
	private Sequence m_recoverTweenSequence; // 0x1e0
	private Boolean m_isInited; // 0x1e8
	private BuildingWorkshopWholeViewModel m_cachedViewModel; // 0x1f0
	private Int32 m_cachedMood; // 0x1f8
	private UIItemCard m_prevItemCard; // 0x200
	private static DelegateBridge __Hotfix0_get_motionEffect; // 0x0
	private static DelegateBridge __Hotfix0__SaveSetupIngredientStorage; // 0x8
	private static DelegateBridge __Hotfix0__SaveSetupIngredient; // 0x10
	private static DelegateBridge __Hotfix0__SaveSetupIngredientJumpBtn; // 0x18
	private static DelegateBridge __Hotfix0__RenderAllIngredient; // 0x20
	private static DelegateBridge __Hotfix0__SetupFormulaItemGroup; // 0x28
	private static DelegateBridge __Hotfix0__SetWorkOverload; // 0x30
	private static DelegateBridge __Hotfix0__SetMoodValue; // 0x38
	private static DelegateBridge __Hotfix0__RefreshView; // 0x40
	private static DelegateBridge __Hotfix0__SetProtect; // 0x48
	private static DelegateBridge __Hotfix0__SetWorkCount; // 0x50
	private static DelegateBridge __Hotfix0__SetPrevItemPanel; // 0x58
	private static DelegateBridge __Hotfix0__SetTargetAmountPanel; // 0x60
	private static DelegateBridge __Hotfix0__HintCallback; // 0x68
	private static DelegateBridge __Hotfix0__MotionAndMoodEffectWithCallback; // 0x70
	private static DelegateBridge __Hotfix0_OutcomeEffectCoroutine; // 0x78
	private static DelegateBridge __Hotfix0__ToastBySideProduct; // 0x80
	private static DelegateBridge __Hotfix0__ShowRecoverMood; // 0x88
	private static DelegateBridge __Hotfix0_StopRecoverTweens; // 0x90
	private static DelegateBridge __Hotfix0_BlockScreen; // 0x98
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0xa0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0xa8
	private static DelegateBridge __Hotfix0_Update; // 0xb0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xb8

	public WorkshopMotionEffect motionEffect { get; }

	// RVA: 0x3d69f10 VA: 0x7596381f10
	public WorkshopMotionEffect get_motionEffect() { }
	// RVA: 0x3d6ebb0 VA: 0x7596386bb0
	private Void _SaveSetupIngredientStorage(IFormulaItem item, Text label, Int32 workCount) { }
	// RVA: 0x3d6ee48 VA: 0x7596386e48
	private Void _SaveSetupIngredient(IFormulaItem item, FormulaItemGroup group, Int32 workCount) { }
	// RVA: 0x3d6f250 VA: 0x7596387250
	private Void _SaveSetupIngredientJumpBtn(IFormulaItem item, FormulaItemGroup group, Int32 workCount) { }
	// RVA: 0x3d6f504 VA: 0x7596387504
	private Void _RenderAllIngredient(IWorkshopFormula currentFormula, Int32 workCount) { }
	// RVA: 0x3d6f7a4 VA: 0x75963877a4
	private Void _SetupFormulaItemGroup(FormulaItemGroup group, Boolean isIngredient, Boolean showItemNum) { }
	// RVA: 0x3d6fb44 VA: 0x7596387b44
	private Void _SetWorkOverload(Boolean on) { }
	// RVA: 0x3d6fc30 VA: 0x7596387c30
	private Void _SetMoodValue(Int32 curMood, IWorkshopStationaryCharacter stationaryChar) { }
	// RVA: 0x3d70000 VA: 0x7596388000
	private Void _RefreshView(BuildingWorkshopWholeViewModel viewModel) { }
	// RVA: 0x3d70930 VA: 0x7596388930
	private Void _SetProtect(Boolean isItemProtection) { }
	// RVA: 0x3d70f50 VA: 0x7596388f50
	private Void _SetWorkCount(BuildingWorkshopModel model, Int32 count) { }
	// RVA: 0x3d709e8 VA: 0x75963889e8
	private Void _SetPrevItemPanel(BuildingWorkshopModel model) { }
	// RVA: 0x3d70d8c VA: 0x7596388d8c
	private Void _SetTargetAmountPanel(BuildingWorkshopModel model) { }
	// RVA: 0x3d71258 VA: 0x7596389258
	private Void _HintCallback(Single val) { }
	// RVA: 0x3d7137c VA: 0x759638937c
	private IEnumerator _MotionAndMoodEffectWithCallback() { }
	// RVA: 0x3d6ab18 VA: 0x7596382b18
	public IEnumerator OutcomeEffectCoroutine(WorkResult workResult, Action refresh) { }
	// RVA: 0x3d71478 VA: 0x7596389478
	private Void _ToastBySideProduct(BuildingWorkshopBySideNotify prefab, String itemId, Int64 count, Int32 index) { }
	// RVA: 0x3d715d0 VA: 0x75963895d0
	private Void _ShowRecoverMood(Int64 recoverCost) { }
	// RVA: 0x3d6a29c VA: 0x759638229c
	public Void StopRecoverTweens() { }
	// RVA: 0x3d6aaa8 VA: 0x7596382aa8
	public Void BlockScreen() { }
	// RVA: 0x3d71b7c VA: 0x7596389b7c
	public override Void OnValueChanged(BuildingWorkshopProperty property) { }
	// RVA: 0x3d71c60 VA: 0x7596389c60
	private Void _InitIfNot() { }
	// RVA: 0x3d71ce8 VA: 0x7596389ce8
	private Void Update() { }
	// RVA: 0x3d71ef4 VA: 0x7596389ef4
	public Void .ctor() { }
	// RVA: 0x3d71f98 VA: 0x7596389f98
	private Void <OutcomeEffectCoroutine>b__84_1() { }
	// RVA: 0x3d71fc0 VA: 0x7596389fc0
	private Void <_ShowRecoverMood>b__86_2() { }
}
```