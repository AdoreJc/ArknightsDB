# CriManaMixerBehaviour

**Namespace:** `CriWare.CriTimeline.Mana`


## Fields

- `Double lastPlayedTime`

- `Double m_currentSeekingFrameTime`

- `Single m_originalAudioVolume`

- `Single m_originalSubAudioVolume`

- `Single m_originalExtraAudioVolume`

- `Boolean enableTimelineScrubPlayback`

- `Double m_lastDirectorTime`

- `MovieMixerState m_movieMixerState`


## Methods

- `Void KeepAudioVolume(Boolean)`

- `Boolean PlayMovie(CriManaClipBase, Int32, Double)`

- `Boolean PrepareMovie(CriManaClipBase)`

- `Boolean StopMovie(Boolean)`

- `Boolean StopForSeekMovie()`

- `Void ProcessFrameOnSeeking(TimelineClip, CriManaClipBase, Double)`

- `Void ForceSyncedStop(Boolean)`

- `Boolean IsIntermediateState()`

- `Void PausePlayer(Boolean)`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare.CriTimeline.Mana
public class CriManaMixerBehaviour : PlayableBehaviour
{
	internal PlayableDirector m_PlayableDirector; // 0x10
	internal TimelineClip[] m_clips; // 0x18
	internal CriManaMovieMaterialBase m_boundMovieMaterial; // 0x20
	internal Dictionary`2 m_gcHandleList; // 0x28
	internal Boolean m_frameSync; // 0x30
	internal Boolean m_CheckPosWithinClip; // 0x31
	private static Double cPreloadTimeSec; // 0x0
	private static Single cFrameSkipTolerance; // 0x8
	private Nullable`1 m_lastClipId; // 0x34
	private Double lastPlayedTime; // 0x48
	private Double m_currentSeekingFrameTime; // 0x50
	private Single m_originalAudioVolume; // 0x58
	private Single m_originalSubAudioVolume; // 0x5c
	private Single m_originalExtraAudioVolume; // 0x60
	private Boolean enableTimelineScrubPlayback; // 0x64
	private Double m_lastDirectorTime; // 0x68
	private MovieMixerState m_movieMixerState; // 0x70

	private static Boolean IsEditMode { get; }

	// RVA: 0x414ec00 VA: 0x7596766c00
	private static Boolean get_IsEditMode() { }
	// RVA: 0x414ec08 VA: 0x7596766c08
	private Void KeepAudioVolume(Boolean fadeAudio) { }
	// RVA: 0x414eca4 VA: 0x7596766ca4
	private Boolean PlayMovie(CriManaClipBase clipAsset, Int32 startFrame, Double startTime) { }
	// RVA: 0x414f218 VA: 0x7596767218
	private Boolean PrepareMovie(CriManaClipBase clipAsset) { }
	// RVA: 0x414f4c0 VA: 0x75967674c0
	private Boolean StopMovie(Boolean keepLastFrame) { }
	// RVA: 0x414f75c VA: 0x759676775c
	private Boolean StopForSeekMovie() { }
	// RVA: 0x414f7e8 VA: 0x75967677e8
	private static Boolean IsPlayerPreparing(Player player) { }
	// RVA: 0x414f814 VA: 0x7596767814
	private static Boolean IsPlayerStopped(Player player) { }
	// RVA: 0x414f834 VA: 0x7596767834
	private static Boolean IsPlayerError(Player player) { }
	// RVA: 0x414f854 VA: 0x7596767854
	private static Boolean IsPlayerReadyOrPlaying(Player player) { }
	// RVA: 0x414f8a0 VA: 0x75967678a0
	private Void ProcessFrameOnSeeking(TimelineClip activeClip, CriManaClipBase clip, Double frameTime) { }
	// RVA: 0x414f9a0 VA: 0x75967679a0
	private Void ForceSyncedStop(Boolean keepLastFrame) { }
	// RVA: 0x414fa4c VA: 0x7596767a4c
	public override Void ProcessFrame(Playable playable, FrameData info, Object playerData) { }
	// RVA: 0x4150588 VA: 0x7596768588
	private Boolean IsIntermediateState() { }
	// RVA: 0x415062c VA: 0x759676862c
	public override Void OnBehaviourPlay(Playable playable, FrameData info) { }
	// RVA: 0x415065c VA: 0x759676865c
	public override Void OnBehaviourPause(Playable playable, FrameData info) { }
	// RVA: 0x4150414 VA: 0x7596768414
	private Void PausePlayer(Boolean pause) { }
	// RVA: 0x4150700 VA: 0x7596768700
	public override Void OnGraphStart(Playable playable) { }
	// RVA: 0x4150970 VA: 0x7596768970
	public override Void OnGraphStop(Playable playable) { }
	// RVA: 0x4150b24 VA: 0x7596768b24
	public override Void OnPlayableCreate(Playable playable) { }
	// RVA: 0x4150bf8 VA: 0x7596768bf8
	public override Void OnPlayableDestroy(Playable playable) { }
	// RVA: 0x4150c74 VA: 0x7596768c74
	public Void .ctor() { }
	// RVA: 0x4150c9c VA: 0x7596768c9c
	private static Void .cctor() { }
}
```