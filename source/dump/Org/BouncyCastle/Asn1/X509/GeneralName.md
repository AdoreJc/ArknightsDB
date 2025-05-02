# GeneralName

**Namespace:** `Org.BouncyCastle.Asn1.X509`


## Properties

- `Int32 TagNo`

- `Asn1Encodable Name`


## Methods

- `Int32 get_TagNo()`

- `Asn1Encodable get_Name()`

- `Void parseIPv4Mask(String, Byte[], Int32)`

- `Void parseIPv4(String, Byte[], Int32)`

- `Void copyInts(Int32[], Byte[], Int32)`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1.X509
public class GeneralName : Asn1Encodable, IAsn1Choice
{
	public const Int32 OtherName; // 0x0
	public const Int32 Rfc822Name; // 0x0
	public const Int32 DnsName; // 0x0
	public const Int32 X400Address; // 0x0
	public const Int32 DirectoryName; // 0x0
	public const Int32 EdiPartyName; // 0x0
	public const Int32 UniformResourceIdentifier; // 0x0
	public const Int32 IPAddress; // 0x0
	public const Int32 RegisteredID; // 0x0
	internal readonly Asn1Encodable obj; // 0x10
	internal readonly Int32 tag; // 0x18

	public Int32 TagNo { get; }
	public Asn1Encodable Name { get; }

	// RVA: 0x65b2d48 VA: 0x7598bcad48
	public Void .ctor(X509Name directoryName) { }
	// RVA: 0x65b2d84 VA: 0x7598bcad84
	public Void .ctor(Asn1Object name, Int32 tag) { }
	// RVA: 0x65b2dc0 VA: 0x7598bcadc0
	public Void .ctor(Int32 tag, Asn1Encodable name) { }
	// RVA: 0x65b2dfc VA: 0x7598bcadfc
	public Void .ctor(Int32 tag, String name) { }
	// RVA: 0x65b32c4 VA: 0x7598bcb2c4
	public static GeneralName GetInstance(Object obj) { }
	// RVA: 0x65b3894 VA: 0x7598bcb894
	public static GeneralName GetInstance(Asn1TaggedObject tagObj, Boolean explicitly) { }
	// RVA: 0x65b38ac VA: 0x7598bcb8ac
	public Int32 get_TagNo() { }
	// RVA: 0x65b38b4 VA: 0x7598bcb8b4
	public Asn1Encodable get_Name() { }
	// RVA: 0x65b38bc VA: 0x7598bcb8bc
	public override String ToString() { }
	// RVA: 0x65b30b0 VA: 0x7598bcb0b0
	private Byte[] toGeneralNameEncoding(String ip) { }
	// RVA: 0x65b40b4 VA: 0x7598bcc0b4
	private Void parseIPv4Mask(String mask, Byte[] addr, Int32 offset) { }
	// RVA: 0x65b3fb4 VA: 0x7598bcbfb4
	private Void parseIPv4(String ip, Byte[] addr, Int32 offset) { }
	// RVA: 0x65b3efc VA: 0x7598bcbefc
	private Int32[] parseMask(String mask) { }
	// RVA: 0x65b3e70 VA: 0x7598bcbe70
	private Void copyInts(Int32[] parsedIp, Byte[] addr, Int32 offSet) { }
	// RVA: 0x65b3a90 VA: 0x7598bcba90
	private Int32[] parseIPv6(String ip) { }
	// RVA: 0x65b4138 VA: 0x7598bcc138
	public override Asn1Object ToAsn1Object() { }
}
```