# RoguelikeCharCommonSkillItem

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Image _spriteIcon`

- `GameObject _lockedPart`

- `GameObject _skillLevelPart`

- `GameObject _skillSpecPart`

- `Text _skillLevel`

- `Image _skillSpec`

- `UIColorGraphic _rayCast`

- `GameObject _selectedObj`

- `AnimationWrapper _unlockShining`

- `AnimationWrapper _unselectedShining`

- `String m_cacheSkillId`


## Methods

- `Void RenderSkill(RoguelikeCharSelectSkillItemViewModel, Boolean, Boolean, Boolean, Boolean, Boolean)`

- `Void _PlayUnlockedAnim()`

- `Void _PlayUnselectedAnim()`

- `Void OnClick()`

- `Void <_PlayUnlockedAnim>b__14_0(String)`

- `Void <_PlayUnselectedAnim>b__15_0(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeCharCommonSkillItem : MonoBehaviour, IHotfixable
{
	private Image _spriteIcon; // 0x18
	private GameObject _lockedPart; // 0x20
	private GameObject _skillLevelPart; // 0x28
	private GameObject _skillSpecPart; // 0x30
	private Text _skillLevel; // 0x38
	private Image _skillSpec; // 0x40
	private UIColorGraphic _rayCast; // 0x48
	private GameObject _selectedObj; // 0x50
	private AnimationWrapper _unlockShining; // 0x58
	private AnimationWrapper _unselectedShining; // 0x60
	public Action`1 onClickSkill; // 0x68
	private String m_cacheSkillId; // 0x70
	private const String SKILL_SHINE_ANIM_NAME; // 0x0
	private static DelegateBridge __Hotfix0_RenderSkill; // 0x0
	private static DelegateBridge __Hotfix0__PlayUnlockedAnim; // 0x8
	private static DelegateBridge __Hotfix0__PlayUnselectedAnim; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2acb074 VA: 0x75950e3074
	public Void RenderSkill(RoguelikeCharSelectSkillItemViewModel skillViewModel, Boolean isSelected, Boolean iconHighlight, Boolean enableClick, Boolean unselectShine, Boolean unlockShine) { }
	// RVA: 0x2acb500 VA: 0x75950e3500
	private Void _PlayUnlockedAnim() { }
	// RVA: 0x2acb374 VA: 0x75950e3374
	private Void _PlayUnselectedAnim() { }
	// RVA: 0x2acb68c VA: 0x75950e368c
	public Void OnClick() { }
	// RVA: 0x2acb718 VA: 0x75950e3718
	public Void .ctor() { }
	// RVA: 0x2acb788 VA: 0x75950e3788
	private Void <_PlayUnlockedAnim>b__14_0(String val) { }
	// RVA: 0x2acb7b0 VA: 0x75950e37b0
	private Void <_PlayUnselectedAnim>b__15_0(String val) { }
}
```