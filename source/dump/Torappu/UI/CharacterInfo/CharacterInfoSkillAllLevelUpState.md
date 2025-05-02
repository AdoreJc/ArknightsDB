# CharacterInfoSkillAllLevelUpState

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `CharacterInfoSelectSkillBean _stateBean`

- `CharacterSkillLvlUpGroupView _upGroup`

- `CharacterSkillLvlUpGroupView _downGroup`

- `Animator _animator`

- `SimpleLayoutContent _layoutGroup`

- `Text _confirmText`

- `Tween m_tagTipTweener`

- `Boolean m_stateFlag`


## Methods

- `Void OnStateChange()`

- `Void OnUpgradeConfirmClick()`

- `Void _UpdateRequirmentViews()`

- `Void <OnUpgradeConfirmClick>b__12_0(UpgradeSkillResponse)`

- `Void <>xLuaBaseProxy_OnResume()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoSkillAllLevelUpState : PopupFadeState
{
	private CharacterInfoSelectSkillBean _stateBean; // 0x70
	private CharacterSkillLvlUpGroupView _upGroup; // 0x78
	private CharacterSkillLvlUpGroupView _downGroup; // 0x80
	private Animator _animator; // 0x88
	private SimpleLayoutContent _layoutGroup; // 0x90
	private Text _confirmText; // 0x98
	private Tween m_tagTipTweener; // 0xa0
	private const Single TWEEN_DURATION; // 0x0
	private Boolean m_stateFlag; // 0xa8
	private static DelegateBridge __Hotfix0_OnResume; // 0x0
	private static DelegateBridge __Hotfix0_OnStateChange; // 0x8
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x10
	private static DelegateBridge __Hotfix0_OnUpgradeConfirmClick; // 0x18
	private static DelegateBridge __Hotfix0__UpdateRequirmentViews; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2d488b8 VA: 0x75953608b8
	protected override Void OnResume() { }
	// RVA: 0x2d48b4c VA: 0x7595360b4c
	public Void OnStateChange() { }
	// RVA: 0x2d48c5c VA: 0x7595360c5c
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2d48cc4 VA: 0x7595360cc4
	public Void OnUpgradeConfirmClick() { }
	// RVA: 0x2d48a68 VA: 0x7595360a68
	private Void _UpdateRequirmentViews() { }
	// RVA: 0x2d48f80 VA: 0x7595360f80
	public Void .ctor() { }
	// RVA: 0x2d48ff8 VA: 0x7595360ff8
	private Void <OnUpgradeConfirmClick>b__12_0(UpgradeSkillResponse response) { }
	// RVA: 0x2d492b0 VA: 0x75953612b0
	private Void <>xLuaBaseProxy_OnResume() { }
}
```