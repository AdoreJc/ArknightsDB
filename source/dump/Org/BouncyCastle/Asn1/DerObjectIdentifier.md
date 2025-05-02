# DerObjectIdentifier

**Namespace:** `Org.BouncyCastle.Asn1`


## Properties

- `String Id`


## Methods

- `String get_Id()`

- `Void WriteField(Stream, Int64)`

- `Void WriteField(Stream, BigInteger)`

- `Void DoOutput(MemoryStream)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1
public class DerObjectIdentifier : Asn1Object
{
	private readonly String identifier; // 0x10
	private Byte[] body; // 0x18
	private const Int64 LONG_LIMIT; // 0x0
	private static readonly DerObjectIdentifier[] cache; // 0x0

	public String Id { get; }

	// RVA: 0x659f368 VA: 0x7598bb7368
	public static DerObjectIdentifier GetInstance(Object obj) { }
	// RVA: 0x659f4c8 VA: 0x7598bb74c8
	public static DerObjectIdentifier GetInstance(Asn1TaggedObject obj, Boolean explicitly) { }
	// RVA: 0x659f544 VA: 0x7598bb7544
	public Void .ctor(String identifier) { }
	// RVA: 0x659f738 VA: 0x7598bb7738
	internal Void .ctor(DerObjectIdentifier oid, String branchID) { }
	// RVA: 0x659f90c VA: 0x7598bb790c
	public String get_Id() { }
	// RVA: 0x659f914 VA: 0x7598bb7914
	public virtual DerObjectIdentifier Branch(String branchID) { }
	// RVA: 0x659f984 VA: 0x7598bb7984
	public virtual Boolean On(DerObjectIdentifier stem) { }
	// RVA: 0x659fa34 VA: 0x7598bb7a34
	internal Void .ctor(Byte[] bytes) { }
	// RVA: 0x659fd28 VA: 0x7598bb7d28
	private Void WriteField(Stream outputStream, Int64 fieldValue) { }
	// RVA: 0x659fe08 VA: 0x7598bb7e08
	private Void WriteField(Stream outputStream, BigInteger fieldValue) { }
	// RVA: 0x659ff84 VA: 0x7598bb7f84
	private Void DoOutput(MemoryStream bOut) { }
	// RVA: 0x65a0138 VA: 0x7598bb8138
	internal Byte[] GetBody() { }
	// RVA: 0x65a0294 VA: 0x7598bb8294
	internal override Void Encode(DerOutputStream derOut) { }
	// RVA: 0x65a02bc VA: 0x7598bb82bc
	protected override Int32 Asn1GetHashCode() { }
	// RVA: 0x65a02dc VA: 0x7598bb82dc
	protected override Boolean Asn1Equals(Asn1Object asn1Object) { }
	// RVA: 0x65a037c VA: 0x7598bb837c
	public override String ToString() { }
	// RVA: 0x659f874 VA: 0x7598bb7874
	private static Boolean IsValidBranchID(String branchID, Int32 start) { }
	// RVA: 0x659f680 VA: 0x7598bb7680
	private static Boolean IsValidIdentifier(String identifier) { }
	// RVA: 0x659facc VA: 0x7598bb7acc
	private static String MakeOidStringFromBytes(Byte[] bytes) { }
	// RVA: 0x6590620 VA: 0x7598ba8620
	internal static DerObjectIdentifier FromOctetString(Byte[] enc) { }
	// RVA: 0x65a0384 VA: 0x7598bb8384
	private static Void .cctor() { }
}
```