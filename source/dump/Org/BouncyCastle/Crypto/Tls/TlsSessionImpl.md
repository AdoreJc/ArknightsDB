# TlsSessionImpl

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
internal class TlsSessionImpl : TlsSession
{
	internal readonly Byte[] mSessionID; // 0x10
	internal SessionParameters mSessionParameters; // 0x18

	public virtual Byte[] SessionID { get; }
	public virtual Boolean IsResumable { get; }

	// RVA: 0x64ff6fc VA: 0x7598b176fc
	internal Void .ctor(Byte[] sessionID, SessionParameters sessionParameters) { }
	// RVA: 0x64ff7f8 VA: 0x7598b177f8
	public virtual SessionParameters ExportSessionParameters() { }
	// RVA: 0x64ff8cc VA: 0x7598b178cc
	public virtual Byte[] get_SessionID() { }
	// RVA: 0x64ff984 VA: 0x7598b17984
	public virtual Void Invalidate() { }
	// RVA: 0x64ffa60 VA: 0x7598b17a60
	public virtual Boolean get_IsResumable() { }
}
```