# VoiceManager

**Namespace:** `Torappu.CharWord`


## Properties

- `Boolean isPlaying`


## Methods

- `Void OnResourceListUpdate(Boolean)`

- `Boolean get_isPlaying()`

- `Single GetCurrentTimePercent()`

- `PlayingStatus GetPlayingStatus()`

- `PlayResult PlayRandomLoadingVoice(Boolean, Single, Single)`

- `PlayResult PlayRandomVoice(IList`1, CharWordShowType, Boolean, Single, Single)`

- `PlayResult PlayRandomVoice(VoiceQuery, CharWordShowType, Boolean, Single, Single)`

- `PlayResult PlayRandomVoice(VoiceQuery, IList`1, Boolean, Single, Single)`

- `PlayResult PlayRandomVoiceWithVoiceLangType(VoiceQuery, CharWordShowType, Boolean, Single, Single)`

- `PlayResult PlayVoice(ICharWordData, Boolean, Single, Single)`

- `PlayResult PlayVoiceWithVoiceLangType(ICharWordData, VoiceLangType, Boolean, Single, Single)`

- `PlayResult _PlayVoiceImpl(ICharWordData, String, Single, Single)`

- `Void StopVoice(Single)`

- `Void PreloadAssets(VoiceQuery, IList`1)`

- `Void UnloadPreloadedAssets()`

- `Boolean CheckVoiceAvailable(String)`

- `Boolean CheckVoiceAvailable(VoiceQuery, CharWordShowType)`

- `Void _ClearCache(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.CharWord
public class VoiceManager : Singleton`1, IResourceListener
{
	private const String AUDIO_CHANNEL_VOICE; // 0x0
	private const Single CROSSFADE_DURATION; // 0x0
	private Dictionary`2 m_avaliableDict; // 0x10
	private List`1 m_randomBuffer; // 0x18
	private List`1 m_filterBuffer; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_OnResourceListUpdate; // 0x8
	private static DelegateBridge __Hotfix0_get_isPlaying; // 0x10
	private static DelegateBridge __Hotfix0_GetCurrentTimePercent; // 0x18
	private static DelegateBridge __Hotfix0_GetPlayingStatus; // 0x20
	private static DelegateBridge __Hotfix0_PlayRandomLoadingVoice; // 0x28
	private static DelegateBridge __Hotfix0_PlayRandomVoice; // 0x30
	private static DelegateBridge __Hotfix1_PlayRandomVoice; // 0x38
	private static DelegateBridge __Hotfix2_PlayRandomVoice; // 0x40
	private static DelegateBridge __Hotfix0_PlayRandomVoiceWithVoiceLangType; // 0x48
	private static DelegateBridge __Hotfix0_PlayVoice; // 0x50
	private static DelegateBridge __Hotfix0_PlayVoiceWithVoiceLangType; // 0x58
	private static DelegateBridge __Hotfix0__PlayVoiceImpl; // 0x60
	private static DelegateBridge __Hotfix0_StopVoice; // 0x68
	private static DelegateBridge __Hotfix0_PreloadAssets; // 0x70
	private static DelegateBridge __Hotfix0_UnloadPreloadedAssets; // 0x78
	private static DelegateBridge __Hotfix0_CheckVoiceAvailable; // 0x80
	private static DelegateBridge __Hotfix1_CheckVoiceAvailable; // 0x88
	private static DelegateBridge __Hotfix0__ClearCache; // 0x90

	public Boolean isPlaying { get; }

	// RVA: 0x376a49c VA: 0x7595d8249c
	private Void .ctor() { }
	// RVA: 0x376a5f8 VA: 0x7595d825f8
	public Void OnResourceListUpdate(Boolean isInit) { }
	// RVA: 0x376a714 VA: 0x7595d82714
	public Boolean get_isPlaying() { }
	// RVA: 0x376a7a0 VA: 0x7595d827a0
	public Single GetCurrentTimePercent() { }
	// RVA: 0x376a83c VA: 0x7595d8283c
	public PlayingStatus GetPlayingStatus() { }
	// RVA: 0x376a96c VA: 0x7595d8296c
	public PlayResult PlayRandomLoadingVoice(Boolean overlapFlag, Single crossfade, Single delay) { }
	// RVA: 0x376adec VA: 0x7595d82dec
	public PlayResult PlayRandomVoice(IList`1 queryList, CharWordShowType showType, Boolean overlapFlag, Single crossfade, Single delay) { }
	// RVA: 0x376b4d8 VA: 0x7595d834d8
	public PlayResult PlayRandomVoice(VoiceQuery query, CharWordShowType showType, Boolean overlapFlag, Single crossfade, Single delay) { }
	// RVA: 0x376b830 VA: 0x7595d83830
	public PlayResult PlayRandomVoice(VoiceQuery query, IList`1 showTypes, Boolean overlapFlag, Single crossfade, Single delay) { }
	// RVA: 0x376bc6c VA: 0x7595d83c6c
	public PlayResult PlayRandomVoiceWithVoiceLangType(VoiceQuery query, CharWordShowType showType, Boolean overlapFlag, Single crossfade, Single delay) { }
	// RVA: 0x376b374 VA: 0x7595d83374
	public PlayResult PlayVoice(ICharWordData charwordData, Boolean overlapFlag, Single crossfade, Single delay) { }
	// RVA: 0x376ac70 VA: 0x7595d82c70
	public PlayResult PlayVoiceWithVoiceLangType(ICharWordData charWordData, VoiceLangType langType, Boolean overlapFlag, Single crossFade, Single delay) { }
	// RVA: 0x376bfd0 VA: 0x7595d83fd0
	private PlayResult _PlayVoiceImpl(ICharWordData charWordData, String voicePath, Single crossFade, Single delay) { }
	// RVA: 0x376c1dc VA: 0x7595d841dc
	public Void StopVoice(Single duration) { }
	// RVA: 0x376c294 VA: 0x7595d84294
	public Void PreloadAssets(VoiceQuery query, IList`1 showType) { }
	// RVA: 0x376c574 VA: 0x7595d84574
	public Void UnloadPreloadedAssets() { }
	// RVA: 0x376b254 VA: 0x7595d83254
	public Boolean CheckVoiceAvailable(String path) { }
	// RVA: 0x376c5f4 VA: 0x7595d845f4
	public Boolean CheckVoiceAvailable(VoiceQuery query, CharWordShowType showType) { }
	// RVA: 0x376a678 VA: 0x7595d82678
	private Void _ClearCache(Boolean isInit) { }
}
```