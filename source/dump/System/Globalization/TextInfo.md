# TextInfo

**Namespace:** `System.Globalization`


## Fields

- `String m_listSeparator`

- `Boolean m_isReadOnly`

- `String m_cultureName`

- `CultureData m_cultureData`

- `String m_textInfoName`

- `String customCultureName`


## Properties

- `String CultureName`

- `Boolean IsReadOnly`

- `Boolean IsAsciiCasingSameAsInvariant`


## Methods

- `Void OnDeserializing(StreamingContext)`

- `Void OnDeserialized()`

- `Void OnDeserialized(StreamingContext)`

- `Void OnSerializing(StreamingContext)`

- `String get_CultureName()`

- `Boolean get_IsReadOnly()`

- `Boolean get_IsAsciiCasingSameAsInvariant()`

- `String ToUpperInternal(String)`

- `String ToLowerInternal(String)`

- `Char ToUpperInternal(Char)`

- `Char ToLowerInternal(Char)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Globalization
public class TextInfo : ICloneable, IDeserializationCallback
{
	private String m_listSeparator; // 0x10
	private Boolean m_isReadOnly; // 0x18
	private String m_cultureName; // 0x20
	private CultureData m_cultureData; // 0x28
	private String m_textInfoName; // 0x30
	private Nullable`1 m_IsAsciiCasingSameAsInvariant; // 0x38
	internal static TextInfo s_Invariant; // 0x0
	private String customCultureName; // 0x40
	internal Int32 m_nDataItem; // 0x48
	internal Boolean m_useUserOverride; // 0x4c
	internal Int32 m_win32LangID; // 0x50
	private const Int32 wordSeparatorMask; // 0x0

	internal static TextInfo Invariant { get; }
	public virtual Int32 OEMCodePage { get; }
	public String CultureName { get; }
	public Boolean IsReadOnly { get; }
	private Boolean IsAsciiCasingSameAsInvariant { get; }

	// RVA: 0x6061b84 VA: 0x7598679b84
	internal static TextInfo get_Invariant() { }
	// RVA: 0x6061c34 VA: 0x7598679c34
	internal Void .ctor(CultureData cultureData) { }
	// RVA: 0x6061ca0 VA: 0x7598679ca0
	private Void OnDeserializing(StreamingContext ctx) { }
	// RVA: 0x6061cc8 VA: 0x7598679cc8
	private Void OnDeserialized() { }
	// RVA: 0x6061de8 VA: 0x7598679de8
	private Void OnDeserialized(StreamingContext ctx) { }
	// RVA: 0x6061dec VA: 0x7598679dec
	private Void OnSerializing(StreamingContext ctx) { }
	// RVA: 0x6061e78 VA: 0x7598679e78
	public virtual Int32 get_OEMCodePage() { }
	// RVA: 0x6061e94 VA: 0x7598679e94
	public String get_CultureName() { }
	// RVA: 0x6061e9c VA: 0x7598679e9c
	public Boolean get_IsReadOnly() { }
	// RVA: 0x6061ea4 VA: 0x7598679ea4
	public virtual Object Clone() { }
	// RVA: 0x6061f2c VA: 0x7598679f2c
	public static TextInfo ReadOnly(TextInfo textInfo) { }
	// RVA: 0x606201c VA: 0x759867a01c
	internal Void SetReadOnlyState(Boolean readOnly) { }
	// RVA: 0x6062028 VA: 0x759867a028
	public virtual Char ToLower(Char c) { }
	// RVA: 0x60625fc VA: 0x759867a5fc
	public virtual String ToLower(String str) { }
	// RVA: 0x60621a0 VA: 0x759867a1a0
	private static Char ToLowerAsciiInvariant(Char c) { }
	// RVA: 0x6062738 VA: 0x759867a738
	public virtual Char ToUpper(Char c) { }
	// RVA: 0x6062c18 VA: 0x759867ac18
	public virtual String ToUpper(String str) { }
	// RVA: 0x606279c VA: 0x759867a79c
	internal static Char ToUpperAsciiInvariant(Char c) { }
	// RVA: 0x606208c VA: 0x759867a08c
	private static Boolean IsAscii(Char c) { }
	// RVA: 0x606209c VA: 0x759867a09c
	private Boolean get_IsAsciiCasingSameAsInvariant() { }
	// RVA: 0x6062d54 VA: 0x759867ad54
	public override Boolean Equals(Object obj) { }
	// RVA: 0x6062df4 VA: 0x759867adf4
	public override Int32 GetHashCode() { }
	// RVA: 0x6062e14 VA: 0x759867ae14
	public override String ToString() { }
	// RVA: 0x6062e6c VA: 0x759867ae6c
	private Void System.Runtime.Serialization.IDeserializationCallback.OnDeserialization(Object sender) { }
	// RVA: 0x6062c70 VA: 0x759867ac70
	private String ToUpperInternal(String str) { }
	// RVA: 0x6062654 VA: 0x759867a654
	private String ToLowerInternal(String str) { }
	// RVA: 0x60627b8 VA: 0x759867a7b8
	private Char ToUpperInternal(Char c) { }
	// RVA: 0x60621bc VA: 0x759867a1bc
	private Char ToLowerInternal(Char c) { }
	// RVA: 0x6062e70 VA: 0x759867ae70
	internal Void ToUpperAsciiInvariant(ReadOnlySpan`1 source, Span`1 destination) { }
	// RVA: 0x6062f00 VA: 0x759867af00
	internal Void ChangeCase(ReadOnlySpan`1 source, Span`1 destination, Boolean toUpper) { }
	// RVA: 0x6063040 VA: 0x759867b040
	internal Void .ctor() { }
}
```