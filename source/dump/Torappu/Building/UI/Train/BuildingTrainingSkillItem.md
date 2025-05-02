# BuildingTrainingSkillItem

**Namespace:** `Torappu.Building.UI.Train`


## Fields

- `GameObject _lvlUpIngObj`

- `Button _lvlUpBtn`

- `GameObject _onSpread`

- `GameObject _otherState`

- `GameObject _unableState`

- `GameObject _maxState`

- `Image _timeCircle`

- `Text _timeText`

- `Image _specialIcon`

- `Int32 m_targetLevel`

- `SkillItemViewModel m_cacheViewModel`

- `LevelUpSnapshot m_trainSnapshot`

- `UIPageFinder m_pageFinder`


## Methods

- `Void Update()`

- `Void BtnOnSpread()`

- `Void BtnOnUnSpread()`

- `Void BtnOnOtherSkillUpgrading()`

- `Void _RenderCountDownValues()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Train
public class BuildingTrainingSkillItem : CharacterInfoSelectSkillView
{
	private GameObject _lvlUpIngObj; // 0x40
	private Button _lvlUpBtn; // 0x48
	private GameObject _onSpread; // 0x50
	private GameObject _otherState; // 0x58
	private GameObject _unableState; // 0x60
	private GameObject _maxState; // 0x68
	private Image _timeCircle; // 0x70
	private Text _timeText; // 0x78
	private Image _specialIcon; // 0x80
	private Int32 m_targetLevel; // 0x88
	private SkillItemViewModel m_cacheViewModel; // 0x90
	private LevelUpSnapshot m_trainSnapshot; // 0x98
	private UIPageFinder m_pageFinder; // 0xc8


	// RVA: 0x3d7c80c VA: 0x759639480c
	public override Void Render(SkillItemViewModel viewModel, Int32 index, Boolean isSelected) { }
	// RVA: 0x3d7cd80 VA: 0x7596394d80
	public Void Update() { }
	// RVA: 0x3d7cd9c VA: 0x7596394d9c
	public Void BtnOnSpread() { }
	// RVA: 0x3d7cdac VA: 0x7596394dac
	public Void BtnOnUnSpread() { }
	// RVA: 0x3d7cdbc VA: 0x7596394dbc
	public Void BtnOnOtherSkillUpgrading() { }
	// RVA: 0x3d7cae8 VA: 0x7596394ae8
	private Void _RenderCountDownValues() { }
	// RVA: 0x3d7d0cc VA: 0x75963950cc
	public Void .ctor() { }
}
```