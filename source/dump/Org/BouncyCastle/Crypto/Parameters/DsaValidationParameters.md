# DsaValidationParameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class DsaValidationParameters
{
	private readonly Byte[] seed; // 0x10
	private readonly Int32 counter; // 0x18
	private readonly Int32 usageIndex; // 0x1c

	public virtual Int32 Counter { get; }
	public virtual Int32 UsageIndex { get; }

	// RVA: 0x6516998 VA: 0x7598b2e998
	public Void .ctor(Byte[] seed, Int32 counter) { }
	// RVA: 0x65169a0 VA: 0x7598b2e9a0
	public Void .ctor(Byte[] seed, Int32 counter, Int32 usageIndex) { }
	// RVA: 0x6516ad0 VA: 0x7598b2ead0
	public virtual Byte[] GetSeed() { }
	// RVA: 0x6516b48 VA: 0x7598b2eb48
	public virtual Int32 get_Counter() { }
	// RVA: 0x6516b50 VA: 0x7598b2eb50
	public virtual Int32 get_UsageIndex() { }
	// RVA: 0x6516b58 VA: 0x7598b2eb58
	public override Boolean Equals(Object obj) { }
	// RVA: 0x6516bfc VA: 0x7598b2ebfc
	protected virtual Boolean Equals(DsaValidationParameters other) { }
	// RVA: 0x6516c38 VA: 0x7598b2ec38
	public override Int32 GetHashCode() { }
}
```