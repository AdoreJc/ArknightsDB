# WebConnection

**Namespace:** `System.Net`


## Fields

- `NetworkCredential ntlm_credentials`

- `Boolean ntlm_authenticated`

- `Boolean unsafe_sharing`

- `Stream networkStream`

- `Socket socket`

- `MonoTlsStream monoTlsStream`

- `WebConnectionTunnel tunnel`

- `Int32 disposed`

- `DateTime idleSince`

- `WebOperation currentOperation`


## Properties

- `ServicePoint ServicePoint`

- `Boolean Closed`

- `DateTime IdleSince`


## Methods

- `ServicePoint get_ServicePoint()`

- `Boolean CanReuse()`

- `Boolean CheckReusable()`

- `Task Connect(WebOperation, CancellationToken)`

- `Boolean PrepareSharingNtlm(WebOperation)`

- `Void Reset()`

- `Void Close(Boolean)`

- `Void CloseSocket()`

- `Boolean get_Closed()`

- `DateTime get_IdleSince()`

- `Boolean StartOperation(WebOperation, Boolean)`

- `Boolean Continue(WebOperation)`

- `Void Dispose(Boolean)`

- `Void Dispose()`

- `Void ResetNtlm()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
internal class WebConnection : IDisposable
{
	private NetworkCredential ntlm_credentials; // 0x10
	private Boolean ntlm_authenticated; // 0x18
	private Boolean unsafe_sharing; // 0x19
	private Stream networkStream; // 0x20
	private Socket socket; // 0x28
	private MonoTlsStream monoTlsStream; // 0x30
	private WebConnectionTunnel tunnel; // 0x38
	private Int32 disposed; // 0x40
	private readonly ServicePoint <ServicePoint>k__BackingField; // 0x48
	private DateTime idleSince; // 0x50
	private WebOperation currentOperation; // 0x58

	public ServicePoint ServicePoint { get; }
	public Boolean Closed { get; }
	public DateTime IdleSince { get; }
	internal Boolean NtlmAuthenticated { get; set; }
	internal NetworkCredential NtlmCredential { get; set; }
	internal Boolean UnsafeAuthenticatedConnectionSharing { get; set; }

	// RVA: 0x63354bc VA: 0x759894d4bc
	public ServicePoint get_ServicePoint() { }
	// RVA: 0x633413c VA: 0x759894c13c
	public Void .ctor(ServicePoint sPoint) { }
	// RVA: 0x63354c4 VA: 0x759894d4c4
	private Boolean CanReuse() { }
	// RVA: 0x63354f4 VA: 0x759894d4f4
	private Boolean CheckReusable() { }
	// RVA: 0x6335590 VA: 0x759894d590
	private Task Connect(WebOperation operation, CancellationToken cancellationToken) { }
	// RVA: 0x63356b4 VA: 0x759894d6b4
	private Task`1 CreateStream(WebOperation operation, Boolean reused, CancellationToken cancellationToken) { }
	// RVA: 0x6335818 VA: 0x759894d818
	internal Task`1 InitConnection(WebOperation operation, CancellationToken cancellationToken) { }
	// RVA: 0x6335964 VA: 0x759894d964
	internal static WebException GetException(WebExceptionStatus status, Exception error) { }
	// RVA: 0x6335aec VA: 0x759894daec
	internal static Boolean ReadLine(Byte[] buffer, ref Int32 start, Int32 max, ref String output) { }
	// RVA: 0x6333b14 VA: 0x759894bb14
	internal Boolean CanReuseConnection(WebOperation operation) { }
	// RVA: 0x6335cec VA: 0x759894dcec
	private Boolean PrepareSharingNtlm(WebOperation operation) { }
	// RVA: 0x6336008 VA: 0x759894e008
	private Void Reset() { }
	// RVA: 0x6336104 VA: 0x759894e104
	private Void Close(Boolean reset) { }
	// RVA: 0x63361cc VA: 0x759894e1cc
	private Void CloseSocket() { }
	// RVA: 0x63337f0 VA: 0x759894b7f0
	public Boolean get_Closed() { }
	// RVA: 0x6336468 VA: 0x759894e468
	public DateTime get_IdleSince() { }
	// RVA: 0x6333f40 VA: 0x759894bf40
	public Boolean StartOperation(WebOperation operation, Boolean reused) { }
	// RVA: 0x6332bf8 VA: 0x759894abf8
	public Boolean Continue(WebOperation next) { }
	// RVA: 0x6336470 VA: 0x759894e470
	private Void Dispose(Boolean disposing) { }
	// RVA: 0x63337e8 VA: 0x759894b7e8
	public Void Dispose() { }
	// RVA: 0x63360dc VA: 0x759894e0dc
	private Void ResetNtlm() { }
	// RVA: 0x63364a8 VA: 0x759894e4a8
	internal Boolean get_NtlmAuthenticated() { }
	// RVA: 0x63364b0 VA: 0x759894e4b0
	internal Void set_NtlmAuthenticated(Boolean value) { }
	// RVA: 0x63364bc VA: 0x759894e4bc
	internal NetworkCredential get_NtlmCredential() { }
	// RVA: 0x63364c4 VA: 0x759894e4c4
	internal Void set_NtlmCredential(NetworkCredential value) { }
	// RVA: 0x63364cc VA: 0x759894e4cc
	internal Boolean get_UnsafeAuthenticatedConnectionSharing() { }
	// RVA: 0x63364d4 VA: 0x759894e4d4
	internal Void set_UnsafeAuthenticatedConnectionSharing(Boolean value) { }
}
```