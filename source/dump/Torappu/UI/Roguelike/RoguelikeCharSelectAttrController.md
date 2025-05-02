# RoguelikeCharSelectAttrController

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Text _name`

- `Text _codeName`

- `Image _evolvePhase`

- `Image _maxEvolvePhase`

- `Text _currentLevel`

- `Text _maxLevel`

- `Text _maxHp`

- `Text _atk`

- `Text _def`

- `Text _res`

- `Text _reviveTimeDesc`

- `Text _cost`

- `Text _blockNum`

- `Text _attackSpeedDesc`

- `Text _evolveLimitText`

- `UICharacterAttackRangeWidget _attackRange`

- `RoguelikeCharSelectSkillGroup _skillGroup`

- `RoguelikeCharSelectBranchGroup _branchGroup`

- `GameObject _haveCharPart`

- `GameObject _noCharPart`

- `Int32 m_chrInstIdCache`

- `RoguelikeCharAttrTabTypeMessage onTabClickEvent`

- `UIStringEvent onSkillSelectEvent`

- `UIStringEvent onBranchSelectEvent`


## Methods

- `Void Render(RoguelikeCharCardViewModel, Boolean)`

- `Void _RenderTab(RoguelikeCharCardViewModel)`

- `Void _RenderSkillGroup(RoguelikeCharCardViewModel)`

- `Void _RenderBranchGroup(RoguelikeCharCardViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeCharSelectAttrController : MonoBehaviour, IHotfixable
{
	private Text _name; // 0x18
	private Text _codeName; // 0x20
	private Image _evolvePhase; // 0x28
	private Image _maxEvolvePhase; // 0x30
	private Text _currentLevel; // 0x38
	private Text _maxLevel; // 0x40
	private Text _maxHp; // 0x48
	private Text _atk; // 0x50
	private Text _def; // 0x58
	private Text _res; // 0x60
	private Text _reviveTimeDesc; // 0x68
	private Text _cost; // 0x70
	private Text _blockNum; // 0x78
	private Text _attackSpeedDesc; // 0x80
	private Text _evolveLimitText; // 0x88
	private UICharacterAttackRangeWidget _attackRange; // 0x90
	private RoguelikeCharSelectSkillGroup _skillGroup; // 0x98
	private RoguelikeCharSelectBranchGroup _branchGroup; // 0xa0
	private GameObject _haveCharPart; // 0xa8
	private GameObject _noCharPart; // 0xb0
	private List`1 _tabList; // 0xb8
	private Int32 m_chrInstIdCache; // 0xc0
	public RoguelikeCharAttrTabTypeMessage onTabClickEvent; // 0xc8
	public UIStringEvent onSkillSelectEvent; // 0xd0
	public UIStringEvent onBranchSelectEvent; // 0xd8
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__RenderTab; // 0x8
	private static DelegateBridge __Hotfix0__RenderSkillGroup; // 0x10
	private static DelegateBridge __Hotfix0__RenderBranchGroup; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2acbf54 VA: 0x75950e3f54
	public Void Render(RoguelikeCharCardViewModel viewModel, Boolean isSelected) { }
	// RVA: 0x2acc3ac VA: 0x75950e43ac
	private Void _RenderTab(RoguelikeCharCardViewModel viewModel) { }
	// RVA: 0x2acc590 VA: 0x75950e4590
	private Void _RenderSkillGroup(RoguelikeCharCardViewModel viewModel) { }
	// RVA: 0x2acc780 VA: 0x75950e4780
	private Void _RenderBranchGroup(RoguelikeCharCardViewModel viewModel) { }
	// RVA: 0x2accdc0 VA: 0x75950e4dc0
	public Void .ctor() { }
}
```