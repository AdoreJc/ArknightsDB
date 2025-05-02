# CharacterInfoHolderState

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `CharacterInfoHolderBean _stateBean`

- `CharacterInfoIllustHolder _holder`

- `CharacterInfoRightHolderView _rightHolderView`

- `AnimationWrapper _animWrapper`

- `RefCountReference m_buildingContextRef`

- `Single m_animIndex`

- `Tween m_cacheTween`


## Methods

- `Void OnIllustrationChanged(Int32)`

- `Void OnSwitchIllustrationClicked()`

- `Void OnHandBookInfo()`

- `Void OnBtnTokenClick()`

- `Void OnEvolveClick()`

- `Void OnTransClick()`

- `Void OnPotentialClick()`

- `Void OnUniEquipClick()`

- `Void OnUplevelClicked()`

- `Void OnIllustClicked()`

- `Void OnSkillHideClick()`

- `Void OnSelectSkillClick()`

- `Void OnSelectSkillAllClick()`

- `Void EventOnTrainingClick()`

- `Void OnSpCharMissionClick()`

- `Void EventOnBackButtonClick()`

- `Void OnProfessionDetailClick()`

- `Void OnStarMarkCharacterClick()`

- `Void OnPotentialSwitchClick()`

- `Void _OnJumpToEvolveState(IStateBean)`

- `Void _OnJumpFromEvolveState(IStateBean)`

- `Void _OnJumpToHandbookState(IStateBean)`

- `Void _OnJumpToToSelectSkillState(IStateBean)`

- `Void _OnJumpFromSelectSkillState(IStateBean)`

- `Void _OnJumpToSpCharMissionState(IStateBean)`

- `Void _OnJumpFromSpCharMissionState(IStateBean)`

- `Void _OnExitCharacterInfoHome()`

- `Void _TriggerAvg()`

- `Void _UniqEquipGuideEndCallback(Story)`

- `Void _TriggerStarMarkToast(Boolean)`

- `Void OnResetSkillId()`

- `Void OnChangeSkill()`

- `Void OnSelectSkillId(String)`

- `Void OnResetEquipId()`

- `Void OnSelectEquipId(String)`

- `Void OnChangeUniEquip()`

- `Void OnDetailHide()`

- `Void OnDetailShow()`

- `Void OnIllustDataApply(Int32)`

- `Void _OnStateChange(Single, Single, Action)`

- `Void OnDestroy()`

- `Void <OnChangeSkill>b__43_0(SetDefaultSkillResponse)`

- `Void <OnDetailShow>b__54_0()`

- `Void <>xLuaBaseProxy_OnResume()`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnExit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoHolderState : State
{
	private CharacterInfoHolderBean _stateBean; // 0x50
	private CharacterInfoIllustHolder _holder; // 0x58
	private CharacterInfoRightHolderView _rightHolderView; // 0x60
	private AnimationWrapper _animWrapper; // 0x68
	private const String ANIM_PARAM; // 0x0
	private const Single HIDE_DURATION; // 0x0
	private const Single SHOW_PRE_HIDE_DURATION; // 0x0
	private const Single SHOW_DURATION; // 0x0
	private RefCountReference m_buildingContextRef; // 0x70
	private Single m_animIndex; // 0x78
	private Tween m_cacheTween; // 0x80
	private const Int32 HIDE_STATE; // 0x0
	private const Int32 SHOW_STATE; // 0x0
	private static DelegateBridge __Hotfix0_RegisterFromDataListener; // 0x0
	private static DelegateBridge __Hotfix0_RegisterToDataListener; // 0x8
	private static DelegateBridge __Hotfix0_OnIllustrationChanged; // 0x10
	private static DelegateBridge __Hotfix0_OnSwitchIllustrationClicked; // 0x18
	private static DelegateBridge __Hotfix0_OnResume; // 0x20
	private static DelegateBridge __Hotfix0_OnHandBookInfo; // 0x28
	private static DelegateBridge __Hotfix0_OnBtnTokenClick; // 0x30
	private static DelegateBridge __Hotfix0_OnEvolveClick; // 0x38
	private static DelegateBridge __Hotfix0_OnTransClick; // 0x40
	private static DelegateBridge __Hotfix0_OnPotentialClick; // 0x48
	private static DelegateBridge __Hotfix0_OnUniEquipClick; // 0x50
	private static DelegateBridge __Hotfix0_OnUplevelClicked; // 0x58
	private static DelegateBridge __Hotfix0_OnIllustClicked; // 0x60
	private static DelegateBridge __Hotfix0_OnSkillHideClick; // 0x68
	private static DelegateBridge __Hotfix0_OnSelectSkillClick; // 0x70
	private static DelegateBridge __Hotfix0_OnSelectSkillAllClick; // 0x78
	private static DelegateBridge __Hotfix0_EventOnTrainingClick; // 0x80
	private static DelegateBridge __Hotfix0_OnSpCharMissionClick; // 0x88
	private static DelegateBridge __Hotfix0_EventOnBackButtonClick; // 0x90
	private static DelegateBridge __Hotfix0_OnProfessionDetailClick; // 0x98
	private static DelegateBridge __Hotfix0_OnStarMarkCharacterClick; // 0xa0
	private static DelegateBridge __Hotfix0_OnPotentialSwitchClick; // 0xa8
	private static DelegateBridge __Hotfix0__OnJumpToEvolveState; // 0xb0
	private static DelegateBridge __Hotfix0__OnJumpFromEvolveState; // 0xb8
	private static DelegateBridge __Hotfix0__OnJumpToHandbookState; // 0xc0
	private static DelegateBridge __Hotfix0__OnJumpToToSelectSkillState; // 0xc8
	private static DelegateBridge __Hotfix0__OnJumpFromSelectSkillState; // 0xd0
	private static DelegateBridge __Hotfix0__OnJumpToSpCharMissionState; // 0xd8
	private static DelegateBridge __Hotfix0__OnJumpFromSpCharMissionState; // 0xe0
	private static DelegateBridge __Hotfix0__OnExitCharacterInfoHome; // 0xe8
	private static DelegateBridge __Hotfix0__TriggerAvg; // 0xf0
	private static DelegateBridge __Hotfix0__UniqEquipGuideEndCallback; // 0xf8
	private static DelegateBridge __Hotfix0__TriggerStarMarkToast; // 0x100
	private static DelegateBridge __Hotfix0_OnResetSkillId; // 0x108
	private static DelegateBridge __Hotfix0_OnChangeSkill; // 0x110
	private static DelegateBridge __Hotfix0_OnSelectSkillId; // 0x118
	private static DelegateBridge __Hotfix0_OnResetEquipId; // 0x120
	private static DelegateBridge __Hotfix0_OnSelectEquipId; // 0x128
	private static DelegateBridge __Hotfix0_OnChangeUniEquip; // 0x130
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x138
	private static DelegateBridge __Hotfix0_OnDetailHide; // 0x140
	private static DelegateBridge __Hotfix0_OnDetailShow; // 0x148
	private static DelegateBridge __Hotfix0_OnIllustDataApply; // 0x150
	private static DelegateBridge __Hotfix0__OnStateChange; // 0x158
	private static DelegateBridge __Hotfix0_OnEnter; // 0x160
	private static DelegateBridge __Hotfix0_OnExit; // 0x168
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x170
	private static DelegateBridge _c__Hotfix0_ctor; // 0x178


	// RVA: 0x2d40314 VA: 0x7595358314
	public override Dictionary`2 RegisterFromDataListener() { }
	// RVA: 0x2d4063c VA: 0x759535863c
	public override Dictionary`2 RegisterToDataListener() { }
	// RVA: 0x2d409d4 VA: 0x75953589d4
	public Void OnIllustrationChanged(Int32 illustIndex) { }
	// RVA: 0x2d40a4c VA: 0x7595358a4c
	public Void OnSwitchIllustrationClicked() { }
	// RVA: 0x2d40ab0 VA: 0x7595358ab0
	protected override Void OnResume() { }
	// RVA: 0x2d40c4c VA: 0x7595358c4c
	public Void OnHandBookInfo() { }
	// RVA: 0x2d40d58 VA: 0x7595358d58
	public Void OnBtnTokenClick() { }
	// RVA: 0x2d40ee8 VA: 0x7595358ee8
	public Void OnEvolveClick() { }
	// RVA: 0x2d41068 VA: 0x7595359068
	public Void OnTransClick() { }
	// RVA: 0x2d41308 VA: 0x7595359308
	public Void OnPotentialClick() { }
	// RVA: 0x2d41430 VA: 0x7595359430
	public Void OnUniEquipClick() { }
	// RVA: 0x2d41534 VA: 0x7595359534
	public Void OnUplevelClicked() { }
	// RVA: 0x2d4170c VA: 0x759535970c
	public Void OnIllustClicked() { }
	// RVA: 0x2d417b0 VA: 0x75953597b0
	public Void OnSkillHideClick() { }
	// RVA: 0x2d41a4c VA: 0x7595359a4c
	public Void OnSelectSkillClick() { }
	// RVA: 0x2d41bc4 VA: 0x7595359bc4
	public Void OnSelectSkillAllClick() { }
	// RVA: 0x2d41d3c VA: 0x7595359d3c
	public Void EventOnTrainingClick() { }
	// RVA: 0x2d41e7c VA: 0x7595359e7c
	public Void OnSpCharMissionClick() { }
	// RVA: 0x2d41f94 VA: 0x7595359f94
	public Void EventOnBackButtonClick() { }
	// RVA: 0x2d421b4 VA: 0x759535a1b4
	public Void OnProfessionDetailClick() { }
	// RVA: 0x2d422cc VA: 0x759535a2cc
	public Void OnStarMarkCharacterClick() { }
	// RVA: 0x2d425b8 VA: 0x759535a5b8
	public Void OnPotentialSwitchClick() { }
	// RVA: 0x2d42680 VA: 0x759535a680
	private Void _OnJumpToEvolveState(IStateBean stateBean) { }
	// RVA: 0x2d4279c VA: 0x759535a79c
	private Void _OnJumpFromEvolveState(IStateBean stateBean) { }
	// RVA: 0x2d42878 VA: 0x759535a878
	private Void _OnJumpToHandbookState(IStateBean stateBean) { }
	// RVA: 0x2d42994 VA: 0x759535a994
	private Void _OnJumpToToSelectSkillState(IStateBean stateBean) { }
	// RVA: 0x2d42af8 VA: 0x759535aaf8
	private Void _OnJumpFromSelectSkillState(IStateBean stateBean) { }
	// RVA: 0x2d42b80 VA: 0x759535ab80
	private Void _OnJumpToSpCharMissionState(IStateBean stateBean) { }
	// RVA: 0x2d42ce0 VA: 0x759535ace0
	private Void _OnJumpFromSpCharMissionState(IStateBean stateBean) { }
	// RVA: 0x2d42140 VA: 0x759535a140
	private Void _OnExitCharacterInfoHome() { }
	// RVA: 0x2d40b70 VA: 0x7595358b70
	private Void _TriggerAvg() { }
	// RVA: 0x2d42ee4 VA: 0x759535aee4
	private Void _UniqEquipGuideEndCallback(Story story) { }
	// RVA: 0x2d42fc4 VA: 0x759535afc4
	private Void _TriggerStarMarkToast(Boolean isSelected) { }
	// RVA: 0x2d43088 VA: 0x759535b088
	public Void OnResetSkillId() { }
	// RVA: 0x2d43178 VA: 0x759535b178
	public Void OnChangeSkill() { }
	// RVA: 0x2d434b4 VA: 0x759535b4b4
	public Void OnSelectSkillId(String skillId) { }
	// RVA: 0x2d4358c VA: 0x759535b58c
	public Void OnResetEquipId() { }
	// RVA: 0x2d4367c VA: 0x759535b67c
	public Void OnSelectEquipId(String equipId) { }
	// RVA: 0x2d43754 VA: 0x759535b754
	public Void OnChangeUniEquip() { }
	// RVA: 0x2d43a48 VA: 0x759535ba48
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2d43ab0 VA: 0x759535bab0
	public Void OnDetailHide() { }
	// RVA: 0x2d43dac VA: 0x759535bdac
	public Void OnDetailShow() { }
	// RVA: 0x2d43e70 VA: 0x759535be70
	public Void OnIllustDataApply(Int32 focusPos) { }
	// RVA: 0x2d43b38 VA: 0x759535bb38
	private Void _OnStateChange(Single target, Single duration, Action onComplete) { }
	// RVA: 0x2d43f74 VA: 0x759535bf74
	protected override Void OnEnter() { }
	// RVA: 0x2d44180 VA: 0x759535c180
	protected override Void OnExit() { }
	// RVA: 0x2d44220 VA: 0x759535c220
	private Void OnDestroy() { }
	// RVA: 0x2d442b4 VA: 0x759535c2b4
	public Void .ctor() { }
	// RVA: 0x2d44324 VA: 0x759535c324
	private Void <OnChangeSkill>b__43_0(SetDefaultSkillResponse response) { }
	// RVA: 0x2d4439c VA: 0x759535c39c
	private Void <OnDetailShow>b__54_0() { }
	// RVA: 0x2d443b0 VA: 0x759535c3b0
	private Dictionary`2 <>xLuaBaseProxy_RegisterFromDataListener() { }
	// RVA: 0x2d443b8 VA: 0x759535c3b8
	private Dictionary`2 <>xLuaBaseProxy_RegisterToDataListener() { }
	// RVA: 0x2d443c0 VA: 0x759535c3c0
	private Void <>xLuaBaseProxy_OnResume() { }
	// RVA: 0x2d443c8 VA: 0x759535c3c8
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2d443d0 VA: 0x759535c3d0
	private Void <>xLuaBaseProxy_OnExit() { }
}
```