# ServerNameList

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
public class ServerNameList
{
	protected readonly IList mServerNameList; // 0x10

	public virtual IList ServerNames { get; }

	// RVA: 0x64e80cc VA: 0x7598b000cc
	public Void .ctor(IList serverNameList) { }
	// RVA: 0x64e814c VA: 0x7598b0014c
	public virtual IList get_ServerNames() { }
	// RVA: 0x64e8154 VA: 0x7598b00154
	public virtual Void Encode(Stream output) { }
	// RVA: 0x64e866c VA: 0x7598b0066c
	public static ServerNameList Parse(Stream input) { }
	// RVA: 0x64e862c VA: 0x7598b0062c
	private static Byte[] CheckNameType(Byte[] nameTypesSeen, Byte nameType) { }
}
```