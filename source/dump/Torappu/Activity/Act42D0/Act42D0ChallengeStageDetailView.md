# Act42D0ChallengeStageDetailView

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `Text _textStageName`

- `Text _textMissionCompletedCount`

- `Text _textMissionTotalCount`

- `Text _textStageDescription`

- `Text _textTipsSelectStage`

- `Text _textChallengeDesc`

- `Text _textChallengeName`

- `SimpleLayoutContent _content`

- `UIAnimationLocation _animDetailEnter`

- `CanvasGroup _canvasBottomMenuNotEmpty`

- `CanvasGroup _canvasBottomMenuEmpty`

- `CanvasGroup _canvasDetailEmpty`

- `Single _fadeDurationDetail`

- `Single _fadeDurationBottomMenu`

- `Boolean m_isInited`

- `Adapter m_adapter`

- `UIPageFinder m_pageFinder`

- `Act42D0ChallengeStageViewModel m_stageViewModel`

- `AnimationSwitchTween m_animDetailEnter`

- `FadeSwitchTween m_fadeBottomMenuNotEmpty`

- `FadeSwitchTween m_fadeBottomMenuEmpty`

- `FadeSwitchTween m_fadeDetailEmpty`

- `String m_stageSelected`


## Methods

- `Void _InitIfNot()`

- `Void OnClickMap()`

- `Void OnClickEnemy()`

- `Void OnClickBattleStart()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0ChallengeStageDetailView : DataBinder`1
{
	private Text _textStageName; // 0x20
	private Text _textMissionCompletedCount; // 0x28
	private Text _textMissionTotalCount; // 0x30
	private Text _textStageDescription; // 0x38
	private Text _textTipsSelectStage; // 0x40
	private Text _textChallengeDesc; // 0x48
	private Text _textChallengeName; // 0x50
	private SimpleLayoutContent _content; // 0x58
	private UIAnimationLocation _animDetailEnter; // 0x60
	private CanvasGroup _canvasBottomMenuNotEmpty; // 0x70
	private CanvasGroup _canvasBottomMenuEmpty; // 0x78
	private CanvasGroup _canvasDetailEmpty; // 0x80
	private Single _fadeDurationDetail; // 0x88
	private Single _fadeDurationBottomMenu; // 0x8c
	private const Int32 MISSION_SLOT_COUNT; // 0x0
	private const String MISSION_SLOT_TOTAL_COUNT; // 0x0
	private List`1 m_missionItemDataList; // 0x90
	private Boolean m_isInited; // 0x98
	private Adapter m_adapter; // 0xa0
	private UIPageFinder m_pageFinder; // 0xa8
	private Act42D0ChallengeStageViewModel m_stageViewModel; // 0xb8
	private AnimationSwitchTween m_animDetailEnter; // 0xc0
	private FadeSwitchTween m_fadeBottomMenuNotEmpty; // 0xc8
	private FadeSwitchTween m_fadeBottomMenuEmpty; // 0xd0
	private FadeSwitchTween m_fadeDetailEmpty; // 0xd8
	private String m_stageSelected; // 0xe0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge __Hotfix0_OnClickMap; // 0x10
	private static DelegateBridge __Hotfix0_OnClickEnemy; // 0x18
	private static DelegateBridge __Hotfix0_OnClickBattleStart; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x32093e8 VA: 0x75958213e8
	private Void _InitIfNot() { }
	// RVA: 0x32096e8 VA: 0x75958216e8
	public override Void OnValueChanged(Act42D0ChallengeStageGroupProperty property) { }
	// RVA: 0x3209bcc VA: 0x7595821bcc
	public Void OnClickMap() { }
	// RVA: 0x3209cd4 VA: 0x7595821cd4
	public Void OnClickEnemy() { }
	// RVA: 0x3209ddc VA: 0x7595821ddc
	public Void OnClickBattleStart() { }
	// RVA: 0x3209e90 VA: 0x7595821e90
	public Void .ctor() { }
}
```