# Resampler

**Namespace:** `RenderHeads.Media.AVProVideo`


## Fields

- `MediaPlayer _mediaPlayer`

- `Int32 _start`

- `Int32 _end`

- `Int32 _bufferSize`

- `Int64 _baseTimestamp`

- `Single _elapsedTimeSinceBase`

- `Material _blendMat`

- `ResampleMode _resampleMode`

- `String _name`

- `Int64 _lastTimeStamp`

- `Int32 _droppedFrames`

- `Int64 _lastDisplayedTimestamp`

- `Int32 _frameDisplayedTimer`

- `Int64 _currentDisplayedTimestamp`

- `Single <LastT>k__BackingField`

- `Int64 <TextureTimeStamp>k__BackingField`

- `Int32 _propAfterTex`

- `Int32 _propT`

- `Single _videoFrameRate`


## Properties

- `Int32 DroppedFrames`

- `Int32 FrameDisplayedTimer`

- `Int64 BaseTimestamp`

- `Single ElapsedTimeSinceBase`

- `Single LastT`

- `Int64 TextureTimeStamp`


## Methods

- `Int32 get_DroppedFrames()`

- `Int32 get_FrameDisplayedTimer()`

- `Int64 get_BaseTimestamp()`

- `Void set_BaseTimestamp(Int64)`

- `Single get_ElapsedTimeSinceBase()`

- `Void set_ElapsedTimeSinceBase(Single)`

- `Single get_LastT()`

- `Void set_LastT(Single)`

- `Int64 get_TextureTimeStamp()`

- `Void set_TextureTimeStamp(Int64)`

- `Void OnVideoEvent(MediaPlayer, EventType, ErrorCode)`

- `Void Reset()`

- `Void Release()`

- `Void ReleaseRenderTextures()`

- `Void ConstructRenderTextures()`

- `Boolean CheckRenderTexturesValid()`

- `Int32 FindBeforeFrameIndex(Int32)`

- `Int32 FindClosestFrame(Int32)`

- `Void PointUpdate()`

- `Void SampleFrame(Int32, Int32)`

- `Void SampleFrames(Int32, Int32, Int32, Single)`

- `Void LinearUpdate()`

- `Void InvalidateBuffer()`

- `Single GuessFrameRate()`

- `Void Update()`

- `Void UpdateTimestamp()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : RenderHeads.Media.AVProVideo
public class Resampler
{
	private List`1 _buffer; // 0x10
	private MediaPlayer _mediaPlayer; // 0x18
	private RenderTexture[] _outputTexture; // 0x20
	private Int32 _start; // 0x28
	private Int32 _end; // 0x2c
	private Int32 _bufferSize; // 0x30
	private Int64 _baseTimestamp; // 0x38
	private Single _elapsedTimeSinceBase; // 0x40
	private Material _blendMat; // 0x48
	private ResampleMode _resampleMode; // 0x50
	private String _name; // 0x58
	private Int64 _lastTimeStamp; // 0x60
	private Int32 _droppedFrames; // 0x68
	private Int64 _lastDisplayedTimestamp; // 0x70
	private Int32 _frameDisplayedTimer; // 0x78
	private Int64 _currentDisplayedTimestamp; // 0x80
	private Single <LastT>k__BackingField; // 0x88
	private Int64 <TextureTimeStamp>k__BackingField; // 0x90
	private const String ShaderPropT; // 0x0
	private const String ShaderPropAftertex; // 0x0
	private Int32 _propAfterTex; // 0x98
	private Int32 _propT; // 0x9c
	private Single _videoFrameRate; // 0xa0

	public Int32 DroppedFrames { get; }
	public Int32 FrameDisplayedTimer { get; }
	public Int64 BaseTimestamp { get; set; }
	public Single ElapsedTimeSinceBase { get; set; }
	public Single LastT { get; set; }
	public Int64 TextureTimeStamp { get; set; }
	public Texture[] OutputTexture { get; }

	// RVA: 0x6694ed0 VA: 0x7598caced0
	public Int32 get_DroppedFrames() { }
	// RVA: 0x6694ed8 VA: 0x7598caced8
	public Int32 get_FrameDisplayedTimer() { }
	// RVA: 0x6694ee0 VA: 0x7598cacee0
	public Int64 get_BaseTimestamp() { }
	// RVA: 0x6694ee8 VA: 0x7598cacee8
	public Void set_BaseTimestamp(Int64 value) { }
	// RVA: 0x6694ef0 VA: 0x7598cacef0
	public Single get_ElapsedTimeSinceBase() { }
	// RVA: 0x6694ef8 VA: 0x7598cacef8
	public Void set_ElapsedTimeSinceBase(Single value) { }
	// RVA: 0x6694f00 VA: 0x7598cacf00
	public Single get_LastT() { }
	// RVA: 0x6694f08 VA: 0x7598cacf08
	private Void set_LastT(Single value) { }
	// RVA: 0x6694f10 VA: 0x7598cacf10
	public Int64 get_TextureTimeStamp() { }
	// RVA: 0x6694f18 VA: 0x7598cacf18
	private Void set_TextureTimeStamp(Int64 value) { }
	// RVA: 0x6694f20 VA: 0x7598cacf20
	public Void OnVideoEvent(MediaPlayer mp, EventType et, ErrorCode errorCode) { }
	// RVA: 0x6695048 VA: 0x7598cad048
	public Void .ctor(MediaPlayer player, String name, Int32 bufferSize, ResampleMode resampleMode) { }
	// RVA: 0x6695360 VA: 0x7598cad360
	public Texture[] get_OutputTexture() { }
	// RVA: 0x6695038 VA: 0x7598cad038
	public Void Reset() { }
	// RVA: 0x6695470 VA: 0x7598cad470
	public Void Release() { }
	// RVA: 0x6695508 VA: 0x7598cad508
	private Void ReleaseRenderTextures() { }
	// RVA: 0x6695718 VA: 0x7598cad718
	private Void ConstructRenderTextures() { }
	// RVA: 0x6695d28 VA: 0x7598cadd28
	private Boolean CheckRenderTexturesValid() { }
	// RVA: 0x66960e4 VA: 0x7598cae0e4
	private Int32 FindBeforeFrameIndex(Int32 frameIdx) { }
	// RVA: 0x669627c VA: 0x7598cae27c
	private Int32 FindClosestFrame(Int32 frameIdx) { }
	// RVA: 0x66963dc VA: 0x7598cae3dc
	private Void PointUpdate() { }
	// RVA: 0x669656c VA: 0x7598cae56c
	private Void SampleFrame(Int32 frameIdx, Int32 bufferIdx) { }
	// RVA: 0x66966bc VA: 0x7598cae6bc
	private Void SampleFrames(Int32 bufferIdx, Int32 frameIdx1, Int32 frameIdx2, Single t) { }
	// RVA: 0x6696948 VA: 0x7598cae948
	private Void LinearUpdate() { }
	// RVA: 0x6695368 VA: 0x7598cad368
	private Void InvalidateBuffer() { }
	// RVA: 0x6696b1c VA: 0x7598caeb1c
	private Single GuessFrameRate() { }
	// RVA: 0x6696d68 VA: 0x7598caed68
	public Void Update() { }
	// RVA: 0x6697974 VA: 0x7598caf974
	public Void UpdateTimestamp() { }
}
```