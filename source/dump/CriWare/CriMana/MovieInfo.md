# MovieInfo

**Namespace:** `CriWare.CriMana`


## Fields

- `UInt32 _reserved1`

- `UInt32 numAlphaStreams`

- `UInt32 width`

- `UInt32 height`

- `UInt32 dispWidth`

- `UInt32 dispHeight`

- `UInt32 framerateN`

- `UInt32 framerateD`

- `UInt32 totalFrames`

- `CodecType codecType`

- `CodecType alphaCodecType`

- `UInt32 numAudioStreams`

- `UInt32 numSubtitleChannels`

- `UInt32 maxSubtitleSize`

- `UInt32 maxChunkSize`


## Properties

- `Boolean hasAlpha`


## Methods

- `Boolean get_hasAlpha()`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare.CriMana
public class MovieInfo
{
	private UInt32 _reserved1; // 0x10
	public UInt32 numAlphaStreams; // 0x14
	public UInt32 width; // 0x18
	public UInt32 height; // 0x1c
	public UInt32 dispWidth; // 0x20
	public UInt32 dispHeight; // 0x24
	public UInt32 framerateN; // 0x28
	public UInt32 framerateD; // 0x2c
	public UInt32 totalFrames; // 0x30
	public CodecType codecType; // 0x34
	public CodecType alphaCodecType; // 0x38
	public UInt32 numAudioStreams; // 0x3c
	public AudioInfo[] audioPrm; // 0x40
	public UInt32 numSubtitleChannels; // 0x48
	public UInt32 maxSubtitleSize; // 0x4c
	public UInt32 maxChunkSize; // 0x50

	public Boolean hasAlpha { get; set; }

	// RVA: 0x4155de4 VA: 0x759676dde4
	public Boolean get_hasAlpha() { }
	// RVA: 0x4155df4 VA: 0x759676ddf4
	internal Void set_hasAlpha(Boolean value) { }
	// RVA: 0x4155e10 VA: 0x759676de10
	public Void .ctor() { }
}
```