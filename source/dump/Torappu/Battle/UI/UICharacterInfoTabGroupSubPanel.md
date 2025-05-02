# UICharacterInfoTabGroupSubPanel

**Namespace:** `Torappu.Battle.UI`


## Fields

- `UICharacterTabGroup _uiCharacterTabGroup`

- `Text _subProfessionTraitDescriptionLabel`

- `Text _traitDescriptionText`

- `Text _subProfessionText`

- `Image _subProfessionImage`

- `UIAutoSlideRect _skillDescAutoSlide`

- `Text _skillNameLabel`

- `Text _skillDescriptionLabel`

- `Image _skillIcon`

- `UISkillTagGroup _skillTagGroup`

- `RectTransform _skillPanel`

- `UICharacterTalentPair _talentTextPair`

- `LayoutGroup _talentLayoutGroup`

- `Boolean m_needUpdateAutoSlide`

- `Int32 m_infoTabEnableMask`


## Properties

- `UICharacterTabGroup uiCharacterTabGroup`


## Methods

- `UICharacterTabGroup get_uiCharacterTabGroup()`

- `Void ActiveAdditionTabs(Int32, Boolean)`

- `Boolean _UpdateTalent(CharacterData, List`1, Boolean, Int32, EvolvePhase, Int32)`

- `Void _UpdateSkillData(SkillData, BattleCharacterData)`

- `String _ParseSkillDescription(String, Blackboard, BattleCharacterData)`

- `Void <>xLuaBaseProxy_OnInit(UICharacterInfoPanel)`

- `Void <>xLuaBaseProxy_SetData(ObjectPtr`1, ModeType, Card)`

- `Void <>xLuaBaseProxy_UpdateData(ObjectPtr`1, ModeType, Card)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UICharacterInfoTabGroupSubPanel : UICharacterInfoSubPanel
{
	private UICharacterTabGroup _uiCharacterTabGroup; // 0x20
	private Text _subProfessionTraitDescriptionLabel; // 0x28
	private Text _traitDescriptionText; // 0x30
	private Text _subProfessionText; // 0x38
	private Image _subProfessionImage; // 0x40
	private UIAutoSlideRect _skillDescAutoSlide; // 0x48
	private Text _skillNameLabel; // 0x50
	private Text _skillDescriptionLabel; // 0x58
	private Image _skillIcon; // 0x60
	private UISkillTagGroup _skillTagGroup; // 0x68
	private RectTransform _skillPanel; // 0x70
	private UICharacterTalentPair _talentTextPair; // 0x78
	private LayoutGroup _talentLayoutGroup; // 0x80
	private const Int32 MAX_TALENT_SHOW_COUNT; // 0x0
	private List`1 m_talentTextPair; // 0x88
	private Boolean m_needUpdateAutoSlide; // 0x90
	private List`1 m_skillTagsCache; // 0x98
	private Int32 m_infoTabEnableMask; // 0xa0
	private List`1 m_sharedTalentList; // 0xa8
	private static DelegateBridge __Hotfix0_get_uiCharacterTabGroup; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_Reset; // 0x10
	private static DelegateBridge __Hotfix0_SetData; // 0x18
	private static DelegateBridge __Hotfix0_ActiveAdditionTabs; // 0x20
	private static DelegateBridge __Hotfix0__UpdateTalent; // 0x28
	private static DelegateBridge __Hotfix0__UpdateSkillData; // 0x30
	private static DelegateBridge __Hotfix0__ParseSkillDescription; // 0x38
	private static DelegateBridge __Hotfix0_UpdateData; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public UICharacterTabGroup uiCharacterTabGroup { get; }

	// RVA: 0x2038630 VA: 0x7594650630
	public UICharacterTabGroup get_uiCharacterTabGroup() { }
	// RVA: 0x2038698 VA: 0x7594650698
	public override Void OnInit(UICharacterInfoPanel parent) { }
	// RVA: 0x2038728 VA: 0x7594650728
	public virtual Void Reset() { }
	// RVA: 0x2038a1c VA: 0x7594650a1c
	public override Void SetData(ObjectPtr`1 characterPtr, ModeType mode, Card card) { }
	// RVA: 0x2039a28 VA: 0x7594651a28
	public Void ActiveAdditionTabs(Int32 addtionMask, Boolean isActive) { }
	// RVA: 0x20392f0 VA: 0x75946512f0
	private Boolean _UpdateTalent(CharacterData data, List`1 queries, Boolean isToken, Int32 level, EvolvePhase phase, Int32 potential) { }
	// RVA: 0x2039694 VA: 0x7594651694
	private Void _UpdateSkillData(SkillData data, BattleCharacterData battleCharacterData) { }
	// RVA: 0x2039ad8 VA: 0x7594651ad8
	private String _ParseSkillDescription(String description, Blackboard blackboard, BattleCharacterData battleCharacterData) { }
	// RVA: 0x2039c50 VA: 0x7594651c50
	public override Void UpdateData(ObjectPtr`1 characterPtr, ModeType mode, Card card) { }
	// RVA: 0x2039de0 VA: 0x7594651de0
	public Void .ctor() { }
	// RVA: 0x2039ef0 VA: 0x7594651ef0
	private Void <>xLuaBaseProxy_OnInit(UICharacterInfoPanel P0) { }
	// RVA: 0x2039ef4 VA: 0x7594651ef4
	private Void <>xLuaBaseProxy_SetData(ObjectPtr`1 P0, ModeType P1, Card P2) { }
	// RVA: 0x2039ef8 VA: 0x7594651ef8
	private Void <>xLuaBaseProxy_UpdateData(ObjectPtr`1 P0, ModeType P1, Card P2) { }
}
```