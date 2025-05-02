# DerUtcTime

**Namespace:** `Org.BouncyCastle.Asn1`


## Properties

- `String TimeString`

- `String AdjustedTime`

- `String AdjustedTimeString`


## Methods

- `DateTime ToDateTime()`

- `DateTime ToAdjustedDateTime()`

- `DateTime ParseDateString(String, String)`

- `String get_TimeString()`

- `String get_AdjustedTime()`

- `String get_AdjustedTimeString()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Asn1
public class DerUtcTime : Asn1Object
{
	private readonly String time; // 0x10

	public String TimeString { get; }
	public String AdjustedTime { get; }
	public String AdjustedTimeString { get; }

	// RVA: 0x65a1c00 VA: 0x7598bb9c00
	public static DerUtcTime GetInstance(Object obj) { }
	// RVA: 0x65a1cf0 VA: 0x7598bb9cf0
	public static DerUtcTime GetInstance(Asn1TaggedObject obj, Boolean isExplicit) { }
	// RVA: 0x65a1e20 VA: 0x7598bb9e20
	public Void .ctor(String time) { }
	// RVA: 0x65a1fe4 VA: 0x7598bb9fe4
	public Void .ctor(DateTime time) { }
	// RVA: 0x6590cc8 VA: 0x7598ba8cc8
	internal Void .ctor(Byte[] bytes) { }
	// RVA: 0x65a1f94 VA: 0x7598bb9f94
	public DateTime ToDateTime() { }
	// RVA: 0x65a261c VA: 0x7598bba61c
	public DateTime ToAdjustedDateTime() { }
	// RVA: 0x65a2564 VA: 0x7598bba564
	private DateTime ParseDateString(String dateStr, String formatStr) { }
	// RVA: 0x65a20e0 VA: 0x7598bba0e0
	public String get_TimeString() { }
	// RVA: 0x65a26f8 VA: 0x7598bba6f8
	public String get_AdjustedTime() { }
	// RVA: 0x65a266c VA: 0x7598bba66c
	public String get_AdjustedTimeString() { }
	// RVA: 0x65a26fc VA: 0x7598bba6fc
	private Byte[] GetOctets() { }
	// RVA: 0x65a2708 VA: 0x7598bba708
	internal override Void Encode(DerOutputStream derOut) { }
	// RVA: 0x65a2738 VA: 0x7598bba738
	protected override Boolean Asn1Equals(Asn1Object asn1Object) { }
	// RVA: 0x65a27d8 VA: 0x7598bba7d8
	protected override Int32 Asn1GetHashCode() { }
	// RVA: 0x65a27f8 VA: 0x7598bba7f8
	public override String ToString() { }
}
```