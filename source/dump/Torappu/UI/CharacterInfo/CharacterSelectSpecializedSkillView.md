# CharacterSelectSpecializedSkillView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `GameObject _lvlUpIngObj`

- `GameObject _skillStateObj`

- `Image _timeCircle`

- `Image _specialIcon`

- `Text _startLevel`

- `Text _targetLevel`

- `Text _currentLevel`

- `GameObject _hasSpecializedPart`

- `GameObject _noSpecializedPart`

- `CharacterInfoSkillView _skillView`

- `Single m_specialTime`

- `Int32 m_targetLevel`

- `SkillItemViewModel m_cacheViewModel`

- `LevelUpSnapshot m_trainSnapshot`

- `UIPageFinder m_pageFinder`


## Methods

- `Void Render(SkillItemViewModel, Int32, Boolean, Boolean)`

- `Void Update()`

- `Void BtnOnOtherSkillUpgrading()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterSelectSpecializedSkillView : MonoBehaviour, IHotfixable
{
	private GameObject _lvlUpIngObj; // 0x18
	private GameObject _skillStateObj; // 0x20
	private Image _timeCircle; // 0x28
	private Image _specialIcon; // 0x30
	private Text _startLevel; // 0x38
	private Text _targetLevel; // 0x40
	private Text _currentLevel; // 0x48
	private GameObject _hasSpecializedPart; // 0x50
	private GameObject _noSpecializedPart; // 0x58
	protected CharacterInfoSkillView _skillView; // 0x60
	private Single m_specialTime; // 0x68
	private Int32 m_targetLevel; // 0x6c
	private SkillItemViewModel m_cacheViewModel; // 0x70
	private LevelUpSnapshot m_trainSnapshot; // 0x78
	private UIPageFinder m_pageFinder; // 0xa8
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_Update; // 0x8
	private static DelegateBridge __Hotfix0_BtnOnOtherSkillUpgrading; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2d8928c VA: 0x75953a128c
	public Void Render(SkillItemViewModel viewModel, Int32 index, Boolean isSelected, Boolean hasSpecialFlag) { }
	// RVA: 0x2d89b00 VA: 0x75953a1b00
	public Void Update() { }
	// RVA: 0x2d89bd8 VA: 0x75953a1bd8
	public Void BtnOnOtherSkillUpgrading() { }
	// RVA: 0x2d89ca0 VA: 0x75953a1ca0
	public Void .ctor() { }
}
```