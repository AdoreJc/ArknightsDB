# Act4D0StoryDetailState

**Namespace:** `Torappu.Activity.Act4D0`


## Fields

- `Act4D0StoryDetailStateBean _stateBean`

- `Text _stageTitleText`

- `Text _stageDescText`

- `Text _stageSort`

- `Boolean _hideTopBar`

- `Image _stageImage`


## Methods

- `Void OnStartButtonPressed()`

- `Void ShowStory()`

- `Void _TrySendFinishCurrentStoryAndPlay()`

- `Void _StartStory(String)`

- `Void OnBackgroundPressed()`

- `Void <_TrySendFinishCurrentStoryAndPlay>b__10_0(Act4D0FinishStoryResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act4D0
public class Act4D0StoryDetailState : PopupFloatState
{
	private Act4D0StoryDetailStateBean _stateBean; // 0x70
	private Text _stageTitleText; // 0x78
	private Text _stageDescText; // 0x80
	private Text _stageSort; // 0x88
	private Boolean _hideTopBar; // 0x90
	private Image _stageImage; // 0x98
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge __Hotfix0_OnStartButtonPressed; // 0x10
	private static DelegateBridge __Hotfix0_ShowStory; // 0x18
	private static DelegateBridge __Hotfix0__TrySendFinishCurrentStoryAndPlay; // 0x20
	private static DelegateBridge __Hotfix0__StartStory; // 0x28
	private static DelegateBridge __Hotfix0_OnBackgroundPressed; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x31de684 VA: 0x75957f6684
	public override IStateBean GetCacheBean() { }
	// RVA: 0x31de6ec VA: 0x75957f66ec
	protected override Void OnEnter() { }
	// RVA: 0x31de9a4 VA: 0x75957f69a4
	public Void OnStartButtonPressed() { }
	// RVA: 0x31dec68 VA: 0x75957f6c68
	public Void ShowStory() { }
	// RVA: 0x31dea24 VA: 0x75957f6a24
	private Void _TrySendFinishCurrentStoryAndPlay() { }
	// RVA: 0x31decd0 VA: 0x75957f6cd0
	private Void _StartStory(String storyId) { }
	// RVA: 0x31deef4 VA: 0x75957f6ef4
	public Void OnBackgroundPressed() { }
	// RVA: 0x31def80 VA: 0x75957f6f80
	public Void .ctor() { }
	// RVA: 0x31deff0 VA: 0x75957f6ff0
	private Void <_TrySendFinishCurrentStoryAndPlay>b__10_0(Act4D0FinishStoryResponse response) { }
	// RVA: 0x31df00c VA: 0x75957f700c
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```