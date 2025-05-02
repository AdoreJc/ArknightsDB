# SixStarBattleFinishView

**Namespace:** `Torappu.UI.BattleFinish`


## Fields

- `UIFullScreenImage _blurBackground`

- `Text _textStageName`

- `Text _textStageCode`

- `TwoStateToggle _rankPanelState`

- `RectTransform _rankPanelRoot`

- `BattleFinishIllustView _ilustView`

- `UIAnimationLocation _entryAnim`

- `SixStarBattleFinishViewModel m_viewModel`

- `Tween m_entryAnimTween`

- `Int32 m_targetTimerLoopCount`

- `Boolean m_isInited`

- `Int32 m_timerId`


## Methods

- `Void _PlayEntryAnim()`

- `Void _RenderStageInfo()`

- `Void _RenderRankInfo()`

- `Void _RenderCharInfo()`

- `Void _InitIfNot()`

- `Void _ResetAnim()`

- `Void _TimerTickCallBack()`

- `Void _StartTimer()`

- `Void _ClearTimer()`

- `Void EventOnViewClicked()`

- `Void OnDestroy()`

- `IEnumerator <>xLuaBaseProxy_ShowEnterEffectCoroutine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BattleFinish
public class SixStarBattleFinishView : DynBattleFinishView
{
	private const Single TWEEN_DELAY; // 0x0
	private const Single TICK_TIME; // 0x0
	private UIFullScreenImage _blurBackground; // 0x20
	private Text _textStageName; // 0x28
	private Text _textStageCode; // 0x30
	private TwoStateToggle _rankPanelState; // 0x38
	private RectTransform _rankPanelRoot; // 0x40
	private SixStarBattleFinishTimeTickListener[] _timerTickListeners; // 0x48
	private BattleFinishIllustView _ilustView; // 0x50
	private UIAnimationLocation _entryAnim; // 0x58
	private SixStarBattleFinishViewModel m_viewModel; // 0x68
	private Tween m_entryAnimTween; // 0x70
	private Int32 m_targetTimerLoopCount; // 0x78
	private Boolean m_isInited; // 0x7c
	private Int32 m_timerId; // 0x80
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_ShowEnterEffectCoroutine; // 0x8
	private static DelegateBridge __Hotfix0__PlayEntryAnim; // 0x10
	private static DelegateBridge __Hotfix0__RenderStageInfo; // 0x18
	private static DelegateBridge __Hotfix0__RenderRankInfo; // 0x20
	private static DelegateBridge __Hotfix0__RenderCharInfo; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge __Hotfix0__ResetAnim; // 0x38
	private static DelegateBridge __Hotfix0__TimerTickCallBack; // 0x40
	private static DelegateBridge __Hotfix0__StartTimer; // 0x48
	private static DelegateBridge __Hotfix0__ClearTimer; // 0x50
	private static DelegateBridge __Hotfix0_EventOnViewClicked; // 0x58
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68


	// RVA: 0x2e95254 VA: 0x75954ad254
	protected override Void OnInit() { }
	// RVA: 0x2e95824 VA: 0x75954ad824
	public override IEnumerator ShowEnterEffectCoroutine() { }
	// RVA: 0x2e958f8 VA: 0x75954ad8f8
	private Void _PlayEntryAnim() { }
	// RVA: 0x2e95768 VA: 0x75954ad768
	private Void _RenderStageInfo() { }
	// RVA: 0x2e956dc VA: 0x75954ad6dc
	private Void _RenderRankInfo() { }
	// RVA: 0x2e95b6c VA: 0x75954adb6c
	private Void _RenderCharInfo() { }
	// RVA: 0x2e95464 VA: 0x75954ad464
	private Void _InitIfNot() { }
	// RVA: 0x2e959b8 VA: 0x75954ad9b8
	private Void _ResetAnim() { }
	// RVA: 0x2e95be8 VA: 0x75954adbe8
	private Void _TimerTickCallBack() { }
	// RVA: 0x2e95cd0 VA: 0x75954adcd0
	private Void _StartTimer() { }
	// RVA: 0x2e95e10 VA: 0x75954ade10
	private Void _ClearTimer() { }
	// RVA: 0x2e953e4 VA: 0x75954ad3e4
	public Void EventOnViewClicked() { }
	// RVA: 0x2e95eb8 VA: 0x75954adeb8
	private Void OnDestroy() { }
	// RVA: 0x2e95f20 VA: 0x75954adf20
	public Void .ctor() { }
	// RVA: 0x2e96040 VA: 0x75954ae040
	private IEnumerator <>xLuaBaseProxy_ShowEnterEffectCoroutine() { }
}
```