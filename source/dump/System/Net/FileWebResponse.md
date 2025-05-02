# FileWebResponse

**Namespace:** `System.Net`


## Fields

- `Boolean m_closed`

- `Int64 m_contentLength`

- `FileAccess m_fileAccess`

- `WebHeaderCollection m_headers`

- `Stream m_stream`

- `Uri m_uri`


## Methods

- `Void CheckDisposed()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
public class FileWebResponse : WebResponse, ISerializable, ICloseEx
{
	private Boolean m_closed; // 0x19
	private Int64 m_contentLength; // 0x20
	private FileAccess m_fileAccess; // 0x28
	private WebHeaderCollection m_headers; // 0x30
	private Stream m_stream; // 0x38
	private Uri m_uri; // 0x40

	public override Int64 ContentLength { get; }
	public override WebHeaderCollection Headers { get; }
	public override Uri ResponseUri { get; }

	// RVA: 0x64405bc VA: 0x7598a585bc
	internal Void .ctor(FileWebRequest request, Uri uri, FileAccess access, Boolean asyncHint) { }
	// RVA: 0x644157c VA: 0x7598a5957c
	protected Void .ctor(SerializationInfo serializationInfo, StreamingContext streamingContext) { }
	// RVA: 0x64417dc VA: 0x7598a597dc
	private Void System.Runtime.Serialization.ISerializable.GetObjectData(SerializationInfo serializationInfo, StreamingContext streamingContext) { }
	// RVA: 0x64417e8 VA: 0x7598a597e8
	protected override Void GetObjectData(SerializationInfo serializationInfo, StreamingContext streamingContext) { }
	// RVA: 0x6441978 VA: 0x7598a59978
	public override Int64 get_ContentLength() { }
	// RVA: 0x6441a14 VA: 0x7598a59a14
	public override WebHeaderCollection get_Headers() { }
	// RVA: 0x6441a2c VA: 0x7598a59a2c
	public override Uri get_ResponseUri() { }
	// RVA: 0x6441990 VA: 0x7598a59990
	private Void CheckDisposed() { }
	// RVA: 0x6441a44 VA: 0x7598a59a44
	public override Void Close() { }
	// RVA: 0x6441adc VA: 0x7598a59adc
	private Void System.Net.ICloseEx.CloseEx(CloseExState closeState) { }
	// RVA: 0x6441c58 VA: 0x7598a59c58
	public override Stream GetResponseStream() { }
}
```