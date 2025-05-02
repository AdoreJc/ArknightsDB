# AudioChannel

**Namespace:** `Torappu.Audio`


## Fields

- `AudioPlayback m_playback`

- `AudioEngine m_engine`

- `Single m_currentBaseVolume`

- `Single m_tweenStartVolume`

- `Single m_tweenTargetVolume`

- `Single m_tweenStartTime`

- `Single m_tweenEndTime`

- `Boolean m_stopWhenTweenEnd`

- `EasingFunction m_easingFunction`

- `Object m_userData`

- `Action onChannelRecycled`

- `AudioVolumeTweenBlender m_volumeTweenBlender`

- `Single m_cacheVolumeBlenderValue`

- `IAudioInfo audioInfo`

- `AudioAsset loadedAsset`


## Properties

- `Single volume`

- `String name`

- `Single pitch`

- `Vector3 position`

- `Boolean isPlaying`

- `Single length`


## Methods

- `Single get_volume()`

- `Void set_volume(Single)`

- `String get_name()`

- `Void set_name(String)`

- `Single get_pitch()`

- `Void set_pitch(Single)`

- `Vector3 get_position()`

- `Void set_position(Vector3)`

- `Boolean get_isPlaying()`

- `Single get_length()`

- `String LogAudioMixer()`

- `Single GetCurrentTimePercent()`

- `ChannelPlayStatus GetChannelPlayStatus()`

- `Object GetUserData()`

- `Void TweenVolume(Single, Single, Single, EaseType)`

- `Void StopTweenVolume()`

- `Void Stop(Single, EaseType)`

- `Void _UpdateVolumes()`

- `Void Init(Transform, AudioEngine)`

- `Void OnAllocate()`

- `Void OnRecycle()`

- `Void Update()`

- `Boolean _GetVolumeBlenderValue()`

- `Void PlayAudio(TAudioParam, AudioAsset, Single, Object)`

- `Void PlayMusicWithSyncStatus(MusicParam, AudioAsset, ChannelPlayStatus, Object)`

- `Void _Stop()`

- `Void _ResetBlenders()`

- `Void PopulateAudioEffect(AudioChannelEffect)`

- `Void ClearAllEffect()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Audio
public class AudioChannel : IReusable, IHotfixable
{
	private AudioPlayback m_playback; // 0x10
	private AudioEngine m_engine; // 0x18
	private Single m_currentBaseVolume; // 0x20
	private Single m_tweenStartVolume; // 0x24
	private Single m_tweenTargetVolume; // 0x28
	private Single m_tweenStartTime; // 0x2c
	private Single m_tweenEndTime; // 0x30
	private Boolean m_stopWhenTweenEnd; // 0x34
	private EasingFunction m_easingFunction; // 0x38
	private Object m_userData; // 0x40
	public Action onChannelRecycled; // 0x48
	private AudioVolumeTweenBlender m_volumeTweenBlender; // 0x50
	private Single m_cacheVolumeBlenderValue; // 0x58
	public IAudioInfo audioInfo; // 0x60
	public AudioAsset loadedAsset; // 0x68
	private static DelegateBridge __Hotfix0_get_volume; // 0x0
	private static DelegateBridge __Hotfix0_set_volume; // 0x8
	private static DelegateBridge __Hotfix0_get_name; // 0x10
	private static DelegateBridge __Hotfix0_set_name; // 0x18
	private static DelegateBridge __Hotfix0_get_pitch; // 0x20
	private static DelegateBridge __Hotfix0_set_pitch; // 0x28
	private static DelegateBridge __Hotfix0_get_position; // 0x30
	private static DelegateBridge __Hotfix0_set_position; // 0x38
	private static DelegateBridge __Hotfix0_get_isPlaying; // 0x40
	private static DelegateBridge __Hotfix0_get_length; // 0x48
	private static DelegateBridge __Hotfix0_LogAudioMixer; // 0x50
	private static DelegateBridge __Hotfix0_GetCurrentTimePercent; // 0x58
	private static DelegateBridge __Hotfix0_GetChannelPlayStatus; // 0x60
	private static DelegateBridge __Hotfix0_GetUserData; // 0x68
	private static DelegateBridge __Hotfix0_TweenVolume; // 0x70
	private static DelegateBridge __Hotfix0_StopTweenVolume; // 0x78
	private static DelegateBridge __Hotfix0_Stop; // 0x80
	private static DelegateBridge __Hotfix0__UpdateVolumes; // 0x88
	private static DelegateBridge __Hotfix0_Init; // 0x90
	private static DelegateBridge __Hotfix0_OnAllocate; // 0x98
	private static DelegateBridge __Hotfix0_OnRecycle; // 0xa0
	private static DelegateBridge __Hotfix0_Update; // 0xa8
	private static DelegateBridge __Hotfix0__GetVolumeBlenderValue; // 0xb0
	private static DelegateBridge __Hotfix0_PlayAudio; // 0xb8
	private static DelegateBridge __Hotfix0_PlayMusicWithSyncStatus; // 0xc0
	private static DelegateBridge __Hotfix0__Stop; // 0xc8
	private static DelegateBridge __Hotfix0__ResetBlenders; // 0xd0
	private static DelegateBridge __Hotfix0_PopulateAudioEffect; // 0xd8
	private static DelegateBridge __Hotfix0_ClearAllEffect; // 0xe0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xe8

	public Single volume { get; set; }
	public String name { get; set; }
	public Single pitch { get; set; }
	public Vector3 position { get; set; }
	public Boolean isPlaying { get; }
	public Single length { get; }

	// RVA: 0x3eb322c VA: 0x75964cb22c
	public Single get_volume() { }
	// RVA: 0x3eb3294 VA: 0x75964cb294
	public Void set_volume(Single value) { }
	// RVA: 0x3eb3410 VA: 0x75964cb410
	public String get_name() { }
	// RVA: 0x3eb3488 VA: 0x75964cb488
	public Void set_name(String value) { }
	// RVA: 0x3eb3518 VA: 0x75964cb518
	public Single get_pitch() { }
	// RVA: 0x3eb3590 VA: 0x75964cb590
	public Void set_pitch(Single value) { }
	// RVA: 0x3eb3620 VA: 0x75964cb620
	public Vector3 get_position() { }
	// RVA: 0x3eb3698 VA: 0x75964cb698
	public Void set_position(Vector3 value) { }
	// RVA: 0x3eb374c VA: 0x75964cb74c
	public Boolean get_isPlaying() { }
	// RVA: 0x3eb37d0 VA: 0x75964cb7d0
	public Single get_length() { }
	// RVA: 0x3eb3854 VA: 0x75964cb854
	public String LogAudioMixer() { }
	// RVA: 0x3eb38f8 VA: 0x75964cb8f8
	public Single GetCurrentTimePercent() { }
	// RVA: 0x3eb39d0 VA: 0x75964cb9d0
	public ChannelPlayStatus GetChannelPlayStatus() { }
	// RVA: 0x3eb3ab0 VA: 0x75964cbab0
	public Object GetUserData() { }
	// RVA: 0x3eb3b18 VA: 0x75964cbb18
	public Void TweenVolume(Single targetVolume, Single duration, Single delay, EaseType easeType) { }
	// RVA: 0x3eb331c VA: 0x75964cb31c
	public Void StopTweenVolume() { }
	// RVA: 0x3eb3c08 VA: 0x75964cbc08
	public Void Stop(Single duration, EaseType easeType) { }
	// RVA: 0x3eb3388 VA: 0x75964cb388
	private Void _UpdateVolumes() { }
	// RVA: 0x3eb3d5c VA: 0x75964cbd5c
	public Void Init(Transform parent, AudioEngine engine) { }
	// RVA: 0x3eb4108 VA: 0x75964cc108
	public Void OnAllocate() { }
	// RVA: 0x3eb3f80 VA: 0x75964cbf80
	public Void OnRecycle() { }
	// RVA: 0x3eb420c VA: 0x75964cc20c
	public Void Update() { }
	// RVA: 0x3eb467c VA: 0x75964cc67c
	private Boolean _GetVolumeBlenderValue() { }
	// RVA: 0x VA: 0x0
	public Void PlayAudio(TAudioParam param, AudioAsset asset, Single delay, Object userData) { }
	// RVA: 0x3eb48fc VA: 0x75964cc8fc
	public Void PlayMusicWithSyncStatus(MusicParam param, AudioAsset asset, ChannelPlayStatus channelPlayStatus, Object userData) { }
	// RVA: 0x3eb3ce0 VA: 0x75964cbce0
	private Void _Stop() { }
	// RVA: 0x3eb4190 VA: 0x75964cc190
	public Void _ResetBlenders() { }
	// RVA: 0x3eb4b94 VA: 0x75964ccb94
	public Void PopulateAudioEffect(AudioChannelEffect channelEffect) { }
	// RVA: 0x3eb4e38 VA: 0x75964cce38
	public Void ClearAllEffect() { }
	// RVA: 0x3eb4ea8 VA: 0x75964ccea8
	public Void .ctor() { }
}
```