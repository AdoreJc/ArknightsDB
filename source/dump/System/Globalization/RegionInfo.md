# RegionInfo

**Namespace:** `System.Globalization`


## Fields

- `Int32 regionId`

- `String iso2Name`

- `String iso3Name`

- `String win3Name`

- `String englishName`

- `String nativeName`

- `String currencySymbol`

- `String isoCurrencySymbol`

- `String currencyEnglishName`

- `String currencyNativeName`


## Methods

- `Boolean GetByTerritory(CultureInfo)`

- `Boolean construct_internal_region_from_name(String)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Globalization
public class RegionInfo
{
	private static RegionInfo currentRegion; // 0x0
	private Int32 regionId; // 0x10
	private String iso2Name; // 0x18
	private String iso3Name; // 0x20
	private String win3Name; // 0x28
	private String englishName; // 0x30
	private String nativeName; // 0x38
	private String currencySymbol; // 0x40
	private String isoCurrencySymbol; // 0x48
	private String currencyEnglishName; // 0x50
	private String currencyNativeName; // 0x58

	public static RegionInfo CurrentRegion { get; }
	public virtual String CurrencyEnglishName { get; }
	public virtual String CurrencySymbol { get; }
	public virtual String DisplayName { get; }
	public virtual String EnglishName { get; }
	public virtual Int32 GeoId { get; }
	public virtual Boolean IsMetric { get; }
	public virtual String ISOCurrencySymbol { get; }
	public virtual String NativeName { get; }
	public virtual String CurrencyNativeName { get; }
	public virtual String Name { get; }
	public virtual String ThreeLetterISORegionName { get; }
	public virtual String ThreeLetterWindowsRegionName { get; }
	public virtual String TwoLetterISORegionName { get; }

	// RVA: 0x6078bdc VA: 0x7598690bdc
	public static RegionInfo get_CurrentRegion() { }
	// RVA: 0x6078eb4 VA: 0x7598690eb4
	public Void .ctor(Int32 culture) { }
	// RVA: 0x607906c VA: 0x759869106c
	public Void .ctor(String name) { }
	// RVA: 0x6078ca8 VA: 0x7598690ca8
	private Void .ctor(CultureInfo ci) { }
	// RVA: 0x6078fc0 VA: 0x7598690fc0
	private Boolean GetByTerritory(CultureInfo ci) { }
	// RVA: 0x60791b0 VA: 0x75986911b0
	private Boolean construct_internal_region_from_name(String name) { }
	// RVA: 0x60791b4 VA: 0x75986911b4
	public virtual String get_CurrencyEnglishName() { }
	// RVA: 0x60791bc VA: 0x75986911bc
	public virtual String get_CurrencySymbol() { }
	// RVA: 0x60791c4 VA: 0x75986911c4
	public virtual String get_DisplayName() { }
	// RVA: 0x60791cc VA: 0x75986911cc
	public virtual String get_EnglishName() { }
	// RVA: 0x60791d4 VA: 0x75986911d4
	public virtual Int32 get_GeoId() { }
	// RVA: 0x60791dc VA: 0x75986911dc
	public virtual Boolean get_IsMetric() { }
	// RVA: 0x6079268 VA: 0x7598691268
	public virtual String get_ISOCurrencySymbol() { }
	// RVA: 0x6079270 VA: 0x7598691270
	public virtual String get_NativeName() { }
	// RVA: 0x6079278 VA: 0x7598691278
	public virtual String get_CurrencyNativeName() { }
	// RVA: 0x6079280 VA: 0x7598691280
	public virtual String get_Name() { }
	// RVA: 0x6079288 VA: 0x7598691288
	public virtual String get_ThreeLetterISORegionName() { }
	// RVA: 0x6079290 VA: 0x7598691290
	public virtual String get_ThreeLetterWindowsRegionName() { }
	// RVA: 0x6079298 VA: 0x7598691298
	public virtual String get_TwoLetterISORegionName() { }
	// RVA: 0x60792a0 VA: 0x75986912a0
	public override Boolean Equals(Object value) { }
	// RVA: 0x6079368 VA: 0x7598691368
	public override Int32 GetHashCode() { }
	// RVA: 0x6079394 VA: 0x7598691394
	public override String ToString() { }
	// RVA: 0x60793a4 VA: 0x75986913a4
	internal static Void ClearCachedData() { }
}
```