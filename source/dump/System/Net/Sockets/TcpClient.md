# TcpClient

**Namespace:** `System.Net.Sockets`


## Fields

- `Socket m_ClientSocket`

- `Boolean m_Active`

- `NetworkStream m_DataStream`

- `AddressFamily m_Family`

- `Boolean m_CleanedUp`


## Properties

- `Socket Client`


## Methods

- `Socket get_Client()`

- `Void set_Client(Socket)`

- `Void Connect(String, Int32)`

- `Void Connect(IPEndPoint)`

- `IAsyncResult BeginConnect(String, Int32, AsyncCallback, Object)`

- `Void EndConnect(IAsyncResult)`

- `Task ConnectAsync(String, Int32)`

- `NetworkStream GetStream()`

- `Void Dispose()`

- `Void initialize()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net.Sockets
public class TcpClient : IDisposable
{
	private Socket m_ClientSocket; // 0x10
	private Boolean m_Active; // 0x18
	private NetworkStream m_DataStream; // 0x20
	private AddressFamily m_Family; // 0x28
	private Boolean m_CleanedUp; // 0x2c

	public Socket Client { get; set; }

	// RVA: 0x63601f4 VA: 0x75989781f4
	public Void .ctor() { }
	// RVA: 0x6360214 VA: 0x7598978214
	public Void .ctor(AddressFamily family) { }
	// RVA: 0x63603a4 VA: 0x75989783a4
	public Socket get_Client() { }
	// RVA: 0x63603ac VA: 0x75989783ac
	public Void set_Client(Socket value) { }
	// RVA: 0x63603b4 VA: 0x75989783b4
	public Void Connect(String hostname, Int32 port) { }
	// RVA: 0x6360a9c VA: 0x7598978a9c
	public Void Connect(IPEndPoint remoteEP) { }
	// RVA: 0x6360ba8 VA: 0x7598978ba8
	public IAsyncResult BeginConnect(String host, Int32 port, AsyncCallback requestCallback, Object state) { }
	// RVA: 0x6360c14 VA: 0x7598978c14
	public Void EndConnect(IAsyncResult asyncResult) { }
	// RVA: 0x6360c5c VA: 0x7598978c5c
	public Task ConnectAsync(String host, Int32 port) { }
	// RVA: 0x6360dc8 VA: 0x7598978dc8
	public NetworkStream GetStream() { }
	// RVA: 0x6360f20 VA: 0x7598978f20
	protected virtual Void Dispose(Boolean disposing) { }
	// RVA: 0x63610e8 VA: 0x75989790e8
	public Void Dispose() { }
	// RVA: 0x63610f8 VA: 0x75989790f8
	protected override Void Finalize() { }
	// RVA: 0x6360324 VA: 0x7598978324
	private Void initialize() { }
}
```