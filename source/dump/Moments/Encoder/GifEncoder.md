# GifEncoder

**Namespace:** `Moments.Encoder`


## Fields

- `Int32 m_Width`

- `Int32 m_Height`

- `Int32 m_Repeat`

- `Int32 m_FrameDelay`

- `Boolean m_HasStarted`

- `FileStream m_FileStream`

- `GifFrame m_CurrentFrame`

- `Int32 m_ColorDepth`

- `Int32 m_PaletteSize`

- `Int32 m_DisposalCode`

- `Boolean m_ShouldCloseStream`

- `Boolean m_IsFirstFrame`

- `Boolean m_IsSizeSet`

- `Int32 m_SampleInterval`


## Methods

- `Void SetDelay(Int32)`

- `Void SetFrameRate(Single)`

- `Void AddFrame(GifFrame)`

- `Void Start(FileStream)`

- `Void Start(String)`

- `Void Finish()`

- `Void SetSize(Int32, Int32)`

- `Void GetImagePixels()`

- `Void AnalyzePixels()`

- `Void WriteGraphicCtrlExt()`

- `Void WriteImageDesc()`

- `Void WriteLSD()`

- `Void WriteNetscapeExt()`

- `Void WritePalette()`

- `Void WritePixels()`

- `Void WriteShort(Int32)`

- `Void WriteString(String)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Moments.Encoder
public class GifEncoder
{
	protected Int32 m_Width; // 0x10
	protected Int32 m_Height; // 0x14
	protected Int32 m_Repeat; // 0x18
	protected Int32 m_FrameDelay; // 0x1c
	protected Boolean m_HasStarted; // 0x20
	protected FileStream m_FileStream; // 0x28
	protected GifFrame m_CurrentFrame; // 0x30
	protected Byte[] m_Pixels; // 0x38
	protected Byte[] m_IndexedPixels; // 0x40
	protected Int32 m_ColorDepth; // 0x48
	protected Byte[] m_ColorTab; // 0x50
	protected Boolean[] m_UsedEntry; // 0x58
	protected Int32 m_PaletteSize; // 0x60
	protected Int32 m_DisposalCode; // 0x64
	protected Boolean m_ShouldCloseStream; // 0x68
	protected Boolean m_IsFirstFrame; // 0x69
	protected Boolean m_IsSizeSet; // 0x6a
	protected Int32 m_SampleInterval; // 0x6c


	// RVA: 0x66c01bc VA: 0x7598cd81bc
	public Void .ctor() { }
	// RVA: 0x66bf934 VA: 0x7598cd7934
	public Void .ctor(Int32 repeat, Int32 quality) { }
	// RVA: 0x66bf9f0 VA: 0x7598cd79f0
	public Void SetDelay(Int32 ms) { }
	// RVA: 0x66c01c8 VA: 0x7598cd81c8
	public Void SetFrameRate(Single fps) { }
	// RVA: 0x66bfea0 VA: 0x7598cd7ea0
	public Void AddFrame(GifFrame frame) { }
	// RVA: 0x66c0ab8 VA: 0x7598cd8ab8
	public Void Start(FileStream os) { }
	// RVA: 0x66bfd74 VA: 0x7598cd7d74
	public Void Start(String file) { }
	// RVA: 0x66bffc8 VA: 0x7598cd7fc8
	public Void Finish() { }
	// RVA: 0x66c02c0 VA: 0x7598cd82c0
	protected Void SetSize(Int32 w, Int32 h) { }
	// RVA: 0x66c02d0 VA: 0x7598cd82d0
	protected Void GetImagePixels() { }
	// RVA: 0x66c0410 VA: 0x7598cd8410
	protected Void AnalyzePixels() { }
	// RVA: 0x66c0834 VA: 0x7598cd8834
	protected Void WriteGraphicCtrlExt() { }
	// RVA: 0x66c0958 VA: 0x7598cd8958
	protected Void WriteImageDesc() { }
	// RVA: 0x66c05dc VA: 0x7598cd85dc
	protected Void WriteLSD() { }
	// RVA: 0x66c0734 VA: 0x7598cd8734
	protected Void WriteNetscapeExt() { }
	// RVA: 0x66c06ac VA: 0x7598cd86ac
	protected Void WritePalette() { }
	// RVA: 0x66c0a40 VA: 0x7598cd8a40
	protected Void WritePixels() { }
	// RVA: 0x66c117c VA: 0x7598cd917c
	protected Void WriteShort(Int32 value) { }
	// RVA: 0x66c0be8 VA: 0x7598cd8be8
	protected Void WriteString(String s) { }
}
```