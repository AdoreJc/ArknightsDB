# TSRandom

**Namespace:** `Torappu`


## Fields

- `Int32 mti`


## Methods

- `Int32 Next()`

- `Int32 Next(Int32, Int32)`

- `FP Next(Single, Single)`

- `FP NextFP()`

- `Single NextFloat()`

- `Single NextFloat(Boolean)`

- `Single NextFloatPositive()`

- `Double NextDouble()`

- `Double NextDouble(Boolean)`

- `Double NextDoublePositive()`

- `Double Next53BitRes()`

- `Void Initialize()`

- `Void Initialize(Int32)`

- `Void Initialize(Int32[])`

- `Void init_genrand(UInt32)`

- `Void init_by_array(UInt32[], UInt32)`

- `UInt32 genrand_int32()`

- `Int32 genrand_int31()`

- `FP genrand_FP()`

- `Double genrand_real1()`

- `Double genrand_real2()`

- `Double genrand_real3()`

- `Double genrand_res53()`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : Torappu
public class TSRandom
{
	private const Int32 N; // 0x0
	private const Int32 M; // 0x0
	private const UInt32 MATRIX_A; // 0x0
	private const UInt32 UPPER_MASK; // 0x0
	private const UInt32 LOWER_MASK; // 0x0
	private const Int32 MAX_RAND_INT; // 0x0
	private UInt32[] mag01; // 0x10
	private UInt32[] mt; // 0x18
	private Int32 mti; // 0x20
	public static TSRandom instance; // 0x0

	public static Int32 MaxRandomInt { get; }
	public static FP value { get; }
	public static TSVector3 insideUnitSphere { get; }

	// RVA: 0x675f780 VA: 0x7598d77780
	internal static Void Init() { }
	// RVA: 0x675f7dc VA: 0x7598d777dc
	public static TSRandom New(Int32 seed) { }
	// RVA: 0x675f900 VA: 0x7598d77900
	private Void .ctor() { }
	// RVA: 0x675f83c VA: 0x7598d7783c
	private Void .ctor(Int32 seed) { }
	// RVA: 0x675fa84 VA: 0x7598d77a84
	private Void .ctor(Int32[] init) { }
	// RVA: 0x675fd34 VA: 0x7598d77d34
	public static Int32 get_MaxRandomInt() { }
	// RVA: 0x675fd3c VA: 0x7598d77d3c
	public Int32 Next() { }
	// RVA: 0x675fd64 VA: 0x7598d77d64
	public static Int32 CallNext() { }
	// RVA: 0x675fdbc VA: 0x7598d77dbc
	public Int32 Next(Int32 minValue, Int32 maxValue) { }
	// RVA: 0x675fdf4 VA: 0x7598d77df4
	public FP Next(Single minValue, Single maxValue) { }
	// RVA: 0x675ff8c VA: 0x7598d77f8c
	public static Int32 Range(Int32 minValue, Int32 maxValue) { }
	// RVA: 0x6760010 VA: 0x7598d78010
	public static FP Range(Single minValue, Single maxValue) { }
	// RVA: 0x675ff04 VA: 0x7598d77f04
	public FP NextFP() { }
	// RVA: 0x6760078 VA: 0x7598d78078
	public static FP get_value() { }
	// RVA: 0x67600c8 VA: 0x7598d780c8
	public static TSVector3 get_insideUnitSphere() { }
	// RVA: 0x6760108 VA: 0x7598d78108
	private Single NextFloat() { }
	// RVA: 0x676014c VA: 0x7598d7814c
	private Single NextFloat(Boolean includeOne) { }
	// RVA: 0x67601a4 VA: 0x7598d781a4
	private Single NextFloatPositive() { }
	// RVA: 0x67601f8 VA: 0x7598d781f8
	private Double NextDouble() { }
	// RVA: 0x6760218 VA: 0x7598d78218
	private Double NextDouble(Boolean includeOne) { }
	// RVA: 0x676024c VA: 0x7598d7824c
	private Double NextDoublePositive() { }
	// RVA: 0x6760274 VA: 0x7598d78274
	private Double Next53BitRes() { }
	// RVA: 0x67602cc VA: 0x7598d782cc
	public Void Initialize() { }
	// RVA: 0x676034c VA: 0x7598d7834c
	public Void Initialize(Int32 seed) { }
	// RVA: 0x6760350 VA: 0x7598d78350
	public Void Initialize(Int32[] init) { }
	// RVA: 0x675fa04 VA: 0x7598d77a04
	private Void init_genrand(UInt32 s) { }
	// RVA: 0x675fbb0 VA: 0x7598d77bb0
	private Void init_by_array(UInt32[] init_key, UInt32 key_length) { }
	// RVA: 0x676040c VA: 0x7598d7840c
	private UInt32 genrand_int32() { }
	// RVA: 0x675fd50 VA: 0x7598d77d50
	private Int32 genrand_int31() { }
	// RVA: 0x67605d8 VA: 0x7598d785d8
	private FP genrand_FP() { }
	// RVA: 0x6760184 VA: 0x7598d78184
	private Double genrand_real1() { }
	// RVA: 0x676012c VA: 0x7598d7812c
	private Double genrand_real2() { }
	// RVA: 0x67601d0 VA: 0x7598d781d0
	private Double genrand_real3() { }
	// RVA: 0x6760278 VA: 0x7598d78278
	private Double genrand_res53() { }
}
```