# UnityAudioPlayback

**Namespace:** `Torappu.Audio.Engine.Unity`


## Fields

- `Double m_realStartDspTime`

- `Int32 loadedClipCount`

- `GameObject m_gameObject`

- `MixerDesc m_descCache`

- `UnityAudioSchedule m_audioSchedule`


## Properties

- `UnityAudioSchedule audioSchedule`


## Methods

- `UnityAudioSchedule get_audioSchedule()`

- `Boolean _FindActiveSourceIndex(out, out)`

- `Void _PrepareAudioSources(Int32)`

- `Void _PlayAudioImpl(Int32, Boolean, Single)`

- `Void _PlayAudioWithTargetStats(Int32, Boolean, ChannelPlayStatus)`

- `Void _UpdateSoundProperties(ISoundInfo)`

- `Void _UpdateMusicProperties(IMusicInfo)`

- `Void _UpdateAudioSourceStatus(Single, AudioMixerGroup)`

- `ChannelAudioSource _CreateAudioSource()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Audio.Engine.Unity
public class UnityAudioPlayback : AudioPlayback
{
	private Double m_realStartDspTime; // 0x18
	public Int32 loadedClipCount; // 0x20
	private GameObject m_gameObject; // 0x28
	private ChannelAudioSource[] m_audioSources; // 0x30
	private AudioClip[] m_clips; // 0x38
	private String[] m_clipKeys; // 0x40
	private MixerDesc m_descCache; // 0x48
	private UnityAudioSchedule m_audioSchedule; // 0x60
	private static DelegateBridge __Hotfix0_get_audioSchedule; // 0x0
	private static DelegateBridge __Hotfix0_get_name; // 0x8
	private static DelegateBridge __Hotfix0_set_name; // 0x10
	private static DelegateBridge __Hotfix0_get_pitch; // 0x18
	private static DelegateBridge __Hotfix0_set_pitch; // 0x20
	private static DelegateBridge __Hotfix0_get_position; // 0x28
	private static DelegateBridge __Hotfix0_set_position; // 0x30
	private static DelegateBridge __Hotfix0_get_currentTime; // 0x38
	private static DelegateBridge __Hotfix0_get_length; // 0x40
	private static DelegateBridge __Hotfix0_OnInit; // 0x48
	private static DelegateBridge __Hotfix0_OnReuse; // 0x50
	private static DelegateBridge __Hotfix0_OnRecycle; // 0x58
	private static DelegateBridge __Hotfix0_IsPlaying; // 0x60
	private static DelegateBridge __Hotfix0_PlaySound; // 0x68
	private static DelegateBridge __Hotfix0_PlayMusic; // 0x70
	private static DelegateBridge __Hotfix0_PlayMusicSyncStatus; // 0x78
	private static DelegateBridge __Hotfix0_SetVolume; // 0x80
	private static DelegateBridge __Hotfix0_Stop; // 0x88
	private static DelegateBridge __Hotfix0_GetChannelPlayStatus; // 0x90
	private static DelegateBridge __Hotfix0_LogAudioMixer; // 0x98
	private static DelegateBridge __Hotfix0__FindActiveSourceIndex; // 0xa0
	private static DelegateBridge __Hotfix0__PrepareClipInput; // 0xa8
	private static DelegateBridge __Hotfix0__PrepareAudioSources; // 0xb0
	private static DelegateBridge __Hotfix0__PlayAudioImpl; // 0xb8
	private static DelegateBridge __Hotfix0__PlayAudioWithTargetStats; // 0xc0
	private static DelegateBridge __Hotfix0__UpdateSoundProperties; // 0xc8
	private static DelegateBridge __Hotfix0__UpdateMusicProperties; // 0xd0
	private static DelegateBridge __Hotfix0__UpdateAudioSourceStatus; // 0xd8
	private static DelegateBridge __Hotfix0__CreateAudioSource; // 0xe0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xe8

	private UnityAudioSchedule audioSchedule { get; }
	public override String name { get; set; }
	public override Single pitch { get; set; }
	public override Vector3 position { get; set; }
	public override Single currentTime { get; }
	public override Single length { get; }

	// RVA: 0x3ee66b8 VA: 0x75964fe6b8
	private UnityAudioSchedule get_audioSchedule() { }
	// RVA: 0x3ee67d4 VA: 0x75964fe7d4
	public override String get_name() { }
	// RVA: 0x3ee6848 VA: 0x75964fe848
	public override Void set_name(String value) { }
	// RVA: 0x3ee68d4 VA: 0x75964fe8d4
	public override Single get_pitch() { }
	// RVA: 0x3ee6980 VA: 0x75964fe980
	public override Void set_pitch(Single value) { }
	// RVA: 0x3ee6a58 VA: 0x75964fea58
	public override Vector3 get_position() { }
	// RVA: 0x3ee6ad8 VA: 0x75964fead8
	public override Void set_position(Vector3 value) { }
	// RVA: 0x3ee6bb4 VA: 0x75964febb4
	public override Single get_currentTime() { }
	// RVA: 0x3ee6f00 VA: 0x75964fef00
	public override Single get_length() { }
	// RVA: 0x3ee706c VA: 0x75964ff06c
	protected override Void OnInit(Transform parent) { }
	// RVA: 0x3ee724c VA: 0x75964ff24c
	public override Void OnReuse() { }
	// RVA: 0x3ee72c4 VA: 0x75964ff2c4
	public override Void OnRecycle() { }
	// RVA: 0x3ee7564 VA: 0x75964ff564
	public override Boolean IsPlaying() { }
	// RVA: 0x3ee76b0 VA: 0x75964ff6b0
	public override Void PlaySound(ISoundInfo sound, PlayOptions options) { }
	// RVA: 0x3ee7d78 VA: 0x75964ffd78
	public override Void PlayMusic(IMusicInfo music, PlayOptions options) { }
	// RVA: 0x3ee7fa4 VA: 0x75964fffa4
	public override Void PlayMusicSyncStatus(IMusicInfo music, PlayOptions options, ChannelPlayStatus status) { }
	// RVA: 0x3ee839c VA: 0x759650039c
	public override Void SetVolume(Single volume) { }
	// RVA: 0x3ee8474 VA: 0x7596500474
	public override Void Stop() { }
	// RVA: 0x3ee853c VA: 0x759650053c
	public override ChannelPlayStatus GetChannelPlayStatus() { }
	// RVA: 0x3ee8600 VA: 0x7596500600
	public override String LogAudioMixer() { }
	// RVA: 0x3ee6d38 VA: 0x75964fed38
	private Boolean _FindActiveSourceIndex(out Int32 index, out Int32 targetSamples) { }
	// RVA: 0x3ee781c VA: 0x75964ff81c
	private static Void _PrepareClipInput(AudioAsset asset, ref String[] clipKeys, ref AudioClip[] clips, out Int32 clipCount) { }
	// RVA: 0x3ee86d4 VA: 0x75965006d4
	private Void _PrepareAudioSources(Int32 count) { }
	// RVA: 0x3ee790c VA: 0x75964ff90c
	private Void _PlayAudioImpl(Int32 clipCount, Boolean loop, Single delay) { }
	// RVA: 0x3ee80c4 VA: 0x75965000c4
	private Void _PlayAudioWithTargetStats(Int32 clipCount, Boolean loop, ChannelPlayStatus channelPlayStatus) { }
	// RVA: 0x3ee7b64 VA: 0x75964ffb64
	private Void _UpdateSoundProperties(ISoundInfo sound) { }
	// RVA: 0x3ee7e68 VA: 0x75964ffe68
	private Void _UpdateMusicProperties(IMusicInfo music) { }
	// RVA: 0x3ee8ab0 VA: 0x7596500ab0
	private Void _UpdateAudioSourceStatus(Single spatialBlend, AudioMixerGroup mixerGroup) { }
	// RVA: 0x3ee8860 VA: 0x7596500860
	private ChannelAudioSource _CreateAudioSource() { }
	// RVA: 0x3ee5768 VA: 0x75964fd768
	public Void .ctor() { }
}
```