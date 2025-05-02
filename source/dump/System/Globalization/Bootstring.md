# Bootstring

**Namespace:** `System.Globalization`


## Methods

- `String Encode(String, Int32)`

- `Char EncodeDigit(Int32)`

- `Int32 DecodeDigit(Char)`

- `Int32 Adapt(Int32, Int32, Boolean)`

- `String Decode(String, Int32)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Globalization
internal class Bootstring
{
	private readonly Char delimiter; // 0x10
	private readonly Int32 base_num; // 0x14
	private readonly Int32 tmin; // 0x18
	private readonly Int32 tmax; // 0x1c
	private readonly Int32 skew; // 0x20
	private readonly Int32 damp; // 0x24
	private readonly Int32 initial_bias; // 0x28
	private readonly Int32 initial_n; // 0x2c


	// RVA: 0x6078aa8 VA: 0x7598690aa8
	public Void .ctor(Char delimiter, Int32 baseNum, Int32 tmin, Int32 tmax, Int32 skew, Int32 damp, Int32 initialBias, Int32 initialN) { }
	// RVA: 0x6078048 VA: 0x7598690048
	public String Encode(String s, Int32 offset) { }
	// RVA: 0x6078b14 VA: 0x7598690b14
	private Char EncodeDigit(Int32 d) { }
	// RVA: 0x6078ba4 VA: 0x7598690ba4
	private Int32 DecodeDigit(Char c) { }
	// RVA: 0x6078b2c VA: 0x7598690b2c
	private Int32 Adapt(Int32 delta, Int32 numPoints, Boolean firstTime) { }
	// RVA: 0x60787d0 VA: 0x75986907d0
	public String Decode(String s, Int32 offset) { }
}
```