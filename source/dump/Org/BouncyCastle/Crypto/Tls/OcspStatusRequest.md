# OcspStatusRequest

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
public class OcspStatusRequest
{
	protected readonly IList mResponderIDList; // 0x10
	protected readonly X509Extensions mRequestExtensions; // 0x18

	public virtual IList ResponderIDList { get; }
	public virtual X509Extensions RequestExtensions { get; }

	// RVA: 0x64e57d4 VA: 0x7598afd7d4
	public Void .ctor(IList responderIDList, X509Extensions requestExtensions) { }
	// RVA: 0x64e5818 VA: 0x7598afd818
	public virtual IList get_ResponderIDList() { }
	// RVA: 0x64e5820 VA: 0x7598afd820
	public virtual X509Extensions get_RequestExtensions() { }
	// RVA: 0x64e5828 VA: 0x7598afd828
	public virtual Void Encode(Stream output) { }
	// RVA: 0x64ddd4c VA: 0x7598af5d4c
	public static OcspStatusRequest Parse(Stream input) { }
}
```