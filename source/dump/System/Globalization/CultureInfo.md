# CultureInfo

**Namespace:** `System.Globalization`


## Fields

- `Boolean m_isReadOnly`

- `Int32 cultureID`

- `Int32 parent_lcid`

- `Int32 datetime_index`

- `Int32 number_index`

- `Int32 default_calendar_type`

- `Boolean m_useUserOverride`

- `TextInfo textInfo`

- `String englishname`

- `String nativename`

- `String iso3lang`

- `String iso2lang`

- `String win3lang`

- `String territory`

- `CompareInfo compareInfo`

- `Int32 m_dataItem`

- `Calendar calendar`

- `CultureInfo parent_culture`

- `Boolean constructed`


## Properties

- `Boolean IsReadOnly`


## Methods

- `Data GetTextInfoData()`

- `Void CheckNeutral()`

- `Boolean get_IsReadOnly()`

- `Void Construct()`

- `Boolean construct_internal_locale_from_lcid(Int32)`

- `Boolean construct_internal_locale_from_name(String)`

- `Void ConstructInvariant(Boolean)`

- `TextInfo CreateTextInfo(Boolean)`

- `Boolean ConstructLocaleFromName(String)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Globalization
public class CultureInfo : ICloneable, IFormatProvider
{
	private static CultureInfo invariant_culture_info; // 0x0
	private static Object shared_table_lock; // 0x8
	private static CultureInfo default_current_culture; // 0x10
	private Boolean m_isReadOnly; // 0x10
	private Int32 cultureID; // 0x14
	private Int32 parent_lcid; // 0x18
	private Int32 datetime_index; // 0x1c
	private Int32 number_index; // 0x20
	private Int32 default_calendar_type; // 0x24
	private Boolean m_useUserOverride; // 0x28
	internal NumberFormatInfo numInfo; // 0x30
	internal DateTimeFormatInfo dateTimeInfo; // 0x38
	private TextInfo textInfo; // 0x40
	internal String m_name; // 0x48
	private String englishname; // 0x50
	private String nativename; // 0x58
	private String iso3lang; // 0x60
	private String iso2lang; // 0x68
	private String win3lang; // 0x70
	private String territory; // 0x78
	private String[] native_calendar_names; // 0x80
	private CompareInfo compareInfo; // 0x88
	private readonly Void* textinfo_data; // 0x90
	private Int32 m_dataItem; // 0x98
	private Calendar calendar; // 0xa0
	private CultureInfo parent_culture; // 0xa8
	private Boolean constructed; // 0xb0
	internal Byte[] cached_serialized_form; // 0xb8
	internal CultureData m_cultureData; // 0xc0
	internal Boolean m_isInherited; // 0xc8
	internal const Int32 InvariantCultureId; // 0x0
	private const Int32 CalendarTypeBits; // 0x0
	internal const Int32 LOCALE_INVARIANT; // 0x0
	private const String MSG_READONLY; // 0x0
	private static CultureInfo s_DefaultThreadCurrentUICulture; // 0x18
	private static CultureInfo s_DefaultThreadCurrentCulture; // 0x20
	private static Dictionary`2 shared_by_number; // 0x28
	private static Dictionary`2 shared_by_name; // 0x30
	private static CultureInfo s_UserPreferredCultureInfoInAppX; // 0x38
	internal static readonly Boolean IsTaiwanSku; // 0x40

	internal CultureData _cultureData { get; }
	internal Boolean _isInherited { get; }
	public static CultureInfo InvariantCulture { get; }
	public static CultureInfo CurrentCulture { get; set; }
	public static CultureInfo CurrentUICulture { get; }
	internal String Territory { get; }
	internal String _name { get; }
	public virtual Int32 LCID { get; }
	public virtual String Name { get; }
	public virtual Calendar Calendar { get; }
	public virtual CultureInfo Parent { get; }
	public virtual TextInfo TextInfo { get; }
	public virtual CompareInfo CompareInfo { get; }
	public virtual Boolean IsNeutralCulture { get; }
	public virtual NumberFormatInfo NumberFormat { get; set; }
	public virtual DateTimeFormatInfo DateTimeFormat { get; set; }
	public virtual String EnglishName { get; }
	public Boolean IsReadOnly { get; }
	internal Int32 CalendarType { get; }
	public static CultureInfo DefaultThreadCurrentCulture { get; set; }
	public static CultureInfo DefaultThreadCurrentUICulture { get; }
	internal String SortName { get; }
	internal static CultureInfo UserDefaultUICulture { get; }
	internal static CultureInfo UserDefaultCulture { get; }
	internal Boolean HasInvariantCultureName { get; }

	// RVA: 0x6071c40 VA: 0x7598689c40
	internal CultureData get__cultureData() { }
	// RVA: 0x6071c48 VA: 0x7598689c48
	internal Boolean get__isInherited() { }
	// RVA: 0x6063cf0 VA: 0x759867bcf0
	public static CultureInfo get_InvariantCulture() { }
	// RVA: 0x6063498 VA: 0x759867b498
	public static CultureInfo get_CurrentCulture() { }
	// RVA: 0x6071c50 VA: 0x7598689c50
	public static Void set_CurrentCulture(CultureInfo value) { }
	// RVA: 0x6071c78 VA: 0x7598689c78
	public static CultureInfo get_CurrentUICulture() { }
	// RVA: 0x6071c98 VA: 0x7598689c98
	internal static CultureInfo ConstructCurrentCulture() { }
	// RVA: 0x60720d4 VA: 0x759868a0d4
	internal static CultureInfo ConstructCurrentUICulture() { }
	// RVA: 0x6072120 VA: 0x759868a120
	internal String get_Territory() { }
	// RVA: 0x6072128 VA: 0x759868a128
	internal String get__name() { }
	// RVA: 0x6072130 VA: 0x759868a130
	public virtual Int32 get_LCID() { }
	// RVA: 0x6072138 VA: 0x759868a138
	public virtual String get_Name() { }
	// RVA: 0x6072140 VA: 0x759868a140
	public virtual Calendar get_Calendar() { }
	// RVA: 0x6072430 VA: 0x759868a430
	public virtual CultureInfo get_Parent() { }
	// RVA: 0x60726b8 VA: 0x759868a6b8
	public virtual TextInfo get_TextInfo() { }
	// RVA: 0x6072858 VA: 0x759868a858
	public virtual Object Clone() { }
	// RVA: 0x6072a00 VA: 0x759868aa00
	public override Boolean Equals(Object value) { }
	// RVA: 0x6072aac VA: 0x759868aaac
	public static CultureInfo[] GetCultures(CultureTypes types) { }
	// RVA: 0x6072d34 VA: 0x759868ad34
	private Data GetTextInfoData() { }
	// RVA: 0x6072dc4 VA: 0x759868adc4
	public override Int32 GetHashCode() { }
	// RVA: 0x6072dd0 VA: 0x759868add0
	public static CultureInfo ReadOnly(CultureInfo ci) { }
	// RVA: 0x6072fa4 VA: 0x759868afa4
	public override String ToString() { }
	// RVA: 0x6072fac VA: 0x759868afac
	public virtual CompareInfo get_CompareInfo() { }
	// RVA: 0x607310c VA: 0x759868b10c
	public virtual Boolean get_IsNeutralCulture() { }
	// RVA: 0x6073154 VA: 0x759868b154
	private Void CheckNeutral() { }
	// RVA: 0x6073158 VA: 0x759868b158
	public virtual NumberFormatInfo get_NumberFormat() { }
	// RVA: 0x60731fc VA: 0x759868b1fc
	public virtual Void set_NumberFormat(NumberFormatInfo value) { }
	// RVA: 0x60732d4 VA: 0x759868b2d4
	public virtual DateTimeFormatInfo get_DateTimeFormat() { }
	// RVA: 0x6073440 VA: 0x759868b440
	public virtual Void set_DateTimeFormat(DateTimeFormatInfo value) { }
	// RVA: 0x6073518 VA: 0x759868b518
	public virtual String get_EnglishName() { }
	// RVA: 0x6073548 VA: 0x759868b548
	public Boolean get_IsReadOnly() { }
	// RVA: 0x6073550 VA: 0x759868b550
	public virtual Object GetFormat(Type formatType) { }
	// RVA: 0x60721d8 VA: 0x759868a1d8
	private Void Construct() { }
	// RVA: 0x6073660 VA: 0x759868b660
	private Boolean construct_internal_locale_from_lcid(Int32 lcid) { }
	// RVA: 0x6073664 VA: 0x759868b664
	private Boolean construct_internal_locale_from_name(String name) { }
	// RVA: 0x6071e84 VA: 0x7598689e84
	private static String get_current_locale_name() { }
	// RVA: 0x6072d24 VA: 0x759868ad24
	private static CultureInfo[] internal_get_cultures(Boolean neutral, Boolean specific, Boolean installed) { }
	// RVA: 0x6073668 VA: 0x759868b668
	private Void ConstructInvariant(Boolean read_only) { }
	// RVA: 0x60727dc VA: 0x759868a7dc
	private TextInfo CreateTextInfo(Boolean readOnly) { }
	// RVA: 0x60726ac VA: 0x759868a6ac
	public Void .ctor(Int32 culture) { }
	// RVA: 0x6073830 VA: 0x759868b830
	public Void .ctor(Int32 culture, Boolean useUserOverride) { }
	// RVA: 0x607383c VA: 0x759868b83c
	private Void .ctor(Int32 culture, Boolean useUserOverride, Boolean read_only) { }
	// RVA: 0x60726a0 VA: 0x759868a6a0
	public Void .ctor(String name) { }
	// RVA: 0x6065b9c VA: 0x759867db9c
	public Void .ctor(String name, Boolean useUserOverride) { }
	// RVA: 0x6073afc VA: 0x759868bafc
	private Void .ctor(String name, Boolean useUserOverride, Boolean read_only) { }
	// RVA: 0x6073ebc VA: 0x759868bebc
	private Void .ctor() { }
	// RVA: 0x6073edc VA: 0x759868bedc
	private static Void insert_into_shared_tables(CultureInfo c) { }
	// RVA: 0x6074078 VA: 0x759868c078
	public static CultureInfo GetCultureInfo(Int32 culture) { }
	// RVA: 0x60742bc VA: 0x759868c2bc
	public static CultureInfo GetCultureInfo(String name) { }
	// RVA: 0x60744e8 VA: 0x759868c4e8
	internal static CultureInfo CreateCulture(String name, Boolean reference) { }
	// RVA: 0x6071e88 VA: 0x7598689e88
	public static CultureInfo CreateSpecificCulture(String name) { }
	// RVA: 0x6073d68 VA: 0x759868bd68
	private Boolean ConstructLocaleFromName(String name) { }
	// RVA: 0x607455c VA: 0x759868c55c
	private static CultureInfo CreateSpecificCultureFromNeutral(String name) { }
	// RVA: 0x6072d4c VA: 0x759868ad4c
	internal Int32 get_CalendarType() { }
	// RVA: 0x60721f8 VA: 0x759868a1f8
	private static Calendar CreateCalendar(Int32 calendarType) { }
	// RVA: 0x6073df4 VA: 0x759868bdf4
	private static Exception CreateNotFoundException(String name) { }
	// RVA: 0x6076cb0 VA: 0x759868ecb0
	public static CultureInfo get_DefaultThreadCurrentCulture() { }
	// RVA: 0x6076d10 VA: 0x759868ed10
	public static Void set_DefaultThreadCurrentCulture(CultureInfo value) { }
	// RVA: 0x6076d74 VA: 0x759868ed74
	public static CultureInfo get_DefaultThreadCurrentUICulture() { }
	// RVA: 0x6076dd4 VA: 0x759868edd4
	internal String get_SortName() { }
	// RVA: 0x6076ddc VA: 0x759868eddc
	internal static CultureInfo get_UserDefaultUICulture() { }
	// RVA: 0x6076e28 VA: 0x759868ee28
	internal static CultureInfo get_UserDefaultCulture() { }
	// RVA: 0x6076e74 VA: 0x759868ee74
	private static extern Void InitializeUserPreferredCultureInfoInAppX(OnCultureInfoChangedDelegate onCultureInfoChangedInAppX) { }
	// RVA: 0x6076e84 VA: 0x759868ee84
	private static extern Void SetUserPreferredCultureInfoInAppX(String name) { }
	// RVA: 0x6071b98 VA: 0x7598689b98
	private static Void OnCultureInfoChangedInAppX(String language) { }
	// RVA: 0x6076e94 VA: 0x759868ee94
	internal static CultureInfo GetCultureInfoForUserPreferredLanguageInAppX() { }
	// RVA: 0x6076f74 VA: 0x759868ef74
	internal static Void SetCultureInfoForUserPreferredLanguageInAppX(CultureInfo cultureInfo) { }
	// RVA: 0x6077088 VA: 0x759868f088
	internal Boolean get_HasInvariantCultureName() { }
	// RVA: 0x6077114 VA: 0x759868f114
	internal static Boolean VerifyCultureName(String cultureName, Boolean throwException) { }
	// RVA: 0x6077278 VA: 0x759868f278
	private static Void .cctor() { }
}
```