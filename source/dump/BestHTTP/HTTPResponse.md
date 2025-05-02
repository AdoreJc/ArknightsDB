# HTTPResponse

**Namespace:** `BestHTTP`


## Fields

- `Int32 <VersionMajor>k__BackingField`

- `Int32 <VersionMinor>k__BackingField`

- `Int32 <StatusCode>k__BackingField`

- `String <Message>k__BackingField`

- `Boolean <IsStreamed>k__BackingField`

- `Boolean <IsStreamingFinished>k__BackingField`

- `Boolean <IsFromCache>k__BackingField`

- `HTTPCacheFileInfo <CacheFileInfo>k__BackingField`

- `Boolean <IsCacheOnly>k__BackingField`

- `Boolean <IsUpgraded>k__BackingField`

- `String dataAsText`

- `Texture2D texture`

- `Boolean <IsClosedManually>k__BackingField`

- `Stream Stream`

- `Object SyncRoot`

- `Int32 fragmentBufferDataLength`

- `Stream cacheStream`

- `Int32 allFragmentSize`

- `MemoryStream decompressorInputStream`

- `MemoryStream decompressorOutputStream`

- `GZipStream decompressorGZipStream`


## Properties

- `Int32 VersionMajor`

- `Int32 VersionMinor`

- `Int32 StatusCode`

- `Boolean IsSuccess`

- `String Message`

- `Boolean IsStreamed`

- `Boolean IsStreamingFinished`

- `Boolean IsFromCache`

- `HTTPCacheFileInfo CacheFileInfo`

- `Boolean IsCacheOnly`

- `Boolean IsUpgraded`

- `String DataAsText`

- `Texture2D DataAsTexture2D`

- `Boolean IsClosedManually`


## Methods

- `Int32 get_VersionMajor()`

- `Void set_VersionMajor(Int32)`

- `Int32 get_VersionMinor()`

- `Void set_VersionMinor(Int32)`

- `Int32 get_StatusCode()`

- `Void set_StatusCode(Int32)`

- `Boolean get_IsSuccess()`

- `String get_Message()`

- `Void set_Message(String)`

- `Boolean get_IsStreamed()`

- `Void set_IsStreamed(Boolean)`

- `Boolean get_IsStreamingFinished()`

- `Boolean get_IsFromCache()`

- `HTTPCacheFileInfo get_CacheFileInfo()`

- `Boolean get_IsCacheOnly()`

- `Void set_IsCacheOnly(Boolean)`

- `Void set_Headers(Dictionary`2)`

- `Boolean get_IsUpgraded()`

- `Void set_IsUpgraded(Boolean)`

- `String get_DataAsText()`

- `Texture2D get_DataAsTexture2D()`

- `Boolean get_IsClosedManually()`

- `Void set_IsClosedManually(Boolean)`

- `Boolean ReadPayload(Int32)`

- `Void ReadHeaders(Stream)`

- `Void AddHeader(String, String)`

- `String GetFirstHeaderValue(String)`

- `Boolean HasHeaderWithValue(String, String)`

- `Boolean HasHeader(String)`

- `HTTPRange GetRange()`

- `Int32 ReadChunkLength(Stream)`

- `Void ReadChunked(Stream)`

- `Void ReadUnknownSize(Stream)`

- `Void BeginReceiveStreamFragments()`

- `Void FeedStreamFragment(Byte[], Int32, Int32)`

- `Void FlushRemainingFragmentBuffer()`

- `Void AddStreamedFragment(Byte[])`

- `Void WaitWhileHasFragments()`

- `Void VerboseLogging(String)`

- `Void Dispose()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : BestHTTP
public class HTTPResponse : IDisposable
{
	internal const Byte CR; // 0x0
	internal const Byte LF; // 0x0
	public const Int32 MinBufferSize; // 0x0
	private Int32 <VersionMajor>k__BackingField; // 0x10
	private Int32 <VersionMinor>k__BackingField; // 0x14
	private Int32 <StatusCode>k__BackingField; // 0x18
	private String <Message>k__BackingField; // 0x20
	private Boolean <IsStreamed>k__BackingField; // 0x28
	private Boolean <IsStreamingFinished>k__BackingField; // 0x29
	private Boolean <IsFromCache>k__BackingField; // 0x2a
	private HTTPCacheFileInfo <CacheFileInfo>k__BackingField; // 0x30
	private Boolean <IsCacheOnly>k__BackingField; // 0x38
	private Dictionary`2 <Headers>k__BackingField; // 0x40
	private Byte[] <Data>k__BackingField; // 0x48
	private Boolean <IsUpgraded>k__BackingField; // 0x50
	private List`1 <Cookies>k__BackingField; // 0x58
	protected String dataAsText; // 0x60
	protected Texture2D texture; // 0x68
	private Boolean <IsClosedManually>k__BackingField; // 0x70
	internal HTTPRequest baseRequest; // 0x78
	protected Stream Stream; // 0x80
	protected List`1 streamedFragments; // 0x88
	protected Object SyncRoot; // 0x90
	protected Byte[] fragmentBuffer; // 0x98
	protected Int32 fragmentBufferDataLength; // 0xa0
	protected Stream cacheStream; // 0xa8
	protected Int32 allFragmentSize; // 0xb0
	private MemoryStream decompressorInputStream; // 0xb8
	private MemoryStream decompressorOutputStream; // 0xc0
	private GZipStream decompressorGZipStream; // 0xc8
	private Byte[] copyBuffer; // 0xd0

	public Int32 VersionMajor { get; set; }
	public Int32 VersionMinor { get; set; }
	public Int32 StatusCode { get; set; }
	public Boolean IsSuccess { get; }
	public String Message { get; set; }
	public Boolean IsStreamed { get; set; }
	public Boolean IsStreamingFinished { get; set; }
	public Boolean IsFromCache { get; set; }
	public HTTPCacheFileInfo CacheFileInfo { get; set; }
	public Boolean IsCacheOnly { get; set; }
	public Dictionary`2 Headers { get; set; }
	public Byte[] Data { get; set; }
	public Boolean IsUpgraded { get; set; }
	public List`1 Cookies { get; set; }
	public String DataAsText { get; }
	public Texture2D DataAsTexture2D { get; }
	public Boolean IsClosedManually { get; set; }

	// RVA: 0x6605ce8 VA: 0x7598c1dce8
	public Int32 get_VersionMajor() { }
	// RVA: 0x6605cf0 VA: 0x7598c1dcf0
	protected Void set_VersionMajor(Int32 value) { }
	// RVA: 0x6605cf8 VA: 0x7598c1dcf8
	public Int32 get_VersionMinor() { }
	// RVA: 0x6605d00 VA: 0x7598c1dd00
	protected Void set_VersionMinor(Int32 value) { }
	// RVA: 0x6605d08 VA: 0x7598c1dd08
	public Int32 get_StatusCode() { }
	// RVA: 0x6605d10 VA: 0x7598c1dd10
	protected Void set_StatusCode(Int32 value) { }
	// RVA: 0x6605d18 VA: 0x7598c1dd18
	public Boolean get_IsSuccess() { }
	// RVA: 0x6605d38 VA: 0x7598c1dd38
	public String get_Message() { }
	// RVA: 0x6605d40 VA: 0x7598c1dd40
	protected Void set_Message(String value) { }
	// RVA: 0x6605d48 VA: 0x7598c1dd48
	public Boolean get_IsStreamed() { }
	// RVA: 0x6605d50 VA: 0x7598c1dd50
	protected Void set_IsStreamed(Boolean value) { }
	// RVA: 0x6605d5c VA: 0x7598c1dd5c
	public Boolean get_IsStreamingFinished() { }
	// RVA: 0x6605d64 VA: 0x7598c1dd64
	internal Void set_IsStreamingFinished(Boolean value) { }
	// RVA: 0x6605d70 VA: 0x7598c1dd70
	public Boolean get_IsFromCache() { }
	// RVA: 0x6605d78 VA: 0x7598c1dd78
	internal Void set_IsFromCache(Boolean value) { }
	// RVA: 0x6605d84 VA: 0x7598c1dd84
	public HTTPCacheFileInfo get_CacheFileInfo() { }
	// RVA: 0x6605d8c VA: 0x7598c1dd8c
	internal Void set_CacheFileInfo(HTTPCacheFileInfo value) { }
	// RVA: 0x6605d94 VA: 0x7598c1dd94
	public Boolean get_IsCacheOnly() { }
	// RVA: 0x6605d9c VA: 0x7598c1dd9c
	private Void set_IsCacheOnly(Boolean value) { }
	// RVA: 0x6605da8 VA: 0x7598c1dda8
	public Dictionary`2 get_Headers() { }
	// RVA: 0x6605db0 VA: 0x7598c1ddb0
	protected Void set_Headers(Dictionary`2 value) { }
	// RVA: 0x6605db8 VA: 0x7598c1ddb8
	public Byte[] get_Data() { }
	// RVA: 0x6605dc0 VA: 0x7598c1ddc0
	internal Void set_Data(Byte[] value) { }
	// RVA: 0x6605dc8 VA: 0x7598c1ddc8
	public Boolean get_IsUpgraded() { }
	// RVA: 0x6605dd0 VA: 0x7598c1ddd0
	protected Void set_IsUpgraded(Boolean value) { }
	// RVA: 0x6605ddc VA: 0x7598c1dddc
	public List`1 get_Cookies() { }
	// RVA: 0x6605de4 VA: 0x7598c1dde4
	internal Void set_Cookies(List`1 value) { }
	// RVA: 0x6605dec VA: 0x7598c1ddec
	public String get_DataAsText() { }
	// RVA: 0x6605ea8 VA: 0x7598c1dea8
	public Texture2D get_DataAsTexture2D() { }
	// RVA: 0x6605f88 VA: 0x7598c1df88
	public Boolean get_IsClosedManually() { }
	// RVA: 0x6605f90 VA: 0x7598c1df90
	protected Void set_IsClosedManually(Boolean value) { }
	// RVA: 0x6605f9c VA: 0x7598c1df9c
	internal Void .ctor(HTTPRequest request, Stream stream, Boolean isStreamed, Boolean isFromCache) { }
	// RVA: 0x6606078 VA: 0x7598c1e078
	internal virtual Boolean Receive(Int32 forceReadRawContentLength, Boolean readPayloadData) { }
	// RVA: 0x6607368 VA: 0x7598c1f368
	protected Boolean ReadPayload(Int32 forceReadRawContentLength) { }
	// RVA: 0x66070cc VA: 0x7598c1f0cc
	protected Void ReadHeaders(Stream stream) { }
	// RVA: 0x6609074 VA: 0x7598c21074
	protected Void AddHeader(String name, String value) { }
	// RVA: 0x6608500 VA: 0x7598c20500
	public List`1 GetHeaderValues(String name) { }
	// RVA: 0x660924c VA: 0x7598c2124c
	public String GetFirstHeaderValue(String name) { }
	// RVA: 0x6607290 VA: 0x7598c1f290
	public Boolean HasHeaderWithValue(String headerName, String value) { }
	// RVA: 0x6607350 VA: 0x7598c1f350
	public Boolean HasHeader(String headerName) { }
	// RVA: 0x66085b4 VA: 0x7598c205b4
	public HTTPRange GetRange() { }
	// RVA: 0x6606c68 VA: 0x7598c1ec68
	public static String ReadTo(Stream stream, Byte blocker) { }
	// RVA: 0x6608e30 VA: 0x7598c20e30
	public static String ReadTo(Stream stream, Byte blocker1, Byte blocker2) { }
	// RVA: 0x6606e9c VA: 0x7598c1ee9c
	public static String NoTrimReadTo(Stream stream, Byte blocker1, Byte blocker2) { }
	// RVA: 0x66093e8 VA: 0x7598c213e8
	protected Int32 ReadChunkLength(Stream stream) { }
	// RVA: 0x6607c8c VA: 0x7598c1fc8c
	protected Void ReadChunked(Stream stream) { }
	// RVA: 0x6607640 VA: 0x7598c1f640
	internal Void ReadRaw(Stream stream, Int64 contentLength) { }
	// RVA: 0x66087d0 VA: 0x7598c207d0
	protected Void ReadUnknownSize(Stream stream) { }
	// RVA: 0x6609af8 VA: 0x7598c21af8
	protected Byte[] DecodeStream(MemoryStream streamToDecode) { }
	// RVA: 0x6609668 VA: 0x7598c21668
	private Byte[] Decompress(Byte[] data, Int32 offset, Int32 count) { }
	// RVA: 0x66094b4 VA: 0x7598c214b4
	protected Void BeginReceiveStreamFragments() { }
	// RVA: 0x66098c4 VA: 0x7598c218c4
	protected Void FeedStreamFragment(Byte[] buffer, Int32 pos, Int32 length) { }
	// RVA: 0x66099fc VA: 0x7598c219fc
	protected Void FlushRemainingFragmentBuffer() { }
	// RVA: 0x6609e80 VA: 0x7598c21e80
	protected Void AddStreamedFragment(Byte[] buffer) { }
	// RVA: 0x6609624 VA: 0x7598c21624
	protected Void WaitWhileHasFragments() { }
	// RVA: 0x660a2ec VA: 0x7598c222ec
	public List`1 GetStreamedFragments() { }
	// RVA: 0x660a1f4 VA: 0x7598c221f4
	internal Boolean HasStreamedFragments() { }
	// RVA: 0x660a62c VA: 0x7598c2262c
	internal Void FinishStreaming() { }
	// RVA: 0x6606b00 VA: 0x7598c1eb00
	private Void VerboseLogging(String str) { }
	// RVA: 0x660a730 VA: 0x7598c22730
	public Void Dispose() { }
}
```