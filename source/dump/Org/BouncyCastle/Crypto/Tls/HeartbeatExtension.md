# HeartbeatExtension

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
public class HeartbeatExtension
{
	protected readonly Byte mMode; // 0x10

	public virtual Byte Mode { get; }

	// RVA: 0x64e5114 VA: 0x7598afd114
	public Void .ctor(Byte mode) { }
	// RVA: 0x64e51c0 VA: 0x7598afd1c0
	public virtual Byte get_Mode() { }
	// RVA: 0x64e51c8 VA: 0x7598afd1c8
	public virtual Void Encode(Stream output) { }
	// RVA: 0x64e5234 VA: 0x7598afd234
	public static HeartbeatExtension Parse(Stream input) { }
}
```