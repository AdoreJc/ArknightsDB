# DebugOverlay

**Namespace:** `RenderHeads.Media.AVProVideo`


## Fields

- `MediaPlayer _mediaPlayer`

- `Int32 _guiDepth`

- `Single _displaySize`

- `Int32 _debugOverlayCount`

- `Boolean _displayControls`

- `Int32 m_GuiPositionX`


## Properties

- `Boolean DisplayControls`

- `MediaPlayer CurrentMediaPlayer`


## Methods

- `Boolean get_DisplayControls()`

- `Void set_DisplayControls(Boolean)`

- `MediaPlayer get_CurrentMediaPlayer()`

- `Void set_CurrentMediaPlayer(MediaPlayer)`

- `Void SetGuiPositionFromVideoIndex(Int32)`

- `Void Update()`

- `Void OnGUI()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : RenderHeads.Media.AVProVideo
public class DebugOverlay : MonoBehaviour
{
	private MediaPlayer _mediaPlayer; // 0x18
	private Int32 _guiDepth; // 0x20
	private Single _displaySize; // 0x24
	private Int32 _debugOverlayCount; // 0x28
	private Boolean _displayControls; // 0x2c
	private const Int32 s_GuiStartWidth; // 0x0
	private const Int32 s_GuiWidth; // 0x0
	private Int32 m_GuiPositionX; // 0x30

	public Boolean DisplayControls { get; set; }
	public MediaPlayer CurrentMediaPlayer { get; set; }

	// RVA: 0x6679374 VA: 0x7598c91374
	public Boolean get_DisplayControls() { }
	// RVA: 0x667937c VA: 0x7598c9137c
	public Void set_DisplayControls(Boolean value) { }
	// RVA: 0x6679388 VA: 0x7598c91388
	public MediaPlayer get_CurrentMediaPlayer() { }
	// RVA: 0x6679390 VA: 0x7598c91390
	public Void set_CurrentMediaPlayer(MediaPlayer value) { }
	// RVA: 0x6679420 VA: 0x7598c91420
	private Void SetGuiPositionFromVideoIndex(Int32 index) { }
	// RVA: 0x66794b8 VA: 0x7598c914b8
	private Void Update() { }
	// RVA: 0x66794c0 VA: 0x7598c914c0
	private Void OnGUI() { }
	// RVA: 0x667aa28 VA: 0x7598c92a28
	public Void .ctor() { }
}
```