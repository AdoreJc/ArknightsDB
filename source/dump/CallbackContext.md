# CallbackContext

**Namespace:** ` `


## Dump
```C#
// Dll : System.dll
// Namespace : 
private class CallbackContext
{
	internal readonly Object request; // 0x10
	internal readonly X509Certificate certificate; // 0x18
	internal readonly X509Chain chain; // 0x20
	internal readonly SslPolicyErrors sslPolicyErrors; // 0x28
	internal Boolean result; // 0x2c


	// RVA: 0x6444f98 VA: 0x7598a5cf98
	internal Void .ctor(Object request, X509Certificate certificate, X509Chain chain, SslPolicyErrors sslPolicyErrors) { }
}
```