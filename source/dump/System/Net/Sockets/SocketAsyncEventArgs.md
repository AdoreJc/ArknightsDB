# SocketAsyncEventArgs

**Namespace:** `System.Net.Sockets`


## Fields

- `Boolean disposed`

- `EndPoint remote_ep`

- `Socket current_socket`

- `Exception <ConnectByNameError>k__BackingField`

- `Socket <AcceptSocket>k__BackingField`

- `Int32 <BytesTransferred>k__BackingField`

- `Boolean <DisconnectReuseSocket>k__BackingField`

- `SocketAsyncOperation <LastOperation>k__BackingField`

- `IPPacketInformation <ReceiveMessageFromPacketInfo>k__BackingField`

- `TransmitFileOptions <SendPacketsFlags>k__BackingField`

- `Int32 <SendPacketsSendSize>k__BackingField`

- `SocketError <SocketError>k__BackingField`

- `SocketFlags <SocketFlags>k__BackingField`

- `Object <UserToken>k__BackingField`

- `Int32 _offset`

- `Int32 _count`

- `Boolean _bufferIsExplicitArray`


## Properties

- `Exception ConnectByNameError`

- `Socket AcceptSocket`

- `Int32 BytesTransferred`

- `SocketAsyncOperation LastOperation`

- `EndPoint RemoteEndPoint`

- `Int32 SendPacketsSendSize`

- `SocketError SocketError`

- `SocketFlags SocketFlags`

- `Object UserToken`

- `Int32 Offset`

- `Int32 Count`


## Methods

- `Void set_ConnectByNameError(Exception)`

- `Socket get_AcceptSocket()`

- `Void set_AcceptSocket(Socket)`

- `Int32 get_BytesTransferred()`

- `Void set_BytesTransferred(Int32)`

- `Void set_LastOperation(SocketAsyncOperation)`

- `EndPoint get_RemoteEndPoint()`

- `Void set_RemoteEndPoint(EndPoint)`

- `Void set_SendPacketsSendSize(Int32)`

- `SocketError get_SocketError()`

- `Void set_SocketError(SocketError)`

- `Void set_SocketFlags(SocketFlags)`

- `Object get_UserToken()`

- `Void set_UserToken(Object)`

- `Void add_Completed(EventHandler`1)`

- `Void remove_Completed(EventHandler`1)`

- `Void Dispose(Boolean)`

- `Void Dispose()`

- `Int32 get_Offset()`

- `Int32 get_Count()`

- `Void SetBuffer(Byte[], Int32, Int32)`

- `Void SetBuffer(Memory`1)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net.Sockets
public class SocketAsyncEventArgs : EventArgs, IDisposable
{
	private Boolean disposed; // 0x10
	internal Int32 in_progress; // 0x14
	private EndPoint remote_ep; // 0x18
	private Socket current_socket; // 0x20
	internal SocketAsyncResult socket_async_result; // 0x28
	private Exception <ConnectByNameError>k__BackingField; // 0x30
	private Socket <AcceptSocket>k__BackingField; // 0x38
	private Int32 <BytesTransferred>k__BackingField; // 0x40
	private Boolean <DisconnectReuseSocket>k__BackingField; // 0x44
	private SocketAsyncOperation <LastOperation>k__BackingField; // 0x48
	private IPPacketInformation <ReceiveMessageFromPacketInfo>k__BackingField; // 0x50
	private SendPacketsElement[] <SendPacketsElements>k__BackingField; // 0x60
	private TransmitFileOptions <SendPacketsFlags>k__BackingField; // 0x68
	private Int32 <SendPacketsSendSize>k__BackingField; // 0x6c
	private SocketError <SocketError>k__BackingField; // 0x70
	private SocketFlags <SocketFlags>k__BackingField; // 0x74
	private Object <UserToken>k__BackingField; // 0x78
	private EventHandler`1 Completed; // 0x80
	private Memory`1 _buffer; // 0x88
	private Int32 _offset; // 0x98
	private Int32 _count; // 0x9c
	private Boolean _bufferIsExplicitArray; // 0xa0
	private IList`1 _bufferList; // 0xa8
	private List`1 _bufferListInternal; // 0xb0

	private Exception ConnectByNameError { set; }
	public Socket AcceptSocket { get; set; }
	public Int32 BytesTransferred { get; set; }
	private SocketAsyncOperation LastOperation { set; }
	public EndPoint RemoteEndPoint { get; set; }
	public Int32 SendPacketsSendSize { set; }
	public SocketError SocketError { get; set; }
	public SocketFlags SocketFlags { set; }
	public Object UserToken { get; set; }
	internal Socket CurrentSocket { get; }
	public Byte[] Buffer { get; }
	public Memory`1 MemoryBuffer { get; }
	public Int32 Offset { get; }
	public Int32 Count { get; }
	public IList`1 BufferList { get; }

	// RVA: 0x6361c14 VA: 0x7598979c14
	private Void set_ConnectByNameError(Exception value) { }
	// RVA: 0x6361c1c VA: 0x7598979c1c
	public Socket get_AcceptSocket() { }
	// RVA: 0x6361c24 VA: 0x7598979c24
	public Void set_AcceptSocket(Socket value) { }
	// RVA: 0x6361c2c VA: 0x7598979c2c
	public Int32 get_BytesTransferred() { }
	// RVA: 0x6361c34 VA: 0x7598979c34
	private Void set_BytesTransferred(Int32 value) { }
	// RVA: 0x6361c3c VA: 0x7598979c3c
	private Void set_LastOperation(SocketAsyncOperation value) { }
	// RVA: 0x6361c44 VA: 0x7598979c44
	public EndPoint get_RemoteEndPoint() { }
	// RVA: 0x6361c4c VA: 0x7598979c4c
	public Void set_RemoteEndPoint(EndPoint value) { }
	// RVA: 0x6361c54 VA: 0x7598979c54
	public Void set_SendPacketsSendSize(Int32 value) { }
	// RVA: 0x6361c5c VA: 0x7598979c5c
	public SocketError get_SocketError() { }
	// RVA: 0x6361c64 VA: 0x7598979c64
	public Void set_SocketError(SocketError value) { }
	// RVA: 0x6361c6c VA: 0x7598979c6c
	public Void set_SocketFlags(SocketFlags value) { }
	// RVA: 0x6361c74 VA: 0x7598979c74
	public Object get_UserToken() { }
	// RVA: 0x6361c7c VA: 0x7598979c7c
	public Void set_UserToken(Object value) { }
	// RVA: 0x6361c84 VA: 0x7598979c84
	public Void add_Completed(EventHandler`1 value) { }
	// RVA: 0x6361d34 VA: 0x7598979d34
	public Void remove_Completed(EventHandler`1 value) { }
	// RVA: 0x6361de4 VA: 0x7598979de4
	public Void .ctor() { }
	// RVA: 0x635b748 VA: 0x7598973748
	internal Void .ctor(Boolean flowExecutionContext) { }
	// RVA: 0x6361e90 VA: 0x7598979e90
	protected override Void Finalize() { }
	// RVA: 0x6361ea0 VA: 0x7598979ea0
	private Void Dispose(Boolean disposing) { }
	// RVA: 0x6361eb4 VA: 0x7598979eb4
	public Void Dispose() { }
	// RVA: 0x6361f18 VA: 0x7598979f18
	internal Void SetConnectByNameError(Exception error) { }
	// RVA: 0x635ef50 VA: 0x7598976f50
	internal Void SetBytesTransferred(Int32 value) { }
	// RVA: 0x6361f20 VA: 0x7598979f20
	internal Socket get_CurrentSocket() { }
	// RVA: 0x6361f28 VA: 0x7598979f28
	internal Void SetCurrentSocket(Socket socket) { }
	// RVA: 0x6361f30 VA: 0x7598979f30
	internal Void SetLastOperation(SocketAsyncOperation op) { }
	// RVA: 0x6361ff8 VA: 0x7598979ff8
	internal Void Complete_internal() { }
	// RVA: 0x6362020 VA: 0x759897a020
	protected virtual Void OnCompleted(SocketAsyncEventArgs e) { }
	// RVA: 0x6362048 VA: 0x759897a048
	public Byte[] get_Buffer() { }
	// RVA: 0x6362104 VA: 0x759897a104
	public Memory`1 get_MemoryBuffer() { }
	// RVA: 0x6362110 VA: 0x759897a110
	public Int32 get_Offset() { }
	// RVA: 0x6362118 VA: 0x759897a118
	public Int32 get_Count() { }
	// RVA: 0x6362120 VA: 0x759897a120
	public IList`1 get_BufferList() { }
	// RVA: 0x6362128 VA: 0x759897a128
	public Void SetBuffer(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x63622c4 VA: 0x759897a2c4
	public Void SetBuffer(Memory`1 buffer) { }
}
```