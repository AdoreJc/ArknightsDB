# DerGeneralizedTime

**Namespace:** `Org.BouncyCastle.Asn1`


## Properties

- `String TimeString`

- `Boolean HasFractionalSeconds`


## Methods

- `String get_TimeString()`

- `String GetTime()`

- `String CalculateGmtOffset()`

- `DateTime ToDateTime()`

- `String FString(Int32)`

- `DateTime ParseDateString(String, String, Boolean)`

- `Boolean get_HasFractionalSeconds()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1
public class DerGeneralizedTime : Asn1Object
{
	private readonly String time; // 0x10

	public String TimeString { get; }
	private Boolean HasFractionalSeconds { get; }

	// RVA: 0x659c7d4 VA: 0x7598bb47d4
	public static DerGeneralizedTime GetInstance(Object obj) { }
	// RVA: 0x659c8d4 VA: 0x7598bb48d4
	public static DerGeneralizedTime GetInstance(Asn1TaggedObject obj, Boolean isExplicit) { }
	// RVA: 0x659ca04 VA: 0x7598bb4a04
	public Void .ctor(String time) { }
	// RVA: 0x659cda8 VA: 0x7598bb4da8
	public Void .ctor(DateTime time) { }
	// RVA: 0x6590adc VA: 0x7598ba8adc
	internal Void .ctor(Byte[] bytes) { }
	// RVA: 0x659ce44 VA: 0x7598bb4e44
	public String get_TimeString() { }
	// RVA: 0x659ce4c VA: 0x7598bb4e4c
	public String GetTime() { }
	// RVA: 0x659d1c4 VA: 0x7598bb51c4
	private String CalculateGmtOffset() { }
	// RVA: 0x659d4bc VA: 0x7598bb54bc
	private static String Convert(Int32 time) { }
	// RVA: 0x659cb28 VA: 0x7598bb4b28
	public DateTime ToDateTime() { }
	// RVA: 0x659d558 VA: 0x7598bb5558
	private String FString(Int32 count) { }
	// RVA: 0x659d5e0 VA: 0x7598bb55e0
	private DateTime ParseDateString(String s, String format, Boolean makeUniversal) { }
	// RVA: 0x659d52c VA: 0x7598bb552c
	private Boolean get_HasFractionalSeconds() { }
	// RVA: 0x659d838 VA: 0x7598bb5838
	private Byte[] GetOctets() { }
	// RVA: 0x659d844 VA: 0x7598bb5844
	internal override Void Encode(DerOutputStream derOut) { }
	// RVA: 0x659d874 VA: 0x7598bb5874
	protected override Boolean Asn1Equals(Asn1Object asn1Object) { }
	// RVA: 0x659d914 VA: 0x7598bb5914
	protected override Int32 Asn1GetHashCode() { }
}
```