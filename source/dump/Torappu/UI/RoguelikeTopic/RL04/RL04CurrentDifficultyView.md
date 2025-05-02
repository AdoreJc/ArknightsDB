# RL04CurrentDifficultyView

**Namespace:** `Torappu.UI.RoguelikeTopic.RL04`


## Fields

- `TwoStateToggle _gradeToggle`

- `Text _gradeText`

- `GameObject _trackPoint`

- `GameObject _buffActiveTips`

- `UIAtlasImage _difficultyIconBack`

- `UIAtlasObject _difficultyAtlasObject`

- `UIPageFinder m_pageFinder`


## Methods

- `Void <>xLuaBaseProxy_OnRenderDifficulty(RoguelikeTopicDifficultyViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.RoguelikeTopic.RL04
public class RL04CurrentDifficultyView : RoguelikeTopicCurrentDifficultyBaseView
{
	private TwoStateToggle _gradeToggle; // 0x40
	private Text _gradeText; // 0x48
	private GameObject _trackPoint; // 0x50
	private GameObject _buffActiveTips; // 0x58
	private UIAtlasImage _difficultyIconBack; // 0x60
	private UIAtlasObject _difficultyAtlasObject; // 0x68
	private UIPageFinder m_pageFinder; // 0x70
	private static DelegateBridge __Hotfix0_OnRender; // 0x0
	private static DelegateBridge __Hotfix0_OnRenderDifficulty; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x26e872c VA: 0x7594d0072c
	protected override Void OnRender(RoguelikeTopicModeViewModel model) { }
	// RVA: 0x26e8880 VA: 0x7594d00880
	protected override Void OnRenderDifficulty(RoguelikeTopicDifficultyViewModel diffModel) { }
	// RVA: 0x26e8a08 VA: 0x7594d00a08
	public Void .ctor() { }
	// RVA: 0x26e8a78 VA: 0x7594d00a78
	private Void <>xLuaBaseProxy_OnRenderDifficulty(RoguelikeTopicDifficultyViewModel P0) { }
}
```