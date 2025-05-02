# SimpleBigDecimal

**Namespace:** `Org.BouncyCastle.Math.EC.Abc`


## Properties

- `Int32 IntValue`

- `Int64 LongValue`

- `Int32 Scale`


## Methods

- `Void CheckScale(SimpleBigDecimal)`

- `SimpleBigDecimal AdjustScale(Int32)`

- `SimpleBigDecimal Add(SimpleBigDecimal)`

- `SimpleBigDecimal Add(BigInteger)`

- `SimpleBigDecimal Negate()`

- `SimpleBigDecimal Subtract(SimpleBigDecimal)`

- `SimpleBigDecimal Subtract(BigInteger)`

- `SimpleBigDecimal Multiply(SimpleBigDecimal)`

- `SimpleBigDecimal Multiply(BigInteger)`

- `SimpleBigDecimal Divide(SimpleBigDecimal)`

- `SimpleBigDecimal Divide(BigInteger)`

- `SimpleBigDecimal ShiftLeft(Int32)`

- `Int32 CompareTo(SimpleBigDecimal)`

- `Int32 CompareTo(BigInteger)`

- `BigInteger Floor()`

- `BigInteger Round()`

- `Int32 get_IntValue()`

- `Int64 get_LongValue()`

- `Int32 get_Scale()`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : Org.BouncyCastle.Math.EC.Abc
internal class SimpleBigDecimal
{
	private readonly BigInteger bigInt; // 0x10
	private readonly Int32 scale; // 0x18

	public Int32 IntValue { get; }
	public Int64 LongValue { get; }
	public Int32 Scale { get; }

	// RVA: 0x64cf238 VA: 0x7598ae7238
	public static SimpleBigDecimal GetInstance(BigInteger val, Int32 scale) { }
	// RVA: 0x64cf2bc VA: 0x7598ae72bc
	public Void .ctor(BigInteger bigInt, Int32 scale) { }
	// RVA: 0x64cf348 VA: 0x7598ae7348
	private Void .ctor(SimpleBigDecimal limBigDec) { }
	// RVA: 0x64cf38c VA: 0x7598ae738c
	private Void CheckScale(SimpleBigDecimal b) { }
	// RVA: 0x64cf3fc VA: 0x7598ae73fc
	public SimpleBigDecimal AdjustScale(Int32 newScale) { }
	// RVA: 0x64cf4dc VA: 0x7598ae74dc
	public SimpleBigDecimal Add(SimpleBigDecimal b) { }
	// RVA: 0x64cf574 VA: 0x7598ae7574
	public SimpleBigDecimal Add(BigInteger b) { }
	// RVA: 0x64cf614 VA: 0x7598ae7614
	public SimpleBigDecimal Negate() { }
	// RVA: 0x64cf694 VA: 0x7598ae7694
	public SimpleBigDecimal Subtract(SimpleBigDecimal b) { }
	// RVA: 0x64cf6bc VA: 0x7598ae76bc
	public SimpleBigDecimal Subtract(BigInteger b) { }
	// RVA: 0x64cf75c VA: 0x7598ae775c
	public SimpleBigDecimal Multiply(SimpleBigDecimal b) { }
	// RVA: 0x64cf7f4 VA: 0x7598ae77f4
	public SimpleBigDecimal Multiply(BigInteger b) { }
	// RVA: 0x64cf87c VA: 0x7598ae787c
	public SimpleBigDecimal Divide(SimpleBigDecimal b) { }
	// RVA: 0x64cf924 VA: 0x7598ae7924
	public SimpleBigDecimal Divide(BigInteger b) { }
	// RVA: 0x64cf9ac VA: 0x7598ae79ac
	public SimpleBigDecimal ShiftLeft(Int32 n) { }
	// RVA: 0x64cfa34 VA: 0x7598ae7a34
	public Int32 CompareTo(SimpleBigDecimal val) { }
	// RVA: 0x64cfa6c VA: 0x7598ae7a6c
	public Int32 CompareTo(BigInteger val) { }
	// RVA: 0x64cfaa8 VA: 0x7598ae7aa8
	public BigInteger Floor() { }
	// RVA: 0x64cfacc VA: 0x7598ae7acc
	public BigInteger Round() { }
	// RVA: 0x64cfb94 VA: 0x7598ae7b94
	public Int32 get_IntValue() { }
	// RVA: 0x64cfbb0 VA: 0x7598ae7bb0
	public Int64 get_LongValue() { }
	// RVA: 0x64cfbcc VA: 0x7598ae7bcc
	public Int32 get_Scale() { }
	// RVA: 0x64cfbd4 VA: 0x7598ae7bd4
	public override String ToString() { }
	// RVA: 0x64cfebc VA: 0x7598ae7ebc
	public override Boolean Equals(Object obj) { }
	// RVA: 0x64cff80 VA: 0x7598ae7f80
	public override Int32 GetHashCode() { }
}
```