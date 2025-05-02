# SupplementalDataEntry

**Namespace:** `Org.BouncyCastle.Crypto.Tls`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Tls
public class SupplementalDataEntry
{
	protected readonly Int32 mDataType; // 0x10
	protected readonly Byte[] mData; // 0x18

	public virtual Int32 DataType { get; }
	public virtual Byte[] Data { get; }

	// RVA: 0x64ea2ac VA: 0x7598b022ac
	public Void .ctor(Int32 dataType, Byte[] data) { }
	// RVA: 0x64ea2e4 VA: 0x7598b022e4
	public virtual Int32 get_DataType() { }
	// RVA: 0x64ea2ec VA: 0x7598b022ec
	public virtual Byte[] get_Data() { }
}
```