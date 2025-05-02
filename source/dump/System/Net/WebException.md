# WebException

**Namespace:** `System.Net`


## Fields

- `WebExceptionStatus m_Status`

- `WebResponse m_Response`

- `WebExceptionInternalStatus m_InternalStatus`


## Properties

- `WebExceptionStatus Status`

- `WebResponse Response`


## Methods

- `WebExceptionStatus get_Status()`

- `WebResponse get_Response()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
public class WebException : InvalidOperationException, ISerializable
{
	private WebExceptionStatus m_Status; // 0x8c
	private WebResponse m_Response; // 0x90
	private WebExceptionInternalStatus m_InternalStatus; // 0x98

	public WebExceptionStatus Status { get; }
	public WebResponse Response { get; }

	// RVA: 0x642b7c0 VA: 0x7598a437c0
	public Void .ctor() { }
	// RVA: 0x642a170 VA: 0x7598a42170
	public Void .ctor(String message) { }
	// RVA: 0x642b7d0 VA: 0x7598a437d0
	public Void .ctor(String message, Exception innerException) { }
	// RVA: 0x642a35c VA: 0x7598a4235c
	public Void .ctor(String message, WebExceptionStatus status) { }
	// RVA: 0x642b7f4 VA: 0x7598a437f4
	internal Void .ctor(String message, WebExceptionStatus status, WebExceptionInternalStatus internalStatus, Exception innerException) { }
	// RVA: 0x642b7e0 VA: 0x7598a437e0
	public Void .ctor(String message, Exception innerException, WebExceptionStatus status, WebResponse response) { }
	// RVA: 0x642b828 VA: 0x7598a43828
	internal Void .ctor(String message, String data, Exception innerException, WebExceptionStatus status, WebResponse response) { }
	// RVA: 0x642b810 VA: 0x7598a43810
	internal Void .ctor(String message, Exception innerException, WebExceptionStatus status, WebResponse response, WebExceptionInternalStatus internalStatus) { }
	// RVA: 0x642b910 VA: 0x7598a43910
	internal Void .ctor(String message, String data, Exception innerException, WebExceptionStatus status, WebResponse response, WebExceptionInternalStatus internalStatus) { }
	// RVA: 0x642ba0c VA: 0x7598a43a0c
	protected Void .ctor(SerializationInfo serializationInfo, StreamingContext streamingContext) { }
	// RVA: 0x642ba1c VA: 0x7598a43a1c
	private Void System.Runtime.Serialization.ISerializable.GetObjectData(SerializationInfo serializationInfo, StreamingContext streamingContext) { }
	// RVA: 0x642ba28 VA: 0x7598a43a28
	public override Void GetObjectData(SerializationInfo serializationInfo, StreamingContext streamingContext) { }
	// RVA: 0x642ba30 VA: 0x7598a43a30
	public WebExceptionStatus get_Status() { }
	// RVA: 0x642ba38 VA: 0x7598a43a38
	public WebResponse get_Response() { }
}
```