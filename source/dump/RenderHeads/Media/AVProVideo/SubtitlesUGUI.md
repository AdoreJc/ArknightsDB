# SubtitlesUGUI

**Namespace:** `RenderHeads.Media.AVProVideo`


## Fields

- `MediaPlayer _mediaPlayer`

- `Text _text`


## Methods

- `Void Start()`

- `Void OnDestroy()`

- `Void ChangeMediaPlayer(MediaPlayer)`

- `Void OnMediaPlayerEvent(MediaPlayer, EventType, ErrorCode)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : RenderHeads.Media.AVProVideo
public class SubtitlesUGUI : MonoBehaviour
{
	private MediaPlayer _mediaPlayer; // 0x18
	private Text _text; // 0x20


	// RVA: 0x6688f30 VA: 0x7598ca0f30
	private Void Start() { }
	// RVA: 0x66890d4 VA: 0x7598ca10d4
	private Void OnDestroy() { }
	// RVA: 0x6688f38 VA: 0x7598ca0f38
	public Void ChangeMediaPlayer(MediaPlayer newPlayer) { }
	// RVA: 0x66890dc VA: 0x7598ca10dc
	private Void OnMediaPlayerEvent(MediaPlayer mp, EventType et, ErrorCode errorCode) { }
	// RVA: 0x66892b8 VA: 0x7598ca12b8
	public Void .ctor() { }
}
```