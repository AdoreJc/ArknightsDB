# DerBitString

**Namespace:** `Org.BouncyCastle.Asn1`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1
public class DerBitString : DerStringBase
{
	private static readonly Char[] table; // 0x0
	protected readonly Byte[] mData; // 0x10
	protected readonly Int32 mPadBits; // 0x18

	public virtual Int32 PadBits { get; }
	public virtual Int32 IntValue { get; }

	// RVA: 0x659aa44 VA: 0x7598bb2a44
	public static DerBitString GetInstance(Object obj) { }
	// RVA: 0x659ac50 VA: 0x7598bb2c50
	public static DerBitString GetInstance(Asn1TaggedObject obj, Boolean isExplicit) { }
	// RVA: 0x6596520 VA: 0x7598bae520
	public Void .ctor(Byte[] data, Int32 padBits) { }
	// RVA: 0x65966b8 VA: 0x7598bae6b8
	public Void .ctor(Byte[] data) { }
	// RVA: 0x6596724 VA: 0x7598bae724
	public Void .ctor(Int32 namedBits) { }
	// RVA: 0x65968cc VA: 0x7598bae8cc
	public Void .ctor(Asn1Encodable obj) { }
	// RVA: 0x659ada8 VA: 0x7598bb2da8
	public virtual Byte[] GetOctets() { }
	// RVA: 0x659ae10 VA: 0x7598bb2e10
	public virtual Byte[] GetBytes() { }
	// RVA: 0x659ae6c VA: 0x7598bb2e6c
	public virtual Int32 get_PadBits() { }
	// RVA: 0x659ae74 VA: 0x7598bb2e74
	public virtual Int32 get_IntValue() { }
	// RVA: 0x6596a44 VA: 0x7598baea44
	internal override Void Encode(DerOutputStream derOut) { }
	// RVA: 0x659afdc VA: 0x7598bb2fdc
	protected override Int32 Asn1GetHashCode() { }
	// RVA: 0x659b020 VA: 0x7598bb3020
	protected override Boolean Asn1Equals(Asn1Object asn1Object) { }
	// RVA: 0x659b0cc VA: 0x7598bb30cc
	public override String GetString() { }
	// RVA: 0x6590844 VA: 0x7598ba8844
	internal static DerBitString FromAsn1Octets(Byte[] octets) { }
	// RVA: 0x659b238 VA: 0x7598bb3238
	private static Void .cctor() { }
}
```