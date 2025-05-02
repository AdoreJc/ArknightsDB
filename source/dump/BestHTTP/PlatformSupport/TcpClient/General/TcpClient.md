# TcpClient

**Namespace:** `BestHTTP.PlatformSupport.TcpClient.General`


## Fields

- `NetworkStream stream`

- `Boolean active`

- `Socket client`

- `Boolean disposed`

- `Properties values`

- `Int32 recv_timeout`

- `Int32 send_timeout`

- `Int32 recv_buffer_size`

- `Int32 send_buffer_size`

- `LingerOption linger_state`

- `Boolean no_delay`

- `TimeSpan <ConnectTimeout>k__BackingField`


## Properties

- `Boolean Active`

- `Socket Client`

- `Int32 Available`

- `Boolean Connected`

- `Boolean ExclusiveAddressUse`

- `LingerOption LingerState`

- `Boolean NoDelay`

- `Int32 ReceiveBufferSize`

- `Int32 ReceiveTimeout`

- `Int32 SendBufferSize`

- `Int32 SendTimeout`

- `TimeSpan ConnectTimeout`


## Methods

- `Void Init(AddressFamily)`

- `Boolean get_Active()`

- `Void set_Active(Boolean)`

- `Socket get_Client()`

- `Void set_Client(Socket)`

- `Int32 get_Available()`

- `Boolean get_Connected()`

- `Boolean IsConnected()`

- `Boolean get_ExclusiveAddressUse()`

- `Void set_ExclusiveAddressUse(Boolean)`

- `LingerOption get_LingerState()`

- `Void set_LingerState(LingerOption)`

- `Boolean get_NoDelay()`

- `Void set_NoDelay(Boolean)`

- `Int32 get_ReceiveBufferSize()`

- `Void set_ReceiveBufferSize(Int32)`

- `Int32 get_ReceiveTimeout()`

- `Void set_ReceiveTimeout(Int32)`

- `Int32 get_SendBufferSize()`

- `Void set_SendBufferSize(Int32)`

- `Int32 get_SendTimeout()`

- `Void set_SendTimeout(Int32)`

- `TimeSpan get_ConnectTimeout()`

- `Void set_ConnectTimeout(TimeSpan)`

- `Void Close()`

- `Void Connect(IPEndPoint)`

- `Void Connect(IPAddress, Int32)`

- `Void SetOptions()`

- `Void Connect(String, Int32)`

- `Void Connect(IPAddress[], Int32)`

- `Void EndConnect(IAsyncResult)`

- `IAsyncResult BeginConnect(IPAddress, Int32, AsyncCallback, Object)`

- `IAsyncResult BeginConnect(IPAddress[], Int32, AsyncCallback, Object)`

- `IAsyncResult BeginConnect(String, Int32, AsyncCallback, Object)`

- `Stream GetStream()`

- `Void CheckDisposed()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : BestHTTP.PlatformSupport.TcpClient.General
public class TcpClient : IDisposable
{
	private NetworkStream stream; // 0x10
	private Boolean active; // 0x18
	private Socket client; // 0x20
	private Boolean disposed; // 0x28
	private Properties values; // 0x2c
	private Int32 recv_timeout; // 0x30
	private Int32 send_timeout; // 0x34
	private Int32 recv_buffer_size; // 0x38
	private Int32 send_buffer_size; // 0x3c
	private LingerOption linger_state; // 0x40
	private Boolean no_delay; // 0x48
	private TimeSpan <ConnectTimeout>k__BackingField; // 0x50
	private const String SHIELD_HOST_FLAG; // 0x0
	private const String SHIELD_TARGET_IP; // 0x0

	protected Boolean Active { get; set; }
	public Socket Client { get; set; }
	public Int32 Available { get; }
	public Boolean Connected { get; }
	public Boolean ExclusiveAddressUse { get; set; }
	public LingerOption LingerState { get; set; }
	public Boolean NoDelay { get; set; }
	public Int32 ReceiveBufferSize { get; set; }
	public Int32 ReceiveTimeout { get; set; }
	public Int32 SendBufferSize { get; set; }
	public Int32 SendTimeout { get; set; }
	public TimeSpan ConnectTimeout { get; set; }

	// RVA: 0x6616fc4 VA: 0x7598c2efc4
	private Void Init(AddressFamily family) { }
	// RVA: 0x6617060 VA: 0x7598c2f060
	public Void .ctor() { }
	// RVA: 0x66170d8 VA: 0x7598c2f0d8
	public Void .ctor(AddressFamily family) { }
	// RVA: 0x66171c4 VA: 0x7598c2f1c4
	public Void .ctor(IPEndPoint localEP) { }
	// RVA: 0x6617258 VA: 0x7598c2f258
	public Void .ctor(String hostname, Int32 port) { }
	// RVA: 0x66174d8 VA: 0x7598c2f4d8
	protected Boolean get_Active() { }
	// RVA: 0x66174e0 VA: 0x7598c2f4e0
	protected Void set_Active(Boolean value) { }
	// RVA: 0x66174ec VA: 0x7598c2f4ec
	public Socket get_Client() { }
	// RVA: 0x66174f4 VA: 0x7598c2f4f4
	public Void set_Client(Socket value) { }
	// RVA: 0x6617518 VA: 0x7598c2f518
	public Int32 get_Available() { }
	// RVA: 0x6617534 VA: 0x7598c2f534
	public Boolean get_Connected() { }
	// RVA: 0x6617550 VA: 0x7598c2f550
	public Boolean IsConnected() { }
	// RVA: 0x6617624 VA: 0x7598c2f624
	public Boolean get_ExclusiveAddressUse() { }
	// RVA: 0x6617640 VA: 0x7598c2f640
	public Void set_ExclusiveAddressUse(Boolean value) { }
	// RVA: 0x6617660 VA: 0x7598c2f660
	internal Void SetTcpClient(Socket s) { }
	// RVA: 0x6617684 VA: 0x7598c2f684
	public LingerOption get_LingerState() { }
	// RVA: 0x6617720 VA: 0x7598c2f720
	public Void set_LingerState(LingerOption value) { }
	// RVA: 0x6617778 VA: 0x7598c2f778
	public Boolean get_NoDelay() { }
	// RVA: 0x661780c VA: 0x7598c2f80c
	public Void set_NoDelay(Boolean value) { }
	// RVA: 0x661785c VA: 0x7598c2f85c
	public Int32 get_ReceiveBufferSize() { }
	// RVA: 0x66178f0 VA: 0x7598c2f8f0
	public Void set_ReceiveBufferSize(Int32 value) { }
	// RVA: 0x661793c VA: 0x7598c2f93c
	public Int32 get_ReceiveTimeout() { }
	// RVA: 0x66179d0 VA: 0x7598c2f9d0
	public Void set_ReceiveTimeout(Int32 value) { }
	// RVA: 0x6617a18 VA: 0x7598c2fa18
	public Int32 get_SendBufferSize() { }
	// RVA: 0x6617aac VA: 0x7598c2faac
	public Void set_SendBufferSize(Int32 value) { }
	// RVA: 0x6617af8 VA: 0x7598c2faf8
	public Int32 get_SendTimeout() { }
	// RVA: 0x6617b8c VA: 0x7598c2fb8c
	public Void set_SendTimeout(Int32 value) { }
	// RVA: 0x6617bd8 VA: 0x7598c2fbd8
	public TimeSpan get_ConnectTimeout() { }
	// RVA: 0x6617be0 VA: 0x7598c2fbe0
	public Void set_ConnectTimeout(TimeSpan value) { }
	// RVA: 0x6617be8 VA: 0x7598c2fbe8
	public Void Close() { }
	// RVA: 0x6617c7c VA: 0x7598c2fc7c
	public Void Connect(IPEndPoint remoteEP) { }
	// RVA: 0x6617fdc VA: 0x7598c2ffdc
	public Void Connect(IPAddress address, Int32 port) { }
	// RVA: 0x6618058 VA: 0x7598c30058
	private Void SetOptions() { }
	// RVA: 0x66180f4 VA: 0x7598c300f4
	private static IPAddress[] _OverrideDns4BestHttp(String host, Int32 port) { }
	// RVA: 0x66181f8 VA: 0x7598c301f8
	private static Boolean _CheckIfOverrideDns(String url) { }
	// RVA: 0x66172e0 VA: 0x7598c2f2e0
	public Void Connect(String hostname, Int32 port) { }
	// RVA: 0x6618278 VA: 0x7598c30278
	public Void Connect(IPAddress[] ipAddresses, Int32 port) { }
	// RVA: 0x66186b4 VA: 0x7598c306b4
	public Void EndConnect(IAsyncResult asyncResult) { }
	// RVA: 0x66186d0 VA: 0x7598c306d0
	public IAsyncResult BeginConnect(IPAddress address, Int32 port, AsyncCallback requestCallback, Object state) { }
	// RVA: 0x66186ec VA: 0x7598c306ec
	public IAsyncResult BeginConnect(IPAddress[] addresses, Int32 port, AsyncCallback requestCallback, Object state) { }
	// RVA: 0x6618708 VA: 0x7598c30708
	public IAsyncResult BeginConnect(String host, Int32 port, AsyncCallback requestCallback, Object state) { }
	// RVA: 0x6618724 VA: 0x7598c30724
	private Void System.IDisposable.Dispose() { }
	// RVA: 0x6618790 VA: 0x7598c30790
	protected virtual Void Dispose(Boolean disposing) { }
	// RVA: 0x6618814 VA: 0x7598c30814
	protected override Void Finalize() { }
	// RVA: 0x66188b4 VA: 0x7598c308b4
	public Stream GetStream() { }
	// RVA: 0x6618630 VA: 0x7598c30630
	private Void CheckDisposed() { }
}
```