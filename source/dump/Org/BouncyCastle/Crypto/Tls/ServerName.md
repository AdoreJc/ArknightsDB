# ServerName

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
public class ServerName
{
	protected readonly Byte mNameType; // 0x10
	protected readonly Object mName; // 0x18

	public virtual Byte NameType { get; }
	public virtual Object Name { get; }

	// RVA: 0x64e7c3c VA: 0x7598affc3c
	public Void .ctor(Byte nameType, Object name) { }
	// RVA: 0x64e7dac VA: 0x7598affdac
	public virtual Byte get_NameType() { }
	// RVA: 0x64e7db4 VA: 0x7598affdb4
	public virtual Object get_Name() { }
	// RVA: 0x64e7dbc VA: 0x7598affdbc
	public virtual String GetHostName() { }
	// RVA: 0x64e7e98 VA: 0x7598affe98
	public virtual Void Encode(Stream output) { }
	// RVA: 0x64e7fb8 VA: 0x7598afffb8
	public static ServerName Parse(Stream input) { }
	// RVA: 0x64e7ce4 VA: 0x7598affce4
	protected static Boolean IsCorrectType(Byte nameType, Object name) { }
}
```