# FileWebRequest

**Namespace:** `System.Net`


## Fields

- `String m_connectionGroupName`

- `Int64 m_contentLength`

- `ICredentials m_credentials`

- `FileAccess m_fileAccess`

- `WebHeaderCollection m_headers`

- `String m_method`

- `IWebProxy m_proxy`

- `ManualResetEvent m_readerEvent`

- `Boolean m_readPending`

- `WebResponse m_response`

- `Stream m_stream`

- `Boolean m_syncHint`

- `Int32 m_timeout`

- `Uri m_uri`

- `Boolean m_writePending`

- `Boolean m_writing`

- `LazyAsyncResult m_WriteAResult`

- `LazyAsyncResult m_ReadAResult`

- `Int32 m_Aborted`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
public class FileWebRequest : WebRequest, ISerializable
{
	private static WaitCallback s_GetRequestStreamCallback; // 0x0
	private static WaitCallback s_GetResponseCallback; // 0x8
	private String m_connectionGroupName; // 0x38
	private Int64 m_contentLength; // 0x40
	private ICredentials m_credentials; // 0x48
	private FileAccess m_fileAccess; // 0x50
	private WebHeaderCollection m_headers; // 0x58
	private String m_method; // 0x60
	private IWebProxy m_proxy; // 0x68
	private ManualResetEvent m_readerEvent; // 0x70
	private Boolean m_readPending; // 0x78
	private WebResponse m_response; // 0x80
	private Stream m_stream; // 0x88
	private Boolean m_syncHint; // 0x90
	private Int32 m_timeout; // 0x94
	private Uri m_uri; // 0x98
	private Boolean m_writePending; // 0xa0
	private Boolean m_writing; // 0xa1
	private LazyAsyncResult m_WriteAResult; // 0xa8
	private LazyAsyncResult m_ReadAResult; // 0xb0
	private Int32 m_Aborted; // 0xb8

	internal Boolean Aborted { get; }
	public override Int64 ContentLength { get; set; }
	public override String ContentType { get; set; }
	public override ICredentials Credentials { get; set; }
	public override WebHeaderCollection Headers { get; }
	public override String Method { get; set; }
	public override IWebProxy Proxy { get; set; }
	public override Int32 Timeout { get; }
	public override Uri RequestUri { get; }
	public override Boolean UseDefaultCredentials { get; }

	// RVA: 0x643eb9c VA: 0x7598a56b9c
	internal Void .ctor(Uri uri) { }
	// RVA: 0x643ed38 VA: 0x7598a56d38
	protected Void .ctor(SerializationInfo serializationInfo, StreamingContext streamingContext) { }
	// RVA: 0x643f154 VA: 0x7598a57154
	private Void System.Runtime.Serialization.ISerializable.GetObjectData(SerializationInfo serializationInfo, StreamingContext streamingContext) { }
	// RVA: 0x643f160 VA: 0x7598a57160
	protected override Void GetObjectData(SerializationInfo serializationInfo, StreamingContext streamingContext) { }
	// RVA: 0x643f3f0 VA: 0x7598a573f0
	internal Boolean get_Aborted() { }
	// RVA: 0x643f400 VA: 0x7598a57400
	public override Int64 get_ContentLength() { }
	// RVA: 0x643f408 VA: 0x7598a57408
	public override Void set_ContentLength(Int64 value) { }
	// RVA: 0x643f48c VA: 0x7598a5748c
	public override String get_ContentType() { }
	// RVA: 0x643f4e0 VA: 0x7598a574e0
	public override Void set_ContentType(String value) { }
	// RVA: 0x643f53c VA: 0x7598a5753c
	public override ICredentials get_Credentials() { }
	// RVA: 0x643f544 VA: 0x7598a57544
	public override Void set_Credentials(ICredentials value) { }
	// RVA: 0x643f54c VA: 0x7598a5754c
	public override WebHeaderCollection get_Headers() { }
	// RVA: 0x643f554 VA: 0x7598a57554
	public override String get_Method() { }
	// RVA: 0x643f55c VA: 0x7598a5755c
	public override Void set_Method(String value) { }
	// RVA: 0x643f638 VA: 0x7598a57638
	public override IWebProxy get_Proxy() { }
	// RVA: 0x643f640 VA: 0x7598a57640
	public override Void set_Proxy(IWebProxy value) { }
	// RVA: 0x643f648 VA: 0x7598a57648
	public override Int32 get_Timeout() { }
	// RVA: 0x643f650 VA: 0x7598a57650
	public override Uri get_RequestUri() { }
	// RVA: 0x643f658 VA: 0x7598a57658
	public override IAsyncResult BeginGetResponse(AsyncCallback callback, Object state) { }
	// RVA: 0x643f93c VA: 0x7598a5793c
	public override WebResponse EndGetResponse(IAsyncResult asyncResult) { }
	// RVA: 0x643fc38 VA: 0x7598a57c38
	public override WebResponse GetResponse() { }
	// RVA: 0x643ffa0 VA: 0x7598a57fa0
	private static Void GetRequestStreamCallback(Object state) { }
	// RVA: 0x644027c VA: 0x7598a5827c
	private static Void GetResponseCallback(Object state) { }
	// RVA: 0x64408dc VA: 0x7598a588dc
	internal Void UnblockReader() { }
	// RVA: 0x64409b4 VA: 0x7598a589b4
	public override Boolean get_UseDefaultCredentials() { }
	// RVA: 0x64409d8 VA: 0x7598a589d8
	public override Void Abort() { }
	// RVA: 0x6440d7c VA: 0x7598a58d7c
	private static Void .cctor() { }
}
```