# ServerCertValidationCallback

**Namespace:** `System.Net`


## Dump
```C#
// Dll : System.dll
// Namespace : System.Net
internal class ServerCertValidationCallback
{
	private readonly RemoteCertificateValidationCallback m_ValidationCallback; // 0x10
	private readonly ExecutionContext m_Context; // 0x18

	internal RemoteCertificateValidationCallback ValidationCallback { get; }

	// RVA: 0x6444cf0 VA: 0x7598a5ccf0
	internal Void .ctor(RemoteCertificateValidationCallback validationCallback) { }
	// RVA: 0x6444d7c VA: 0x7598a5cd7c
	internal RemoteCertificateValidationCallback get_ValidationCallback() { }
	// RVA: 0x6444d84 VA: 0x7598a5cd84
	internal Void Callback(Object state) { }
	// RVA: 0x6444e30 VA: 0x7598a5ce30
	internal Boolean Invoke(Object request, X509Certificate certificate, X509Chain chain, SslPolicyErrors sslPolicyErrors) { }
}
```