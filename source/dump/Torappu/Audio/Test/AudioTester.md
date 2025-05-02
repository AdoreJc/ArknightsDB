# AudioTester

**Namespace:** `Torappu.Audio.Test`


## Fields

- `Rect m_mixerWindowRect`

- `String m_mixerTransitionToSnapshot`

- `Single m_mixerTransitionDuration`

- `Rect m_musicWindowRect`

- `String m_musicIntroKey`

- `String m_musicLoopKey`

- `Single m_musicVolume`

- `Single m_musicDelay`

- `Single m_musicCrossfadeDuration`

- `Rect m_voiceWindowRect`

- `String m_voiceKey`

- `String m_voiceChannel`

- `Single m_voiceVolume`

- `Single m_voiceDelay`

- `Boolean m_voiceLoop`

- `Rect m_fxWindowRect`

- `String m_fxKey`

- `String m_fxChannel`

- `Single m_fxVolume`

- `Single m_fxDelay`

- `Boolean m_fxLoop`

- `Rect m_audioClipManagerWindowRect`

- `String m_audioSignalToPreload`

- `String m_preloadPersistTag`

- `Int32 m_audioMaxInstance`

- `Vector2 m_audioClipScroll`

- `Rect m_channelWindowRect`

- `Vector2 m_channelScroll`


## Methods

- `Void Awake()`

- `Single _LayoutHorizontalSlider(String, Single, Single, Single, Single, String)`

- `String _LayoutTextField(String, Single, String, Single)`

- `Void _MakeMixerWindow(Int32)`

- `Void _MakeMusicWindow(Int32)`

- `Void _MakeVoiceWindow(Int32)`

- `Void _MakeSoundWindow(Int32)`

- `Void _MakeAudioClipManagerWindow(Int32)`

- `Void _MakeChannelWindow(Int32)`

- `Void OnGUI()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Audio.Test
public class AudioTester : MonoBehaviour
{
	private Rect m_mixerWindowRect; // 0x18
	private String m_mixerTransitionToSnapshot; // 0x28
	private Single m_mixerTransitionDuration; // 0x30
	private Rect m_musicWindowRect; // 0x34
	private String m_musicIntroKey; // 0x48
	private String m_musicLoopKey; // 0x50
	private Single m_musicVolume; // 0x58
	private Single m_musicDelay; // 0x5c
	private Single m_musicCrossfadeDuration; // 0x60
	private Rect m_voiceWindowRect; // 0x64
	private String m_voiceKey; // 0x78
	private String m_voiceChannel; // 0x80
	private Single m_voiceVolume; // 0x88
	private Single m_voiceDelay; // 0x8c
	private Boolean m_voiceLoop; // 0x90
	private Rect m_fxWindowRect; // 0x94
	private String m_fxKey; // 0xa8
	private String m_fxChannel; // 0xb0
	private Single m_fxVolume; // 0xb8
	private Single m_fxDelay; // 0xbc
	private Boolean m_fxLoop; // 0xc0
	private Rect m_audioClipManagerWindowRect; // 0xc4
	private String m_audioSignalToPreload; // 0xd8
	private String m_preloadPersistTag; // 0xe0
	private Int32 m_audioMaxInstance; // 0xe8
	private Vector2 m_audioClipScroll; // 0xec
	private Rect m_channelWindowRect; // 0xf4
	private Vector2 m_channelScroll; // 0x104


	// RVA: 0x3ebae90 VA: 0x75964d2e90
	private Void Awake() { }
	// RVA: 0x3ebae98 VA: 0x75964d2e98
	private Single _LayoutHorizontalSlider(String title, Single titleWidth, Single value, Single left, Single right, String valueFormat) { }
	// RVA: 0x3ebb0d0 VA: 0x75964d30d0
	private String _LayoutTextField(String title, Single titleWidth, String text, Single fieldWidth) { }
	// RVA: 0x3ebb2cc VA: 0x75964d32cc
	private Void _MakeMixerWindow(Int32 windowID) { }
	// RVA: 0x3ebb624 VA: 0x75964d3624
	private Void _MakeMusicWindow(Int32 windowID) { }
	// RVA: 0x3ebb83c VA: 0x75964d383c
	private Void _MakeVoiceWindow(Int32 windowID) { }
	// RVA: 0x3ebbcd0 VA: 0x75964d3cd0
	private Void _MakeSoundWindow(Int32 windowID) { }
	// RVA: 0x3ebc410 VA: 0x75964d4410
	private Void _MakeAudioClipManagerWindow(Int32 windowID) { }
	// RVA: 0x3ebcb3c VA: 0x75964d4b3c
	private Void _MakeChannelWindow(Int32 windowID) { }
	// RVA: 0x3ebd1f4 VA: 0x75964d51f4
	private Void OnGUI() { }
	// RVA: 0x3ebc408 VA: 0x75964d4408
	public static AudioChannel PlaySoundFx(String key, AudioPlayOption playOption, FXCategory fxCategory, Boolean important) { }
	// RVA: 0x3ebd754 VA: 0x75964d5754
	public Void .ctor() { }
}
```