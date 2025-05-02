# FrameInfo

**Namespace:** `CriWare.CriMana`


## Fields

- `Int32 frameNo`

- `Int32 frameNoPerFile`

- `UInt32 width`

- `UInt32 height`

- `UInt32 dispWidth`

- `UInt32 dispHeight`

- `UInt32 numImages`

- `UInt32 framerateN`

- `UInt32 framerateD`

- `UInt32 _reserved1`

- `UInt64 time`

- `UInt64 tunit`

- `UInt32 cntConcatenatedMovie`

- `AlphaType alphaType`

- `UInt32 cntSkippedFrames`

- `UInt32 totalFramesPerFile`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare.CriMana
public class FrameInfo
{
	public Int32 frameNo; // 0x10
	public Int32 frameNoPerFile; // 0x14
	public UInt32 width; // 0x18
	public UInt32 height; // 0x1c
	public UInt32 dispWidth; // 0x20
	public UInt32 dispHeight; // 0x24
	public UInt32 numImages; // 0x28
	public UInt32 framerateN; // 0x2c
	public UInt32 framerateD; // 0x30
	private UInt32 _reserved1; // 0x34
	public UInt64 time; // 0x38
	public UInt64 tunit; // 0x40
	public UInt32 cntConcatenatedMovie; // 0x48
	private AlphaType alphaType; // 0x4c
	public UInt32 cntSkippedFrames; // 0x50
	public UInt32 totalFramesPerFile; // 0x54


	// RVA: 0x4155e18 VA: 0x759676de18
	public Void .ctor() { }
}
```