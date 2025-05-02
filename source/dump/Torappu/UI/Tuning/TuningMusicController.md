# TuningMusicController

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `UIMusicDuckingHelper m_musicDuckingHelper`

- `AudioMusicGroupHandler m_mainMusicGroupHandler`

- `AudioMusicGroupHandler m_subMusicGroupHandler`

- `TuningCachedMusicParam m_cachedMusicParam`


## Methods

- `Void PlayMusic(TuningPlayMusicOption)`

- `Void StopMusic()`

- `Void _PlayMainMusicWithDucking(String, Boolean, String)`

- `Void _PlaySubMusic(String)`

- `Void _StopMainMusic()`

- `Void _StopSubMusic()`

- `Void _StopMusicWithoutClearCache()`

- `Void _PlayCachedMusic()`

- `Void <>xLuaBaseProxy_OnDestroy()`

- `Void <>xLuaBaseProxy_OnStop()`

- `Void <>xLuaBaseProxy_OnStart()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningMusicController : PageSingleComponent
{
	private UIMusicDuckingHelper m_musicDuckingHelper; // 0x20
	private AudioMusicGroupHandler m_mainMusicGroupHandler; // 0x28
	private AudioMusicGroupHandler m_subMusicGroupHandler; // 0x30
	private TuningCachedMusicParam m_cachedMusicParam; // 0x38
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x0
	private static DelegateBridge __Hotfix0_OnStop; // 0x8
	private static DelegateBridge __Hotfix0_OnStart; // 0x10
	private static DelegateBridge __Hotfix0_PlayMusic; // 0x18
	private static DelegateBridge __Hotfix0_StopMusic; // 0x20
	private static DelegateBridge __Hotfix0__PlayMainMusicWithDucking; // 0x28
	private static DelegateBridge __Hotfix0__PlaySubMusic; // 0x30
	private static DelegateBridge __Hotfix0__StopMainMusic; // 0x38
	private static DelegateBridge __Hotfix0__StopSubMusic; // 0x40
	private static DelegateBridge __Hotfix0__StopMusicWithoutClearCache; // 0x48
	private static DelegateBridge __Hotfix0__PlayCachedMusic; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58


	// RVA: 0x232ded4 VA: 0x7594945ed4
	protected override Void OnDestroy() { }
	// RVA: 0x232e01c VA: 0x759494601c
	protected override Void OnStop() { }
	// RVA: 0x232e11c VA: 0x759494611c
	protected override Void OnStart() { }
	// RVA: 0x232e250 VA: 0x7594946250
	public Void PlayMusic(TuningPlayMusicOption playOption) { }
	// RVA: 0x232df74 VA: 0x7594945f74
	public Void StopMusic() { }
	// RVA: 0x232e4d0 VA: 0x75949464d0
	private Void _PlayMainMusicWithDucking(String musicId, Boolean needInterrupt, String prevMusicId) { }
	// RVA: 0x232e6f8 VA: 0x75949466f8
	private Void _PlaySubMusic(String musicId) { }
	// RVA: 0x232e848 VA: 0x7594946848
	private Void _StopMainMusic() { }
	// RVA: 0x232e67c VA: 0x759494667c
	private Void _StopSubMusic() { }
	// RVA: 0x232e090 VA: 0x7594946090
	private Void _StopMusicWithoutClearCache() { }
	// RVA: 0x232e190 VA: 0x7594946190
	private Void _PlayCachedMusic() { }
	// RVA: 0x232e8c4 VA: 0x75949468c4
	public Void .ctor() { }
	// RVA: 0x232e974 VA: 0x7594946974
	private Void <>xLuaBaseProxy_OnDestroy() { }
	// RVA: 0x232e97c VA: 0x759494697c
	private Void <>xLuaBaseProxy_OnStop() { }
	// RVA: 0x232e984 VA: 0x7594946984
	private Void <>xLuaBaseProxy_OnStart() { }
}
```