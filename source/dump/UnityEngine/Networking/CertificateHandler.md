# CertificateHandler

**Namespace:** `UnityEngine.Networking`


## Methods

- `Void Release()`

- `Void Dispose()`


## Dump
```C#
// Dll : UnityEngine.UnityWebRequestModule.dll
// Namespace : UnityEngine.Networking
public class CertificateHandler
{
	internal IntPtr m_Ptr; // 0x10


	// RVA: 0x6a87ac8 VA: 0x759909fac8
	private Void Release() { }
	// RVA: 0x6a87b04 VA: 0x759909fb04
	protected virtual Boolean ValidateCertificate(Byte[] certificateData) { }
	// RVA: 0x6a87b0c VA: 0x759909fb0c
	internal Boolean ValidateCertificateNative(Byte[] certificateData) { }
	// RVA: 0x6a86230 VA: 0x759909e230
	public Void Dispose() { }
}
```