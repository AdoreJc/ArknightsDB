# AudioOutput

**Namespace:** `RenderHeads.Media.AVProVideo`


## Fields

- `AudioOutputMode _audioOutputMode`

- `MediaPlayer _mediaPlayer`

- `AudioSource _audioSource`

- `Int32 _channelMask`


## Methods

- `Void Awake()`

- `Void Start()`

- `Void OnDestroy()`

- `Void Update()`

- `Void ChangeMediaPlayer(MediaPlayer)`

- `Void OnMediaPlayerEvent(MediaPlayer, EventType, ErrorCode)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : RenderHeads.Media.AVProVideo
public class AudioOutput : MonoBehaviour
{
	public AudioOutputMode _audioOutputMode; // 0x18
	private MediaPlayer _mediaPlayer; // 0x20
	private AudioSource _audioSource; // 0x28
	public Int32 _channelMask; // 0x30


	// RVA: 0x66776e4 VA: 0x7598c8f6e4
	private Void Awake() { }
	// RVA: 0x667773c VA: 0x7598c8f73c
	private Void Start() { }
	// RVA: 0x66778e4 VA: 0x7598c8f8e4
	private Void OnDestroy() { }
	// RVA: 0x66778ec VA: 0x7598c8f8ec
	private Void Update() { }
	// RVA: 0x6677744 VA: 0x7598c8f744
	public Void ChangeMediaPlayer(MediaPlayer newPlayer) { }
	// RVA: 0x6677c64 VA: 0x7598c8fc64
	private Void OnMediaPlayerEvent(MediaPlayer mp, EventType et, ErrorCode errorCode) { }
	// RVA: 0x6677a10 VA: 0x7598c8fa10
	private static Void ApplyAudioSettings(MediaPlayer player, AudioSource audioSource) { }
	// RVA: 0x6677cb8 VA: 0x7598c8fcb8
	public Void .ctor() { }
}
```