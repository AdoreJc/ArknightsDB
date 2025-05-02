# CharacterTokenDetailShowView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Text _maxHp`

- `Text _atk`

- `Text _def`

- `Text _res`

- `Text _reviveTime`

- `Text _cost`

- `Text _blockNum`

- `Text _atkSpeed`

- `Text _textName`

- `UICharacterAttackRangeWidget _attackRange`

- `Image _tokenAvatar`

- `GameObject _tokenAvatarObj`

- `Text _tokenPos`

- `GameObject _skillPanel`

- `GameObject _talentPanel`

- `GameObject _subProfPanel`

- `UISkillTagGroup _uiSkillTagGroup`

- `Text _skillName`

- `UICommentedText _skillDesc`

- `Image _skillIcon`

- `UICommentedText _subProfDesc`

- `SimpleLayoutContent _talentListContent`

- `CharTokenViewModel m_tokenViewModel`

- `TalentListAdapter m_adapter`

- `Boolean m_isInited`

- `UIPageFinder m_pageFinder`


## Methods

- `Void Render(CharTokenViewModel)`

- `Void _InitIfNot()`

- `Void _ShowAttribute()`

- `Void _ShowSubProf()`

- `Void _ShowTalent()`

- `Void _ShowSkill()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterTokenDetailShowView : MonoBehaviour, IHotfixable
{
	private Text _maxHp; // 0x18
	private Text _atk; // 0x20
	private Text _def; // 0x28
	private Text _res; // 0x30
	private Text _reviveTime; // 0x38
	private Text _cost; // 0x40
	private Text _blockNum; // 0x48
	private Text _atkSpeed; // 0x50
	private Text _textName; // 0x58
	private UICharacterAttackRangeWidget _attackRange; // 0x60
	private Image _tokenAvatar; // 0x68
	private GameObject _tokenAvatarObj; // 0x70
	private Text _tokenPos; // 0x78
	private GameObject _skillPanel; // 0x80
	private GameObject _talentPanel; // 0x88
	private GameObject _subProfPanel; // 0x90
	private UISkillTagGroup _uiSkillTagGroup; // 0x98
	private Text _skillName; // 0xa0
	private UICommentedText _skillDesc; // 0xa8
	private Image _skillIcon; // 0xb0
	private UICommentedText _subProfDesc; // 0xb8
	private SimpleLayoutContent _talentListContent; // 0xc0
	private CharTokenViewModel m_tokenViewModel; // 0xc8
	private TalentListAdapter m_adapter; // 0xd0
	private Boolean m_isInited; // 0xd8
	private UIPageFinder m_pageFinder; // 0xe0
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__ShowAttribute; // 0x10
	private static DelegateBridge __Hotfix0__ShowSubProf; // 0x18
	private static DelegateBridge __Hotfix0__ShowTalent; // 0x20
	private static DelegateBridge __Hotfix0__ShowSkill; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2d69ec4 VA: 0x7595381ec4
	public Void Render(CharTokenViewModel tokenData) { }
	// RVA: 0x2d6a0c8 VA: 0x75953820c8
	private Void _InitIfNot() { }
	// RVA: 0x2d6a1a0 VA: 0x75953821a0
	private Void _ShowAttribute() { }
	// RVA: 0x2d6a350 VA: 0x7595382350
	private Void _ShowSubProf() { }
	// RVA: 0x2d6a44c VA: 0x759538244c
	private Void _ShowTalent() { }
	// RVA: 0x2d6a4f4 VA: 0x75953824f4
	private Void _ShowSkill() { }
	// RVA: 0x2d6a6dc VA: 0x75953826dc
	public Void .ctor() { }
}
```