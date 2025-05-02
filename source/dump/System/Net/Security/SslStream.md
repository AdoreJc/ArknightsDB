# SslStream

**Namespace:** `System.Net.Security`


## Fields

- `MobileTlsProvider provider`

- `MonoTlsSettings settings`

- `RemoteCertificateValidationCallback validationCallback`

- `LocalCertificateSelectionCallback selectionCallback`

- `MobileAuthenticatedStream impl`

- `Boolean explicitSettings`


## Methods

- `Void SetAndVerifyValidationCallback(RemoteCertificateValidationCallback)`

- `Void SetAndVerifySelectionCallback(LocalCertificateSelectionCallback)`

- `Void CheckDisposed()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net.Security
public class SslStream : AuthenticatedStream
{
	private MobileTlsProvider provider; // 0x38
	private MonoTlsSettings settings; // 0x40
	private RemoteCertificateValidationCallback validationCallback; // 0x48
	private LocalCertificateSelectionCallback selectionCallback; // 0x50
	private MobileAuthenticatedStream impl; // 0x58
	private Boolean explicitSettings; // 0x60

	internal MobileAuthenticatedStream Impl { get; }
	internal String InternalTargetHost { get; }
	public override Boolean IsAuthenticated { get; }
	public virtual X509Certificate LocalCertificate { get; }
	public override Boolean CanSeek { get; }
	public override Boolean CanRead { get; }
	public override Boolean CanTimeout { get; }
	public override Boolean CanWrite { get; }
	public override Int32 ReadTimeout { get; set; }
	public override Int32 WriteTimeout { get; set; }
	public override Int64 Length { get; }
	public override Int64 Position { get; set; }

	// RVA: 0x63630a4 VA: 0x759897b0a4
	internal MobileAuthenticatedStream get_Impl() { }
	// RVA: 0x636311c VA: 0x759897b11c
	internal String get_InternalTargetHost() { }
	// RVA: 0x6363140 VA: 0x759897b140
	private static MobileTlsProvider GetProvider() { }
	// RVA: 0x63631b0 VA: 0x759897b1b0
	public Void .ctor(Stream innerStream, Boolean leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback) { }
	// RVA: 0x63631bc VA: 0x759897b1bc
	public Void .ctor(Stream innerStream, Boolean leaveInnerStreamOpen, RemoteCertificateValidationCallback userCertificateValidationCallback, LocalCertificateSelectionCallback userCertificateSelectionCallback) { }
	// RVA: 0x636354c VA: 0x759897b54c
	internal Void .ctor(Stream innerStream, Boolean leaveInnerStreamOpen, MonoTlsProvider provider, MonoTlsSettings settings) { }
	// RVA: 0x6363278 VA: 0x759897b278
	private Void SetAndVerifyValidationCallback(RemoteCertificateValidationCallback callback) { }
	// RVA: 0x6363384 VA: 0x759897b384
	private Void SetAndVerifySelectionCallback(LocalCertificateSelectionCallback callback) { }
	// RVA: 0x6363694 VA: 0x759897b694
	public virtual Void AuthenticateAsClient(String targetHost) { }
	// RVA: 0x636371c VA: 0x759897b71c
	public virtual Void AuthenticateAsClient(String targetHost, X509CertificateCollection clientCertificates, SslProtocols enabledSslProtocols, Boolean checkCertificateRevocation) { }
	// RVA: 0x6363770 VA: 0x759897b770
	public virtual IAsyncResult BeginAuthenticateAsClient(String targetHost, X509CertificateCollection clientCertificates, SslProtocols enabledSslProtocols, Boolean checkCertificateRevocation, AsyncCallback asyncCallback, Object asyncState) { }
	// RVA: 0x63637e4 VA: 0x759897b7e4
	public virtual Void EndAuthenticateAsClient(IAsyncResult asyncResult) { }
	// RVA: 0x63637f0 VA: 0x759897b7f0
	public virtual Task AuthenticateAsClientAsync(String targetHost, X509CertificateCollection clientCertificates, SslProtocols enabledSslProtocols, Boolean checkCertificateRevocation) { }
	// RVA: 0x6363844 VA: 0x759897b844
	public override Boolean get_IsAuthenticated() { }
	// RVA: 0x6363870 VA: 0x759897b870
	public virtual X509Certificate get_LocalCertificate() { }
	// RVA: 0x6363894 VA: 0x759897b894
	public override Boolean get_CanSeek() { }
	// RVA: 0x636389c VA: 0x759897b89c
	public override Boolean get_CanRead() { }
	// RVA: 0x63638b4 VA: 0x759897b8b4
	public override Boolean get_CanTimeout() { }
	// RVA: 0x63638d4 VA: 0x759897b8d4
	public override Boolean get_CanWrite() { }
	// RVA: 0x63638ec VA: 0x759897b8ec
	public override Int32 get_ReadTimeout() { }
	// RVA: 0x6363918 VA: 0x759897b918
	public override Void set_ReadTimeout(Int32 value) { }
	// RVA: 0x6363954 VA: 0x759897b954
	public override Int32 get_WriteTimeout() { }
	// RVA: 0x6363980 VA: 0x759897b980
	public override Void set_WriteTimeout(Int32 value) { }
	// RVA: 0x63639bc VA: 0x759897b9bc
	public override Int64 get_Length() { }
	// RVA: 0x63639e4 VA: 0x759897b9e4
	public override Int64 get_Position() { }
	// RVA: 0x6363a0c VA: 0x759897ba0c
	public override Void set_Position(Int64 value) { }
	// RVA: 0x6363a6c VA: 0x759897ba6c
	public override Void SetLength(Int64 value) { }
	// RVA: 0x6363aa8 VA: 0x759897baa8
	public override Int64 Seek(Int64 offset, SeekOrigin origin) { }
	// RVA: 0x6363b08 VA: 0x759897bb08
	public override Task FlushAsync(CancellationToken cancellationToken) { }
	// RVA: 0x6363b2c VA: 0x759897bb2c
	public override Void Flush() { }
	// RVA: 0x63630bc VA: 0x759897b0bc
	private Void CheckDisposed() { }
	// RVA: 0x6363b50 VA: 0x759897bb50
	protected override Void Dispose(Boolean disposing) { }
	// RVA: 0x6363c0c VA: 0x759897bc0c
	public override Int32 Read(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x6363c60 VA: 0x759897bc60
	public override Void Write(Byte[] buffer, Int32 offset, Int32 count) { }
	// RVA: 0x6363cb4 VA: 0x759897bcb4
	public override Task`1 ReadAsync(Byte[] buffer, Int32 offset, Int32 count, CancellationToken cancellationToken) { }
	// RVA: 0x6363d10 VA: 0x759897bd10
	public override Task WriteAsync(Byte[] buffer, Int32 offset, Int32 count, CancellationToken cancellationToken) { }
	// RVA: 0x6363d6c VA: 0x759897bd6c
	public override IAsyncResult BeginRead(Byte[] buffer, Int32 offset, Int32 count, AsyncCallback callback, Object state) { }
	// RVA: 0x6363dd8 VA: 0x759897bdd8
	public override Int32 EndRead(IAsyncResult asyncResult) { }
	// RVA: 0x6363e20 VA: 0x759897be20
	public override IAsyncResult BeginWrite(Byte[] buffer, Int32 offset, Int32 count, AsyncCallback callback, Object state) { }
	// RVA: 0x6363e8c VA: 0x759897be8c
	public override Void EndWrite(IAsyncResult asyncResult) { }
}
```