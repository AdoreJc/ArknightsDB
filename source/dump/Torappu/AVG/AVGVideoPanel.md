# AVGVideoPanel

**Namespace:** `Torappu.AVG`


## Fields

- `Transform _mediaPlayerContainer`

- `Ease _hideEase`

- `Coroutine m_startPlayCoroutine`

- `Coroutine m_stopPlayCoroutine`

- `Tween m_disposeVideoTween`

- `CanvasGroup m_canvasGroup`

- `Boolean m_hidden`

- `AbstractMediaPlayerHolder m_mediaPlayer`

- `Boolean m_isSettingInited`


## Methods

- `Void Awake()`

- `AbstractResRefCollecter DontInvoke_PlzImplInternalResRefCollector()`

- `Boolean _PlayVideo(Command, out)`

- `Boolean _ExecuteVideo(Command)`

- `Void _HandlePlayEvent(Status)`

- `Void _SetHiddenInternal(Boolean, Boolean)`

- `Void _DisposeVideo(Single, Action)`

- `IEnumerator _StopCoro(Action)`

- `IEnumerator _StartPlayCoroutine()`

- `Void _InitSettingsIfNot()`

- `Void _OnSettingChange(SettingType)`

- `Void _ApplyMusicSettings()`

- `Void <_DisposeVideo>b__20_0()`

- `Void <>xLuaBaseProxy_OnReset()`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGVideoPanel : ExecutorComponent
{
	private const Single FADE_DURATION; // 0x0
	private Transform _mediaPlayerContainer; // 0x50
	private Ease _hideEase; // 0x58
	private Coroutine m_startPlayCoroutine; // 0x60
	private Coroutine m_stopPlayCoroutine; // 0x68
	private Tween m_disposeVideoTween; // 0x70
	private CanvasGroup m_canvasGroup; // 0x78
	private Boolean m_hidden; // 0x80
	private AbstractMediaPlayerHolder m_mediaPlayer; // 0x88
	private Boolean m_isSettingInited; // 0x90
	private static DelegateBridge __Hotfix0_Awake; // 0x0
	private static DelegateBridge __Hotfix0_OnReset; // 0x8
	private static DelegateBridge __Hotfix0_GetExecutors; // 0x10
	private static DelegateBridge __Hotfix0_DontInvoke_PlzImplInternalResRefCollector; // 0x18
	private static DelegateBridge __Hotfix0_ForceCommandEnd; // 0x20
	private static DelegateBridge __Hotfix0__PlayVideo; // 0x28
	private static DelegateBridge __Hotfix0__ExecuteVideo; // 0x30
	private static DelegateBridge __Hotfix0__HandlePlayEvent; // 0x38
	private static DelegateBridge __Hotfix0_OnFinish; // 0x40
	private static DelegateBridge __Hotfix0__SetHiddenInternal; // 0x48
	private static DelegateBridge __Hotfix0__DisposeVideo; // 0x50
	private static DelegateBridge __Hotfix0__StopCoro; // 0x58
	private static DelegateBridge __Hotfix0__StartPlayCoroutine; // 0x60
	private static DelegateBridge __Hotfix0__InitSettingsIfNot; // 0x68
	private static DelegateBridge __Hotfix0__OnSettingChange; // 0x70
	private static DelegateBridge __Hotfix0__ApplyMusicSettings; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80


	// RVA: 0x3e79874 VA: 0x7596491874
	private Void Awake() { }
	// RVA: 0x3e7992c VA: 0x759649192c
	public override Void OnReset() { }
	// RVA: 0x3e79c84 VA: 0x7596491c84
	public override Dictionary`2 GetExecutors() { }
	// RVA: 0x3e79dc0 VA: 0x7596491dc0
	public AbstractResRefCollecter DontInvoke_PlzImplInternalResRefCollector() { }
	// RVA: 0x3e79e54 VA: 0x7596491e54
	protected override Void ForceCommandEnd() { }
	// RVA: 0x3e7a324 VA: 0x7596492324
	private Boolean _PlayVideo(Command command, out String url) { }
	// RVA: 0x3e7a51c VA: 0x759649251c
	private Boolean _ExecuteVideo(Command command) { }
	// RVA: 0x3e7a7d0 VA: 0x75964927d0
	private Void _HandlePlayEvent(Status status) { }
	// RVA: 0x3e7a990 VA: 0x7596492990
	protected override Void OnFinish() { }
	// RVA: 0x3e7a184 VA: 0x7596492184
	private Void _SetHiddenInternal(Boolean value, Boolean force) { }
	// RVA: 0x3e79ed8 VA: 0x7596491ed8
	private Void _DisposeVideo(Single closeDelay, Action callback) { }
	// RVA: 0x3e7aa14 VA: 0x7596492a14
	private IEnumerator _StopCoro(Action callback) { }
	// RVA: 0x3e7a724 VA: 0x7596492724
	private IEnumerator _StartPlayCoroutine() { }
	// RVA: 0x3e79a90 VA: 0x7596491a90
	private Void _InitSettingsIfNot() { }
	// RVA: 0x3e7abd8 VA: 0x7596492bd8
	private Void _OnSettingChange(SettingType type) { }
	// RVA: 0x3e7ab34 VA: 0x7596492b34
	private Void _ApplyMusicSettings() { }
	// RVA: 0x3e7ac74 VA: 0x7596492c74
	public Void .ctor() { }
	// RVA: 0x3e7acec VA: 0x7596492cec
	private Void <_DisposeVideo>b__20_0() { }
	// RVA: 0x3e7ad20 VA: 0x7596492d20
	private Void <>xLuaBaseProxy_OnReset() { }
	// RVA: 0x3e7ad28 VA: 0x7596492d28
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```