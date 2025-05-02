# TlsStream

**Namespace:** `System.Net`


## Fields

- `SslStream _sslStream`

- `String _host`

- `X509CertificateCollection _clientCertificates`


## Methods

- `Void AuthenticateAsClient()`

- `IAsyncResult BeginAuthenticateAsClient(AsyncCallback, Object)`

- `Void EndAuthenticateAsClient(IAsyncResult)`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
internal class TlsStream : NetworkStream
{
	private SslStream _sslStream; // 0x48
	private String _host; // 0x50
	private X509CertificateCollection _clientCertificates; // 0x58


	// RVA: 0x6416534 VA: 0x7598a2e534
	public Void .ctor(NetworkStream stream, Socket socket, String host, X509CertificateCollection clientCertificates) { }
	// RVA: 0x641662c VA: 0x7598a2e62c
	public Void AuthenticateAsClient() { }
	// RVA: 0x641672c VA: 0x7598a2e72c
	public IAsyncResult BeginAuthenticateAsClient(AsyncCallback asyncCallback, Object state) { }
	// RVA: 0x6416844 VA: 0x7598a2e844
	public Void EndAuthenticateAsClient(IAsyncResult asyncResult) { }
	// RVA: 0x6416868 VA: 0x7598a2e868
	public override IAsyncResult BeginWrite(Byte[] buffer, Int32 offset, Int32 size, AsyncCallback callback, Object state) { }
	// RVA: 0x641688c VA: 0x7598a2e88c
	public override Void EndWrite(IAsyncResult result) { }
	// RVA: 0x64168b0 VA: 0x7598a2e8b0
	public override Void Write(Byte[] buffer, Int32 offset, Int32 size) { }
	// RVA: 0x64168d4 VA: 0x7598a2e8d4
	public override Int32 Read(Byte[] buffer, Int32 offset, Int32 size) { }
	// RVA: 0x64168f8 VA: 0x7598a2e8f8
	public override IAsyncResult BeginRead(Byte[] buffer, Int32 offset, Int32 count, AsyncCallback callback, Object state) { }
	// RVA: 0x641691c VA: 0x7598a2e91c
	public override Int32 EndRead(IAsyncResult asyncResult) { }
	// RVA: 0x6416940 VA: 0x7598a2e940
	public override Void Close() { }
}
```