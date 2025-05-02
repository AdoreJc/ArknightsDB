# CommonExecutors

**Namespace:** `Torappu.AVG`


## Fields

- `Single _clickAutoDelay`

- `Single _soundDefaultFadeTime`

- `Action m_onStoryEnd`

- `Coroutine m_delayCoroutine`

- `EventCallbackDelegate m_onClickCallback`

- `Action m_gotoFinishCb`

- `String m_gotoWaitForSignal`

- `Action m_gotoCharInfoFinishCb`

- `String m_gotoCharInfoWaitForSignal`


## Methods

- `Single CalculateFadetime(Single)`

- `Boolean NeedSkipAnimation(Single)`

- `String _GenAVGSoundChannelName(String)`

- `Void _ExecuteDelayCommand(Command, Action)`

- `Void _ForceEndDelayCommand()`

- `Void _ExecuteClickCommand(Command, Action)`

- `Void _ForceEndClickCommand()`

- `Void _ResetAudio()`

- `Void _ExecutePlaySoundCommand(Command, Action)`

- `Void _ExecuteStopSoundCommand(Command, Action)`

- `Void _ExecuteSoundVolumeCommand(Command, Action)`

- `Void _ExecutePlayMusicCommand(Command, Action)`

- `Void _ExecuteStopMusicCommand(Command, Action)`

- `Void _ExecuteMusicVolumeCommand(Command, Action)`

- `Void _ExecuteConsumeGuideOnStoryEndCommand(Command, Action)`

- `Void _ExecuteGotoPageCommand(Command, Action)`

- `Boolean _RouteToTarget(UIRouteTarget, Command)`

- `Void _SignalGotoPageReceiver(Command)`

- `Void _ExecuteStartBattleCommand(Command, Action)`

- `Void _InvokeStartBattle(String, Boolean, Action, Action)`

- `Boolean _TryGetRouteTargetFromGotoDest(AVGGotoPageDest, out)`

- `Void _ExecuteGotoCharInfoCommand(Command, Action)`

- `Void _SignalGotoCharInfoReceiver(Command)`

- `Void <>xLuaBaseProxy_OnReset()`

- `Void <>xLuaBaseProxy_OnStoryEnd(Story)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class CommonExecutors : AVGComponent, IHotfixable, IFadeTimeRatio, IContainsResRefs
{
	private Single _clickAutoDelay; // 0x28
	private Single _soundDefaultFadeTime; // 0x2c
	private const String AVG_SOUND_CHANNEL_FORMAT; // 0x0
	private Action m_onStoryEnd; // 0x30
	private HashSet`1 m_allSoundChannels; // 0x38
	private Coroutine m_delayCoroutine; // 0x40
	private EventCallbackDelegate m_onClickCallback; // 0x48
	private Action m_gotoFinishCb; // 0x50
	private String m_gotoWaitForSignal; // 0x58
	private Action m_gotoCharInfoFinishCb; // 0x60
	private String m_gotoCharInfoWaitForSignal; // 0x68
	private static DelegateBridge __Hotfix0_GetCommandExecutors; // 0x0
	private static DelegateBridge __Hotfix0_OnReset; // 0x8
	private static DelegateBridge __Hotfix0_OnStoryEnd; // 0x10
	private static DelegateBridge __Hotfix0_CalculateFadetime; // 0x18
	private static DelegateBridge __Hotfix0_NeedSkipAnimation; // 0x20
	private static DelegateBridge __Hotfix0__GenAVGSoundChannelName; // 0x28
	private static DelegateBridge __Hotfix0__ExecuteDelayCommand; // 0x30
	private static DelegateBridge __Hotfix0__ForceEndDelayCommand; // 0x38
	private static DelegateBridge __Hotfix0__ExecuteClickCommand; // 0x40
	private static DelegateBridge __Hotfix0__ForceEndClickCommand; // 0x48
	private static DelegateBridge __Hotfix0__ResetAudio; // 0x50
	private static DelegateBridge __Hotfix0__ExecutePlaySoundCommand; // 0x58
	private static DelegateBridge __Hotfix0__ExecuteStopSoundCommand; // 0x60
	private static DelegateBridge __Hotfix0__ExecuteSoundVolumeCommand; // 0x68
	private static DelegateBridge __Hotfix0__ExecutePlayMusicCommand; // 0x70
	private static DelegateBridge __Hotfix0__ExecuteStopMusicCommand; // 0x78
	private static DelegateBridge __Hotfix0__ExecuteMusicVolumeCommand; // 0x80
	private static DelegateBridge __Hotfix0__ExecuteConsumeGuideOnStoryEndCommand; // 0x88
	private static DelegateBridge __Hotfix0__ExtractStrFromCommand; // 0x90
	private static DelegateBridge __Hotfix0__ExecuteGotoPageCommand; // 0x98
	private static DelegateBridge __Hotfix0__RouteToTarget; // 0xa0
	private static DelegateBridge __Hotfix0__SignalGotoPageReceiver; // 0xa8
	private static DelegateBridge __Hotfix0__ExecuteStartBattleCommand; // 0xb0
	private static DelegateBridge __Hotfix0__InvokeStartBattle; // 0xb8
	private static DelegateBridge __Hotfix0__TryGetRouteTargetFromGotoDest; // 0xc0
	private static DelegateBridge __Hotfix0__ExecuteGotoCharInfoCommand; // 0xc8
	private static DelegateBridge __Hotfix0__PageStackParamToCharInfo; // 0xd0
	private static DelegateBridge __Hotfix0__SignalGotoCharInfoReceiver; // 0xd8
	private static DelegateBridge __Hotfix0_DontInvoke_PlzImplInternalResRefCollector; // 0xe0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xe8


	// RVA: 0x3e7eb38 VA: 0x7596496b38
	public override IList`1 GetCommandExecutors() { }
	// RVA: 0x3e7f4a0 VA: 0x75964974a0
	public override Void OnReset() { }
	// RVA: 0x3e7f6c8 VA: 0x75964976c8
	public override Void OnStoryEnd(Story story) { }
	// RVA: 0x3e7f784 VA: 0x7596497784
	public Single CalculateFadetime(Single initialFadetime) { }
	// RVA: 0x3e7f82c VA: 0x759649782c
	public Boolean NeedSkipAnimation(Single fadetime) { }
	// RVA: 0x3e7f8d0 VA: 0x75964978d0
	private String _GenAVGSoundChannelName(String rawChannel) { }
	// RVA: 0x3e7f968 VA: 0x7596497968
	private Void _ExecuteDelayCommand(Command command, Action finishCb) { }
	// RVA: 0x3e7fab8 VA: 0x7596497ab8
	private Void _ForceEndDelayCommand() { }
	// RVA: 0x3e7fb4c VA: 0x7596497b4c
	private Void _ExecuteClickCommand(Command command, Action finishCb) { }
	// RVA: 0x3e7fcd8 VA: 0x7596497cd8
	private Void _ForceEndClickCommand() { }
	// RVA: 0x3e7f524 VA: 0x7596497524
	private Void _ResetAudio() { }
	// RVA: 0x3e7fdc0 VA: 0x7596497dc0
	private Void _ExecutePlaySoundCommand(Command command, Action finishCb) { }
	// RVA: 0x3e800d4 VA: 0x75964980d4
	private Void _ExecuteStopSoundCommand(Command command, Action finishCb) { }
	// RVA: 0x3e802e4 VA: 0x75964982e4
	private Void _ExecuteSoundVolumeCommand(Command command, Action finishCb) { }
	// RVA: 0x3e80440 VA: 0x7596498440
	private Void _ExecutePlayMusicCommand(Command command, Action finishCb) { }
	// RVA: 0x3e80724 VA: 0x7596498724
	private Void _ExecuteStopMusicCommand(Command command, Action finishCb) { }
	// RVA: 0x3e807ec VA: 0x75964987ec
	private Void _ExecuteMusicVolumeCommand(Command command, Action finishCb) { }
	// RVA: 0x3e8090c VA: 0x759649890c
	private Void _ExecuteConsumeGuideOnStoryEndCommand(Command command, Action finishCb) { }
	// RVA: 0x3e80b24 VA: 0x7596498b24
	private static String _ExtractStrFromCommand(Command command, String paramName) { }
	// RVA: 0x3e80bfc VA: 0x7596498bfc
	private Void _ExecuteGotoPageCommand(Command command, Action finishCb) { }
	// RVA: 0x3e80f7c VA: 0x7596498f7c
	private Boolean _RouteToTarget(UIRouteTarget routeTarget, Command command) { }
	// RVA: 0x3e81190 VA: 0x7596499190
	private Void _SignalGotoPageReceiver(Command command) { }
	// RVA: 0x3e812a4 VA: 0x75964992a4
	private Void _ExecuteStartBattleCommand(Command command, Action finishCb) { }
	// RVA: 0x3e813d4 VA: 0x75964993d4
	private Void _InvokeStartBattle(String stageId, Boolean isPractice, Action onProceed, Action onBlock) { }
	// RVA: 0x3e80e54 VA: 0x7596498e54
	private Boolean _TryGetRouteTargetFromGotoDest(AVGGotoPageDest destPage, out UIRouteTarget target) { }
	// RVA: 0x3e815bc VA: 0x75964995bc
	private Void _ExecuteGotoCharInfoCommand(Command command, Action finishCb) { }
	// RVA: 0x3e8182c VA: 0x759649982c
	private static UIPageStackParam _PageStackParamToCharInfo(Object charArgs) { }
	// RVA: 0x3e81b9c VA: 0x7596499b9c
	private Void _SignalGotoCharInfoReceiver(Command command) { }
	// RVA: 0x3e81cb0 VA: 0x7596499cb0
	public virtual AbstractResRefCollecter DontInvoke_PlzImplInternalResRefCollector() { }
	// RVA: 0x3e81d44 VA: 0x7596499d44
	public Void .ctor() { }
	// RVA: 0x3e81e14 VA: 0x7596499e14
	private Void <>xLuaBaseProxy_OnReset() { }
	// RVA: 0x3e81e1c VA: 0x7596499e1c
	private Void <>xLuaBaseProxy_OnStoryEnd(Story P0) { }
}
```