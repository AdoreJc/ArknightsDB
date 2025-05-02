# BuildingTrainingConfirmState

**Namespace:** `Torappu.Building.UI.Train`


## Fields

- `BuildingTrainingStateBean _stateBean`

- `CharacterInfoSkillLevelUpSpecializedView _nowLevel`

- `CharacterInfoSkillLevelUpSpecializedView _upLevel`

- `Text _timeText`

- `Text _hourText`

- `Image _specialLvl`

- `Image _specialLvlGlow`

- `SimpleLayoutContent _layoutGroup`

- `Tween m_tagTipTweener`


## Methods

- `Void _UpdateView()`

- `Void _OnBackToCurState()`

- `Void EventOnExitSelectSkill()`

- `Void OnUpgradeConfirmClick()`

- `Void <OnUpgradeConfirmClick>b__17_0(UpdateSpecializationResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Train
public class BuildingTrainingConfirmState : State
{
	private BuildingTrainingStateBean _stateBean; // 0x50
	private CharacterInfoSkillLevelUpSpecializedView _nowLevel; // 0x58
	private CharacterInfoSkillLevelUpSpecializedView _upLevel; // 0x60
	private Text _timeText; // 0x68
	private Text _hourText; // 0x70
	private Image _specialLvl; // 0x78
	private Image _specialLvlGlow; // 0x80
	private SimpleLayoutContent _layoutGroup; // 0x88
	private Tween m_tagTipTweener; // 0x90
	private const Single TWEEN_DURATION; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnResume; // 0x10
	private static DelegateBridge __Hotfix0__UpdateView; // 0x18
	private static DelegateBridge __Hotfix0__OnBackToCurState; // 0x20
	private static DelegateBridge __Hotfix0_EventOnExitSelectSkill; // 0x28
	private static DelegateBridge __Hotfix0_OnUpgradeConfirmClick; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x3d79804 VA: 0x7596391804
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3d7986c VA: 0x759639186c
	protected override Void OnEnter() { }
	// RVA: 0x3d79cac VA: 0x7596391cac
	protected override Void OnResume() { }
	// RVA: 0x3d798d4 VA: 0x75963918d4
	private Void _UpdateView() { }
	// RVA: 0x3d79d3c VA: 0x7596391d3c
	private Void _OnBackToCurState() { }
	// RVA: 0x3d79ea4 VA: 0x7596391ea4
	public Void EventOnExitSelectSkill() { }
	// RVA: 0x3d79f30 VA: 0x7596391f30
	public Void OnUpgradeConfirmClick() { }
	// RVA: 0x3d7a208 VA: 0x7596392208
	public Void .ctor() { }
	// RVA: 0x3d7a278 VA: 0x7596392278
	private Void <OnUpgradeConfirmClick>b__17_0(UpdateSpecializationResponse response) { }
	// RVA: 0x3d7a2ec VA: 0x75963922ec
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x3d7a2f4 VA: 0x75963922f4
	private Void <>xLuaBaseProxy_OnResume() { }
}
```