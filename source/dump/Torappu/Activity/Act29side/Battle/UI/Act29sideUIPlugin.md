# Act29sideUIPlugin

**Namespace:** `Torappu.Activity.Act29side.Battle.UI`


## Fields

- `Color _enthuBarColor`

- `Color _depressedBarColor`

- `Color _emptyBarColor`

- `UIAtlasImage _progressMark`

- `UIAtlasImage _progressMarkDepressed`

- `UIAtlasImage _progressMarkEnthu`

- `UIAtlasImage _progressMarkEmpty`

- `GameObject _backgroundLine`

- `GameObject _backgroundQuad1`

- `GameObject _backgroundQuad2`

- `GameObject _backgroundQuad3`

- `Act29sideUIProgressBar _progressBar`

- `RectTransform _anchor`

- `RectTransform _backgroundQuadsAnchor`

- `RectTransform _backgroundLinesAnchor`

- `RectTransform _progressBarAnchor`

- `String _evnSystemKey`

- `Act29sideUIProgressBarBoss _progressBarBoss`

- `AnimationWrapper _animWrapper`

- `Act29SideManager m_evnManager`

- `Single m_progress`

- `Boolean m_hasGameStarted`

- `Boolean m_isValid`

- `Boolean m_isFadingIn`

- `Boolean m_isFadingOut`

- `Single m_tweenTime`

- `Int32 m_currentStage`

- `Single m_totalStageLength`

- `Single m_standardLength`

- `Boolean m_hasBeenControlledByBoss`

- `Tween m_markEnthuTweenFO`

- `Tween m_markEnthuTweenFI`

- `Tween m_markDepressedTweenFO`

- `Tween m_markDepressedTweenFI`

- `Tween m_markEmptyTweenFO`

- `Tween m_markEmptyTweenFI`

- `Tween m_markProgressTweenFI`

- `Tween m_markProgressTweenFO`


## Methods

- `Boolean _CheckAllResourcesValid()`

- `Boolean _InitAllMembers()`

- `Void _SetProgressBars()`

- `Void _SetBackground()`

- `Single _ComputeProgress()`

- `Void _ComputeStageList()`

- `Void _CloseNormalBars()`

- `Void _FadeEnthuMark(Boolean)`

- `Void _FadeDepressedMark(Boolean)`

- `Void _FadeEmptyMark(Boolean)`

- `Void _FadeProgressMark(Boolean)`

- `Void _DoFade(Boolean, ref, ref)`

- `Void <>xLuaBaseProxy_OnGameStart()`

- `Void <>xLuaBaseProxy_UpdateGameInfo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act29side.Battle.UI
public class Act29sideUIPlugin : Plugin
{
	private Color _enthuBarColor; // 0x28
	private Color _depressedBarColor; // 0x38
	private Color _emptyBarColor; // 0x48
	private UIAtlasImage _progressMark; // 0x58
	private UIAtlasImage _progressMarkDepressed; // 0x60
	private UIAtlasImage _progressMarkEnthu; // 0x68
	private UIAtlasImage _progressMarkEmpty; // 0x70
	private GameObject _backgroundLine; // 0x78
	private GameObject _backgroundQuad1; // 0x80
	private GameObject _backgroundQuad2; // 0x88
	private GameObject _backgroundQuad3; // 0x90
	private Act29sideUIProgressBar _progressBar; // 0x98
	private RectTransform _anchor; // 0xa0
	private RectTransform _backgroundQuadsAnchor; // 0xa8
	private RectTransform _backgroundLinesAnchor; // 0xb0
	private RectTransform _progressBarAnchor; // 0xb8
	private String _evnSystemKey; // 0xc0
	private Act29sideUIProgressBarBoss _progressBarBoss; // 0xc8
	private AnimationWrapper _animWrapper; // 0xd0
	private Act29SideManager m_evnManager; // 0xd8
	private Single m_progress; // 0xe0
	private Boolean m_hasGameStarted; // 0xe4
	private Boolean m_isValid; // 0xe5
	private Boolean m_isFadingIn; // 0xe6
	private Boolean m_isFadingOut; // 0xe7
	private Single m_tweenTime; // 0xe8
	private Int32 m_currentStage; // 0xec
	private Single m_totalStageLength; // 0xf0
	private List`1 m_stageInfoList; // 0xf8
	private List`1 m_preTimeList; // 0x100
	private Single m_standardLength; // 0x108
	private List`1 m_progressBars; // 0x110
	private Boolean m_hasBeenControlledByBoss; // 0x118
	private Tween m_markEnthuTweenFO; // 0x120
	private Tween m_markEnthuTweenFI; // 0x128
	private Tween m_markDepressedTweenFO; // 0x130
	private Tween m_markDepressedTweenFI; // 0x138
	private Tween m_markEmptyTweenFO; // 0x140
	private Tween m_markEmptyTweenFI; // 0x148
	private Tween m_markProgressTweenFI; // 0x150
	private Tween m_markProgressTweenFO; // 0x158
	private const String START_ANIM; // 0x0
	private const String SWITCH_AUDIO_ANIM; // 0x0
	private const String BOSS_APPEAR_ANIM; // 0x0
	private const Single DECO_QUAD_LADDER_3; // 0x0
	private const Single DECO_QUAD_LADDER_2; // 0x0
	private const Single DECO_QUAD_LADDER_1; // 0x0
	private static DelegateBridge __Hotfix0_OnGameStart; // 0x0
	private static DelegateBridge __Hotfix0_UpdateGameInfo; // 0x8
	private static DelegateBridge __Hotfix0__CheckAllResourcesValid; // 0x10
	private static DelegateBridge __Hotfix0__InitAllMembers; // 0x18
	private static DelegateBridge __Hotfix0__SetProgressBars; // 0x20
	private static DelegateBridge __Hotfix0__SetBackground; // 0x28
	private static DelegateBridge __Hotfix0__ComputeProgress; // 0x30
	private static DelegateBridge __Hotfix0__ComputeStageList; // 0x38
	private static DelegateBridge __Hotfix0__CloseNormalBars; // 0x40
	private static DelegateBridge __Hotfix0__FadeEnthuMark; // 0x48
	private static DelegateBridge __Hotfix0__FadeDepressedMark; // 0x50
	private static DelegateBridge __Hotfix0__FadeEmptyMark; // 0x58
	private static DelegateBridge __Hotfix0__FadeProgressMark; // 0x60
	private static DelegateBridge __Hotfix0__DoFade; // 0x68
	private static DelegateBridge _c__Hotfix0_ctor; // 0x70


	// RVA: 0x3264418 VA: 0x759587c418
	public override Void OnGameStart() { }
	// RVA: 0x3265494 VA: 0x759587d494
	public override Void UpdateGameInfo() { }
	// RVA: 0x3264608 VA: 0x759587c608
	private Boolean _CheckAllResourcesValid() { }
	// RVA: 0x3264848 VA: 0x759587c848
	private Boolean _InitAllMembers() { }
	// RVA: 0x3264ea0 VA: 0x759587cea0
	private Void _SetProgressBars() { }
	// RVA: 0x3264bf0 VA: 0x759587cbf0
	private Void _SetBackground() { }
	// RVA: 0x326624c VA: 0x759587e24c
	private Single _ComputeProgress() { }
	// RVA: 0x3266d80 VA: 0x759587ed80
	private Void _ComputeStageList() { }
	// RVA: 0x3265aec VA: 0x759587daec
	private Void _CloseNormalBars() { }
	// RVA: 0x326675c VA: 0x759587e75c
	private Void _FadeEnthuMark(Boolean isFadeIn) { }
	// RVA: 0x3266514 VA: 0x759587e514
	private Void _FadeDepressedMark(Boolean isFadeIn) { }
	// RVA: 0x3266638 VA: 0x759587e638
	private Void _FadeEmptyMark(Boolean isFadeIn) { }
	// RVA: 0x3266880 VA: 0x759587e880
	private Void _FadeProgressMark(Boolean isFadeIn) { }
	// RVA: 0x3267594 VA: 0x759587f594
	private Void _DoFade(Boolean isFadeIn, ref UIAtlasImage atlasImage, ref Tween tween) { }
	// RVA: 0x3267774 VA: 0x759587f774
	public Void .ctor() { }
	// RVA: 0x3267824 VA: 0x759587f824
	private Void <>xLuaBaseProxy_OnGameStart() { }
	// RVA: 0x326782c VA: 0x759587f82c
	private Void <>xLuaBaseProxy_UpdateGameInfo() { }
}
```