# DHValidationParameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Properties

- `Int32 Counter`


## Methods

- `Int32 get_Counter()`

- `Boolean Equals(DHValidationParameters)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class DHValidationParameters
{
	private readonly Byte[] seed; // 0x10
	private readonly Int32 counter; // 0x18

	public Int32 Counter { get; }

	// RVA: 0x6515eb8 VA: 0x7598b2deb8
	public Void .ctor(Byte[] seed, Int32 counter) { }
	// RVA: 0x6515fdc VA: 0x7598b2dfdc
	public Byte[] GetSeed() { }
	// RVA: 0x6516054 VA: 0x7598b2e054
	public Int32 get_Counter() { }
	// RVA: 0x651605c VA: 0x7598b2e05c
	public override Boolean Equals(Object obj) { }
	// RVA: 0x65160f8 VA: 0x7598b2e0f8
	protected Boolean Equals(DHValidationParameters other) { }
	// RVA: 0x6516134 VA: 0x7598b2e134
	public override Int32 GetHashCode() { }
}
```