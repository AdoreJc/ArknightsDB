# HLSStream

**Namespace:** `RenderHeads.Media.AVProVideo`


## Fields

- `String _streamURL`

- `Int32 _width`

- `Int32 _height`

- `Int32 _bandwidth`


## Methods

- `Boolean ExtractStreamInfo(String, ref, ref, ref)`

- `Void ParseFile(String[], String)`

- `Boolean MyRemoteCertificateValidationCallback(Object, X509Certificate, X509Chain, SslPolicyErrors)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : RenderHeads.Media.AVProVideo
public class HLSStream : Stream
{
	private const String BANDWIDTH_NAME; // 0x0
	private const String RESOLUTION_NAME; // 0x0
	private const String CHUNK_TAG; // 0x0
	private const String STREAM_TAG; // 0x0
	private List`1 _streams; // 0x10
	private List`1 _chunks; // 0x18
	private String _streamURL; // 0x20
	private Int32 _width; // 0x28
	private Int32 _height; // 0x2c
	private Int32 _bandwidth; // 0x30

	public override Int32 Width { get; }
	public override Int32 Height { get; }
	public override Int32 Bandwidth { get; }
	public override String URL { get; }

	// RVA: 0x6691a6c VA: 0x7598ca9a6c
	public override Int32 get_Width() { }
	// RVA: 0x6691a74 VA: 0x7598ca9a74
	public override Int32 get_Height() { }
	// RVA: 0x6691a7c VA: 0x7598ca9a7c
	public override Int32 get_Bandwidth() { }
	// RVA: 0x6691a84 VA: 0x7598ca9a84
	public override String get_URL() { }
	// RVA: 0x6691a8c VA: 0x7598ca9a8c
	public override List`1 GetAllChunks() { }
	// RVA: 0x6691b9c VA: 0x7598ca9b9c
	public override List`1 GetChunks() { }
	// RVA: 0x6691ba4 VA: 0x7598ca9ba4
	public override List`1 GetAllStreams() { }
	// RVA: 0x6691cb4 VA: 0x7598ca9cb4
	public override List`1 GetStreams() { }
	// RVA: 0x6691cbc VA: 0x7598ca9cbc
	private Boolean ExtractStreamInfo(String line, ref Int32 width, ref Int32 height, ref Int32 bandwidth) { }
	// RVA: 0x6691ed4 VA: 0x7598ca9ed4
	private static Boolean IsChunk(String line) { }
	// RVA: 0x6691f28 VA: 0x7598ca9f28
	private Void ParseFile(String[] text, String path) { }
	// RVA: 0x6692474 VA: 0x7598caa474
	public Void .ctor(String filename, Int32 width, Int32 height, Int32 bandwidth) { }
	// RVA: 0x6692980 VA: 0x7598caa980
	private Boolean MyRemoteCertificateValidationCallback(Object sender, X509Certificate certificate, X509Chain chain, SslPolicyErrors sslPolicyErrors) { }
}
```