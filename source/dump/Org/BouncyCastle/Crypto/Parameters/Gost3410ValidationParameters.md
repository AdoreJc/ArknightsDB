# Gost3410ValidationParameters

**Namespace:** `Org.BouncyCastle.Crypto.Parameters`


## Fields

- `Int32 x0`

- `Int32 c`

- `Int64 x0L`

- `Int64 cL`


## Properties

- `Int32 C`

- `Int32 X0`

- `Int64 CL`

- `Int64 X0L`


## Methods

- `Int32 get_C()`

- `Int32 get_X0()`

- `Int64 get_CL()`

- `Int64 get_X0L()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Crypto.Parameters
public class Gost3410ValidationParameters
{
	private Int32 x0; // 0x10
	private Int32 c; // 0x14
	private Int64 x0L; // 0x18
	private Int64 cL; // 0x20

	public Int32 C { get; }
	public Int32 X0 { get; }
	public Int64 CL { get; }
	public Int64 X0L { get; }

	// RVA: 0x651940c VA: 0x7598b3140c
	public Void .ctor(Int32 x0, Int32 c) { }
	// RVA: 0x6519438 VA: 0x7598b31438
	public Void .ctor(Int64 x0L, Int64 cL) { }
	// RVA: 0x6519464 VA: 0x7598b31464
	public Int32 get_C() { }
	// RVA: 0x651946c VA: 0x7598b3146c
	public Int32 get_X0() { }
	// RVA: 0x6519474 VA: 0x7598b31474
	public Int64 get_CL() { }
	// RVA: 0x651947c VA: 0x7598b3147c
	public Int64 get_X0L() { }
	// RVA: 0x6519484 VA: 0x7598b31484
	public override Boolean Equals(Object obj) { }
	// RVA: 0x651954c VA: 0x7598b3154c
	public override Int32 GetHashCode() { }
}
```