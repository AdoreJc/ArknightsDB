# RC2Transform

**Namespace:** `System.Security.Cryptography`


## Fields

- `UInt16 R0`

- `UInt16 R1`

- `UInt16 R2`

- `UInt16 R3`

- `Int32 j`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Security.Cryptography
internal class RC2Transform : SymmetricTransform
{
	private UInt16 R0; // 0x58
	private UInt16 R1; // 0x5a
	private UInt16 R2; // 0x5c
	private UInt16 R3; // 0x5e
	private UInt16[] K; // 0x60
	private Int32 j; // 0x68
	private static readonly Byte[] pitable; // 0x0


	// RVA: 0x5f72984 VA: 0x759858a984
	public Void .ctor(RC2 rc2Algo, Boolean encryption, Byte[] key, Byte[] iv) { }
	// RVA: 0x5f72edc VA: 0x759858aedc
	protected override Void ECB(Byte[] input, Byte[] output) { }
	// RVA: 0x5f7380c VA: 0x759858b80c
	private static Void .cctor() { }
}
```