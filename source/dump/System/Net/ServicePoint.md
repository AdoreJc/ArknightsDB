# ServicePoint

**Namespace:** `System.Net`


## Fields

- `DateTime lastDnsResolve`

- `Version protocolVersion`

- `IPHostEntry host`

- `Boolean usesProxy`

- `Boolean sendContinue`

- `Boolean useConnect`

- `Object hostE`

- `Boolean useNagle`

- `BindIPEndPoint endPointCallback`

- `Boolean tcp_keepalive`

- `Int32 tcp_keepalive_time`

- `Int32 tcp_keepalive_interval`

- `Boolean disposed`

- `Int32 connectionLeaseTimeout`

- `Int32 receiveBufferSize`

- `ServicePointScheduler <Scheduler>k__BackingField`

- `Int32 connectionLimit`

- `Int32 maxIdleTime`

- `Object m_ServerCertificateOrBytes`

- `Object m_ClientCertificateOrBytes`


## Properties

- `ServicePointScheduler Scheduler`

- `Uri Address`

- `Int32 ConnectionLimit`

- `Boolean Expect100Continue`

- `Boolean UseNagleAlgorithm`

- `Boolean HasTimedOut`


## Methods

- `ServicePointScheduler get_Scheduler()`

- `Void set_Scheduler(ServicePointScheduler)`

- `Uri get_Address()`

- `Int32 get_ConnectionLimit()`

- `Void set_Expect100Continue(Boolean)`

- `Boolean get_UseNagleAlgorithm()`

- `Void set_UseNagleAlgorithm(Boolean)`

- `Void SetTcpKeepAlive(Boolean, Int32, Int32)`

- `Boolean get_HasTimedOut()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
public class ServicePoint
{
	private readonly Uri uri; // 0x10
	private DateTime lastDnsResolve; // 0x18
	private Version protocolVersion; // 0x20
	private IPHostEntry host; // 0x28
	private Boolean usesProxy; // 0x30
	private Boolean sendContinue; // 0x31
	private Boolean useConnect; // 0x32
	private Object hostE; // 0x38
	private Boolean useNagle; // 0x40
	private BindIPEndPoint endPointCallback; // 0x48
	private Boolean tcp_keepalive; // 0x50
	private Int32 tcp_keepalive_time; // 0x54
	private Int32 tcp_keepalive_interval; // 0x58
	private Boolean disposed; // 0x5c
	private Int32 connectionLeaseTimeout; // 0x60
	private Int32 receiveBufferSize; // 0x64
	private readonly SPKey <Key>k__BackingField; // 0x68
	private ServicePointScheduler <Scheduler>k__BackingField; // 0x70
	private Int32 connectionLimit; // 0x78
	private Int32 maxIdleTime; // 0x7c
	private Object m_ServerCertificateOrBytes; // 0x80
	private Object m_ClientCertificateOrBytes; // 0x88

	internal SPKey Key { get; }
	private ServicePointScheduler Scheduler { get; set; }
	public Uri Address { get; }
	public Int32 ConnectionLimit { get; }
	public virtual Version ProtocolVersion { get; }
	public Boolean Expect100Continue { set; }
	public Boolean UseNagleAlgorithm { get; set; }
	internal Boolean SendContinue { get; set; }
	internal Boolean UsesProxy { get; set; }
	internal Boolean UseConnect { get; set; }
	private Boolean HasTimedOut { get; }
	internal IPHostEntry HostEntry { get; }

	// RVA: 0x633091c VA: 0x759894891c
	internal Void .ctor(SPKey key, Uri uri, Int32 connectionLimit, Int32 maxIdleTime) { }
	// RVA: 0x6330c44 VA: 0x7598948c44
	internal SPKey get_Key() { }
	// RVA: 0x6330c4c VA: 0x7598948c4c
	private ServicePointScheduler get_Scheduler() { }
	// RVA: 0x6330c54 VA: 0x7598948c54
	private Void set_Scheduler(ServicePointScheduler value) { }
	// RVA: 0x6330c5c VA: 0x7598948c5c
	public Uri get_Address() { }
	// RVA: 0x6330c64 VA: 0x7598948c64
	public Int32 get_ConnectionLimit() { }
	// RVA: 0x6330c6c VA: 0x7598948c6c
	public virtual Version get_ProtocolVersion() { }
	// RVA: 0x6330c74 VA: 0x7598948c74
	public Void set_Expect100Continue(Boolean value) { }
	// RVA: 0x6330c80 VA: 0x7598948c80
	public Boolean get_UseNagleAlgorithm() { }
	// RVA: 0x6330c88 VA: 0x7598948c88
	public Void set_UseNagleAlgorithm(Boolean value) { }
	// RVA: 0x632a7bc VA: 0x75989427bc
	internal Boolean get_SendContinue() { }
	// RVA: 0x6330c94 VA: 0x7598948c94
	internal Void set_SendContinue(Boolean value) { }
	// RVA: 0x6330ca0 VA: 0x7598948ca0
	public Void SetTcpKeepAlive(Boolean enabled, Int32 keepAliveTime, Int32 keepAliveInterval) { }
	// RVA: 0x6330d58 VA: 0x7598948d58
	internal Void KeepAliveSetup(Socket socket) { }
	// RVA: 0x6330e0c VA: 0x7598948e0c
	private static Void PutBytes(Byte[] bytes, UInt32 v, Int32 offset) { }
	// RVA: 0x6330f50 VA: 0x7598948f50
	internal Boolean get_UsesProxy() { }
	// RVA: 0x6330f58 VA: 0x7598948f58
	internal Void set_UsesProxy(Boolean value) { }
	// RVA: 0x6330f64 VA: 0x7598948f64
	internal Boolean get_UseConnect() { }
	// RVA: 0x6330f6c VA: 0x7598948f6c
	internal Void set_UseConnect(Boolean value) { }
	// RVA: 0x6330f78 VA: 0x7598948f78
	private Boolean get_HasTimedOut() { }
	// RVA: 0x63310a4 VA: 0x75989490a4
	internal IPHostEntry get_HostEntry() { }
	// RVA: 0x633146c VA: 0x759894946c
	internal Void SetVersion(Version version) { }
	// RVA: 0x6328eb4 VA: 0x7598940eb4
	internal Void SendRequest(WebOperation operation, String groupName) { }
	// RVA: 0x633155c VA: 0x759894955c
	internal Void FreeServicePoint() { }
	// RVA: 0x6331570 VA: 0x7598949570
	internal Void UpdateServerCertificate(X509Certificate certificate) { }
	// RVA: 0x63315ac VA: 0x75989495ac
	internal Void UpdateClientCertificate(X509Certificate certificate) { }
	// RVA: 0x63315e8 VA: 0x75989495e8
	internal Boolean CallEndPointDelegate(Socket sock, IPEndPoint remote) { }
}
```