# SocketException

**Namespace:** `System.Net.Sockets`


## Fields

- `EndPoint m_EndPoint`


## Properties

- `SocketError SocketErrorCode`


## Methods

- `SocketError get_SocketErrorCode()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net.Sockets
public class SocketException : Win32Exception
{
	private EndPoint m_EndPoint; // 0x90

	public override String Message { get; }
	public SocketError SocketErrorCode { get; }

	// RVA: 0x6360008 VA: 0x7598978008
	private static Int32 WSAGetLastError_icall() { }
	// RVA: 0x636000c VA: 0x759897800c
	public Void .ctor() { }
	// RVA: 0x636002c VA: 0x759897802c
	internal Void .ctor(Int32 error, String message) { }
	// RVA: 0x635c5c8 VA: 0x75989745c8
	public Void .ctor(Int32 errorCode) { }
	// RVA: 0x635f788 VA: 0x7598977788
	internal Void .ctor(SocketError socketError) { }
	// RVA: 0x6360034 VA: 0x7598978034
	protected Void .ctor(SerializationInfo serializationInfo, StreamingContext streamingContext) { }
	// RVA: 0x636003c VA: 0x759897803c
	public override String get_Message() { }
	// RVA: 0x635ddb0 VA: 0x7598975db0
	public SocketError get_SocketErrorCode() { }
}
```