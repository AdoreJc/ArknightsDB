# AudioManager

**Namespace:** `Torappu`


## Fields

- `AudioOptions m_audioOptions`

- `GameObject m_audioSourcesHolder`

- `Component m_listener`

- `Int32 m_allocatedChannelID`

- `Single m_musicVolume`

- `Single m_fxVolume`

- `Single m_voiceVolume`

- `SnapshotParam m_currentSnapshotParam`

- `AudioEngine m_engine`

- `AudioAssetRefCollection m_assetsCache`


## Properties

- `Single _musicVolume`

- `Single _fxVolume`

- `Single _voiceVolume`


## Methods

- `Single get__musicVolume()`

- `Void set__musicVolume(Single)`

- `Single get__fxVolume()`

- `Void set__fxVolume(Single)`

- `Single get__voiceVolume()`

- `Void set__voiceVolume(Single)`

- `Void _Init()`

- `AudioChannel _CreateChannel()`

- `Void _StopMusicWithFade(String, AudioFadeParam)`

- `Void _SetListenerPosition(Vector3, Quaternion)`

- `Void _RecycleChannel(AudioChannel)`

- `Void _ApplyChannelEffect(AudioChannelEffect)`

- `Void _RemoveChannelEffect(AudioChannelEffect)`

- `Void _UpdateChannelEffects()`

- `Void _ClearAllChannelEffects()`

- `Void _OnAudioOptionsChanged()`

- `Void _OnAudioConfigChanged(Boolean)`

- `Void _OnSettingChange(SettingType)`

- `Void Update()`

- `Void _InitEngine()`

- `AudioChannel _PlayAudio(TParam, AudioPlayOption)`

- `AudioChannel _PlayMusicWithSyncChannel(MusicParam, AudioPlayOption, AudioFadeParam, String)`

- `IEnumerator _StopAllChannels(Single, EaseType)`

- `Void _PreloadAudio(TParam)`

- `AudioAssetRefCollection _EnsureAudioAssetsRefCache(String)`

- `Void _StopChannelsWithAssets(AudioAssetRefCollection)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class AudioManager : PersistentSingleton`1, IHotfixable, ISingletonNotAutoCreate
{
	public const String SNAPSHOT_DEFAULT; // 0x0
	public const String CHANNEL_MUSIC; // 0x0
	private const String CHANNEL_AUTO; // 0x0
	private static String[] s_singleSnapshot; // 0x0
	private static Single[] s_singleWeight; // 0x8
	private AudioOptions m_audioOptions; // 0x18
	private GameObject m_audioSourcesHolder; // 0x20
	private Component m_listener; // 0x28
	private ObjectPool`1 m_channelPool; // 0x30
	private Dictionary`2 m_channels; // 0x38
	private Int32 m_allocatedChannelID; // 0x40
	private List`1 m_tempChannelsToRemove; // 0x48
	private HashSet`1 m_channelEffects; // 0x50
	private Single m_musicVolume; // 0x58
	private Single m_fxVolume; // 0x5c
	private Single m_voiceVolume; // 0x60
	private SnapshotParam m_currentSnapshotParam; // 0x68
	private AudioEngine m_engine; // 0x70
	private AudioAssetRefCollection m_assetsCache; // 0x78
	private static DelegateBridge __Hotfix0_get_musicVolume; // 0x10
	private static DelegateBridge __Hotfix0_set_musicVolume; // 0x18
	private static DelegateBridge __Hotfix0_get_fxVolume; // 0x20
	private static DelegateBridge __Hotfix0_set_fxVolume; // 0x28
	private static DelegateBridge __Hotfix0_get_voiceVolume; // 0x30
	private static DelegateBridge __Hotfix0_set_voiceVolume; // 0x38
	private static DelegateBridge __Hotfix0_get_currentSnapshotParam; // 0x40
	private static DelegateBridge __Hotfix0_get_inspectAudioAssets; // 0x48
	private static DelegateBridge __Hotfix0_Init; // 0x50
	private static DelegateBridge __Hotfix0_StopGroupMusicWithFade; // 0x58
	private static DelegateBridge __Hotfix0_GetChannel; // 0x60
	private static DelegateBridge __Hotfix0_GetMusicChannel; // 0x68
	private static DelegateBridge __Hotfix0_StopChannel; // 0x70
	private static DelegateBridge __Hotfix0_StopMusic; // 0x78
	private static DelegateBridge __Hotfix0_TransitionToDefaultSnapshot; // 0x80
	private static DelegateBridge __Hotfix0_TransitionToSnapshot; // 0x88
	private static DelegateBridge __Hotfix0_SetListenerPosition; // 0x90
	private static DelegateBridge __Hotfix0_IsAudioChannelActive; // 0x98
	private static DelegateBridge __Hotfix0_ApplyChannelEffect; // 0xa0
	private static DelegateBridge __Hotfix0_RemoveChannelEffect; // 0xa8
	private static DelegateBridge __Hotfix0_ClearAllChannelEffects; // 0xb0
	private static DelegateBridge __Hotfix0_get_channelPool; // 0xb8
	private static DelegateBridge __Hotfix0_get_channels; // 0xc0
	private static DelegateBridge __Hotfix0_get__musicVolume; // 0xc8
	private static DelegateBridge __Hotfix0_set__musicVolume; // 0xd0
	private static DelegateBridge __Hotfix0_get__fxVolume; // 0xd8
	private static DelegateBridge __Hotfix0_set__fxVolume; // 0xe0
	private static DelegateBridge __Hotfix0_get__voiceVolume; // 0xe8
	private static DelegateBridge __Hotfix0_set__voiceVolume; // 0xf0
	private static DelegateBridge __Hotfix0__Init; // 0xf8
	private static DelegateBridge __Hotfix0__CreateChannel; // 0x100
	private static DelegateBridge __Hotfix0__StopMusicWithFade; // 0x108
	private static DelegateBridge __Hotfix0__SetListenerPosition; // 0x110
	private static DelegateBridge __Hotfix0__RecycleChannel; // 0x118
	private static DelegateBridge __Hotfix0__ApplyChannelEffect; // 0x120
	private static DelegateBridge __Hotfix0__RemoveChannelEffect; // 0x128
	private static DelegateBridge __Hotfix0__UpdateChannelEffects; // 0x130
	private static DelegateBridge __Hotfix0__ClearAllChannelEffects; // 0x138
	private static DelegateBridge __Hotfix0__OnAudioOptionsChanged; // 0x140
	private static DelegateBridge __Hotfix0__OnAudioConfigChanged; // 0x148
	private static DelegateBridge __Hotfix0__OnSettingChange; // 0x150
	private static DelegateBridge __Hotfix0_OnInit; // 0x158
	private static DelegateBridge __Hotfix0_Update; // 0x160
	private static DelegateBridge __Hotfix0__InitEngine; // 0x168
	private static DelegateBridge __Hotfix0_OnReloadBanks; // 0x170
	private static DelegateBridge __Hotfix0_GetMixerParam; // 0x178
	private static DelegateBridge __Hotfix0_SetMixerParam; // 0x180
	private static DelegateBridge __Hotfix0_PlayVoice; // 0x188
	private static DelegateBridge __Hotfix0_PlayMusicForAVG; // 0x190
	private static DelegateBridge __Hotfix0_PlaySoundForAVG; // 0x198
	private static DelegateBridge __Hotfix0_PlayAudio; // 0x1a0
	private static DelegateBridge __Hotfix0__PlayAudio; // 0x1a8
	private static DelegateBridge __Hotfix0_PlayMusicWithSyncChannel; // 0x1b0
	private static DelegateBridge __Hotfix0__PlayMusicWithSyncChannel; // 0x1b8
	private static DelegateBridge __Hotfix1_TransitionToSnapshot; // 0x1c0
	private static DelegateBridge __Hotfix0_UnloadAll; // 0x1c8
	private static DelegateBridge __Hotfix0__StopAllChannels; // 0x1d0
	private static DelegateBridge __Hotfix0_PreloadAudio; // 0x1d8
	private static DelegateBridge __Hotfix0_PreloadVoice; // 0x1e0
	private static DelegateBridge __Hotfix0__PreloadAudio; // 0x1e8
	private static DelegateBridge __Hotfix0_UnloadPreloadedAudios; // 0x1f0
	private static DelegateBridge __Hotfix0_StopPreloadedAudios; // 0x1f8
	private static DelegateBridge __Hotfix0__EnsureAudioAssetsRefCache; // 0x200
	private static DelegateBridge __Hotfix0__StopChannelsWithAssets; // 0x208
	private static DelegateBridge _c__Hotfix0_ctor; // 0x210

	public static Single musicVolume { get; set; }
	public static Single fxVolume { get; set; }
	public static Single voiceVolume { get; set; }
	public static SnapshotParam currentSnapshotParam { get; }
	public List`1 inspectAudioAssets { get; }
	public ObjectPool`1 channelPool { get; }
	public Dictionary`2 channels { get; }
	private Single _musicVolume { get; set; }
	private Single _fxVolume { get; set; }
	private Single _voiceVolume { get; set; }

	// RVA: 0x2c3109c VA: 0x759524909c
	public static Single get_musicVolume() { }
	// RVA: 0x2c31184 VA: 0x7595249184
	public static Void set_musicVolume(Single value) { }
	// RVA: 0x2c31304 VA: 0x7595249304
	public static Single get_fxVolume() { }
	// RVA: 0x2c313ec VA: 0x75952493ec
	public static Void set_fxVolume(Single value) { }
	// RVA: 0x2c3156c VA: 0x759524956c
	public static Single get_voiceVolume() { }
	// RVA: 0x2c31654 VA: 0x7595249654
	public static Void set_voiceVolume(Single value) { }
	// RVA: 0x2c317d4 VA: 0x75952497d4
	public static SnapshotParam get_currentSnapshotParam() { }
	// RVA: 0x2c31858 VA: 0x7595249858
	public List`1 get_inspectAudioAssets() { }
	// RVA: 0x2c318bc VA: 0x75952498bc
	public static Void Init() { }
	// RVA: 0x2c319a0 VA: 0x75952499a0
	public static Void StopGroupMusicWithFade(String channelName, AudioFadeParam audioFadeParam) { }
	// RVA: 0x2c31c48 VA: 0x7595249c48
	public static AudioChannel GetChannel(String channelName) { }
	// RVA: 0x2c31d78 VA: 0x7595249d78
	public static AudioChannel GetMusicChannel() { }
	// RVA: 0x2c31dec VA: 0x7595249dec
	public static Void StopChannel(String channelName, Single fadeDuration) { }
	// RVA: 0x2c31e9c VA: 0x7595249e9c
	public static Void StopMusic(Single fadeDuration) { }
	// RVA: 0x2c31f28 VA: 0x7595249f28
	public static Void TransitionToDefaultSnapshot(Single duration, Single delay) { }
	// RVA: 0x2c31fc0 VA: 0x7595249fc0
	public static Boolean TransitionToSnapshot(String snapshot, Single duration, Single delay) { }
	// RVA: 0x2c32284 VA: 0x759524a284
	public static Void SetListenerPosition(Vector3 worldPosition, Quaternion worldRotation) { }
	// RVA: 0x2c32544 VA: 0x759524a544
	public static Boolean IsAudioChannelActive(String channelName) { }
	// RVA: 0x2c325c4 VA: 0x759524a5c4
	public static Void ApplyChannelEffect(AudioChannelEffect channelEffect) { }
	// RVA: 0x2c327b4 VA: 0x759524a7b4
	public static Void RemoveChannelEffect(AudioChannelEffect channelEffect) { }
	// RVA: 0x2c32aac VA: 0x759524aaac
	public static Void ClearAllChannelEffects() { }
	// RVA: 0x2c32d5c VA: 0x759524ad5c
	public ObjectPool`1 get_channelPool() { }
	// RVA: 0x2c32dc4 VA: 0x759524adc4
	public Dictionary`2 get_channels() { }
	// RVA: 0x2c3111c VA: 0x759524911c
	private Single get__musicVolume() { }
	// RVA: 0x2c3121c VA: 0x759524921c
	private Void set__musicVolume(Single value) { }
	// RVA: 0x2c31384 VA: 0x7595249384
	private Single get__fxVolume() { }
	// RVA: 0x2c31484 VA: 0x7595249484
	private Void set__fxVolume(Single value) { }
	// RVA: 0x2c315ec VA: 0x75952495ec
	private Single get__voiceVolume() { }
	// RVA: 0x2c316ec VA: 0x75952496ec
	private Void set__voiceVolume(Single value) { }
	// RVA: 0x2c3193c VA: 0x759524993c
	private Void _Init() { }
	// RVA: 0x2c32e2c VA: 0x759524ae2c
	private AudioChannel _CreateChannel() { }
	// RVA: 0x2c31ad8 VA: 0x7595249ad8
	private Void _StopMusicWithFade(String channelName, AudioFadeParam audioFadeParam) { }
	// RVA: 0x2c3240c VA: 0x759524a40c
	private Void _SetListenerPosition(Vector3 worldPosition, Quaternion worldRotation) { }
	// RVA: 0x2c32ee8 VA: 0x759524aee8
	private Void _RecycleChannel(AudioChannel channel) { }
	// RVA: 0x2c326c4 VA: 0x759524a6c4
	private Void _ApplyChannelEffect(AudioChannelEffect channelEffect) { }
	// RVA: 0x2c328b4 VA: 0x759524a8b4
	private Void _RemoveChannelEffect(AudioChannelEffect channelEffect) { }
	// RVA: 0x2c32f88 VA: 0x759524af88
	private Void _UpdateChannelEffects() { }
	// RVA: 0x2c32ba0 VA: 0x759524aba0
	private Void _ClearAllChannelEffects() { }
	// RVA: 0x2c3329c VA: 0x759524b29c
	private Void _OnAudioOptionsChanged() { }
	// RVA: 0x2c33770 VA: 0x759524b770
	private Void _OnAudioConfigChanged(Boolean isDeviceChanged) { }
	// RVA: 0x2c33308 VA: 0x759524b308
	private Void _OnSettingChange(SettingType type) { }
	// RVA: 0x2c337f0 VA: 0x759524b7f0
	protected override Void OnInit() { }
	// RVA: 0x2c34040 VA: 0x759524c040
	private Void Update() { }
	// RVA: 0x2c33ebc VA: 0x759524bebc
	private Void _InitEngine() { }
	// RVA: 0x2c34378 VA: 0x759524c378
	public static Void OnReloadBanks() { }
	// RVA: 0x2c344b8 VA: 0x759524c4b8
	public static Single GetMixerParam(String name, Single defaultVal) { }
	// RVA: 0x2c345fc VA: 0x759524c5fc
	public static Void SetMixerParam(String name, Single value) { }
	// RVA: 0x2c34720 VA: 0x759524c720
	public static AudioChannel PlayVoice(String voicePath, AudioPlayOption playOptions) { }
	// RVA: 0x2c3492c VA: 0x759524c92c
	public static AudioChannel PlayMusicForAVG(String intro, String loop, AudioPlayOption playOptions) { }
	// RVA: 0x2c34b18 VA: 0x759524cb18
	public static AudioChannel PlaySoundForAVG(String asset, Boolean loop, AudioPlayOption playOptions) { }
	// RVA: 0x VA: 0x0
	public static AudioChannel PlayAudio(TParam audioParam, AudioPlayOption options) { }
	// RVA: 0x VA: 0x0
	private AudioChannel _PlayAudio(TParam audioParam, AudioPlayOption options) { }
	// RVA: 0x2c34d04 VA: 0x759524cd04
	public static AudioChannel PlayMusicWithSyncChannel(MusicParam audioParam, AudioPlayOption options, AudioFadeParam audioFadeParam, String channelNameToSync) { }
	// RVA: 0x2c34eb0 VA: 0x759524ceb0
	private AudioChannel _PlayMusicWithSyncChannel(MusicParam audioParam, AudioPlayOption options, AudioFadeParam audioFadeParam, String channelNameToSync) { }
	// RVA: 0x2c320d8 VA: 0x759524a0d8
	public static Boolean TransitionToSnapshot(String[] snapshots, Single[] weights, Single duration, Single delay) { }
	// RVA: 0x2c354e4 VA: 0x759524d4e4
	public static IEnumerator UnloadAll(Single duration, EaseType easeType) { }
	// RVA: 0x2c3559c VA: 0x759524d59c
	private IEnumerator _StopAllChannels(Single duration, EaseType easeType) { }
	// RVA: 0x VA: 0x0
	public static Void PreloadAudio(TParam param) { }
	// RVA: 0x2c35678 VA: 0x759524d678
	public static Void PreloadVoice(String voicePath, String persistTag) { }
	// RVA: 0x VA: 0x0
	public Void _PreloadAudio(TParam param) { }
	// RVA: 0x2c35828 VA: 0x759524d828
	public static Void UnloadPreloadedAudios(String persistTag) { }
	// RVA: 0x2c35c40 VA: 0x759524dc40
	public static Void StopPreloadedAudios(String persistTag) { }
	// RVA: 0x2c35960 VA: 0x759524d960
	private AudioAssetRefCollection _EnsureAudioAssetsRefCache(String persistTag) { }
	// RVA: 0x2c35a60 VA: 0x759524da60
	private Void _StopChannelsWithAssets(AudioAssetRefCollection assetsRef) { }
	// RVA: 0x2c35d4c VA: 0x759524dd4c
	public Void .ctor() { }
}
```