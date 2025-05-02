# CharacterInfoSkillSpecializedLevelUpState

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `CharacterInfoSelectSkillBean _stateBean`

- `CharacterInfoSkillLevelUpSpecializedView _nowLevel`

- `CharacterInfoSkillLevelUpSpecializedView _upLevel`

- `Text _timeText`

- `Text _hourText`

- `Image _specialLvl`

- `Image _specialLvlGlow`

- `SimpleLayoutContent _layoutGroup`

- `RectTransform _grid`

- `Tween m_tagTipTweener`


## Methods

- `Void OnUpgradeConfirmClick()`

- `Void EventOnExitSelectSkill()`

- `IEnumerator UpdateLayout(RectTransform)`

- `Void <OnUpgradeConfirmClick>b__12_0(UpgradeSpecializationResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoSkillSpecializedLevelUpState : State
{
	private CharacterInfoSelectSkillBean _stateBean; // 0x50
	private CharacterInfoSkillLevelUpSpecializedView _nowLevel; // 0x58
	private CharacterInfoSkillLevelUpSpecializedView _upLevel; // 0x60
	private Text _timeText; // 0x68
	private Text _hourText; // 0x70
	private Image _specialLvl; // 0x78
	private Image _specialLvlGlow; // 0x80
	private SimpleLayoutContent _layoutGroup; // 0x88
	private RectTransform _grid; // 0x90
	private Tween m_tagTipTweener; // 0x98
	private const Single TWEEN_DURATION; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnUpgradeConfirmClick; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge __Hotfix0_OnResume; // 0x18
	private static DelegateBridge __Hotfix0_EventOnExitSelectSkill; // 0x20
	private static DelegateBridge __Hotfix0_UpdateLayout; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2d495d0 VA: 0x75953615d0
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2d49638 VA: 0x7595361638
	public Void OnUpgradeConfirmClick() { }
	// RVA: 0x2d4984c VA: 0x759536184c
	protected override Void OnEnter() { }
	// RVA: 0x2d49c88 VA: 0x7595361c88
	protected override Void OnResume() { }
	// RVA: 0x2d49dd0 VA: 0x7595361dd0
	public Void EventOnExitSelectSkill() { }
	// RVA: 0x2d49d10 VA: 0x7595361d10
	private IEnumerator UpdateLayout(RectTransform rect) { }
	// RVA: 0x2d49e84 VA: 0x7595361e84
	public Void .ctor() { }
	// RVA: 0x2d49ef4 VA: 0x7595361ef4
	private Void <OnUpgradeConfirmClick>b__12_0(UpgradeSpecializationResponse response) { }
	// RVA: 0x2d49fe0 VA: 0x7595361fe0
	private Void <>xLuaBaseProxy_OnEnter() { }
	// RVA: 0x2d49fe8 VA: 0x7595361fe8
	private Void <>xLuaBaseProxy_OnResume() { }
}
```