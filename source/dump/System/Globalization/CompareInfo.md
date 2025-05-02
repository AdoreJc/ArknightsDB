# CompareInfo

**Namespace:** `System.Globalization`


## Fields

- `String m_name`

- `String _sortName`

- `SortVersion m_SortVersion`

- `Int32 culture`

- `ISimpleCollator collator`


## Methods

- `SortKey InvariantCreateSortKey(String, CompareOptions)`

- `Void OnDeserializing(StreamingContext)`

- `Void OnDeserialized(StreamingContext)`

- `Void OnDeserialized()`

- `Void OnSerializing(StreamingContext)`

- `ISimpleCollator GetCollator()`

- `SortKey CreateSortKeyCore(String, CompareOptions)`

- `Int32 internal_index_switch(String, Int32, Int32, String, CompareOptions, Boolean)`

- `Int32 internal_compare_switch(String, Int32, Int32, String, Int32, Int32, CompareOptions)`

- `Int32 internal_compare_managed(String, Int32, Int32, String, Int32, Int32, CompareOptions)`

- `Int32 internal_index_managed(String, Int32, Int32, String, CompareOptions, Boolean)`

- `Void InitSort(CultureInfo)`

- `Int32 LastIndexOfCore(String, String, Int32, Int32, CompareOptions)`

- `Int32 IndexOfCore(String, String, Int32, Int32, CompareOptions, Int32*)`

- `Int32 CompareString(ReadOnlySpan`1, String, CompareOptions)`

- `Int32 CompareString(ReadOnlySpan`1, ReadOnlySpan`1, CompareOptions)`

- `SortKey CreateSortKey(String, CompareOptions)`

- `Boolean StartsWith(String, String, CompareOptions)`

- `Boolean EndsWith(String, String, CompareOptions)`

- `Boolean EndsWith(ReadOnlySpan`1, ReadOnlySpan`1, CompareOptions)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Globalization
public class CompareInfo : IDeserializationCallback
{
	private const CompareOptions ValidIndexMaskOffFlags; // 0x0
	private const CompareOptions ValidCompareMaskOffFlags; // 0x0
	private const CompareOptions ValidHashCodeOfStringMaskOffFlags; // 0x0
	private const CompareOptions ValidSortkeyCtorMaskOffFlags; // 0x0
	internal static readonly CompareInfo Invariant; // 0x0
	private String m_name; // 0x10
	private String _sortName; // 0x18
	private SortVersion m_SortVersion; // 0x20
	private Int32 culture; // 0x28
	private ISimpleCollator collator; // 0x30
	private static Dictionary`2 collators; // 0x8
	private static Boolean managedCollation; // 0x10
	private static Boolean managedCollationChecked; // 0x11

	public virtual String Name { get; }
	private static Boolean UseManagedCollation { get; }

	// RVA: 0x6040b5c VA: 0x7598658b5c
	internal static Int32 InvariantIndexOf(String source, String value, Int32 startIndex, Int32 count, Boolean ignoreCase) { }
	// RVA: 0x6040f4c VA: 0x7598658f4c
	internal static Int32 InvariantLastIndexOf(String source, String value, Int32 startIndex, Int32 count, Boolean ignoreCase) { }
	// RVA: 0x6040c20 VA: 0x7598658c20
	private static Int32 InvariantFindString(Char* source, Int32 sourceCount, Char* value, Int32 valueCount, Boolean ignoreCase, Boolean start) { }
	// RVA: 0x6041018 VA: 0x7598659018
	private static Char InvariantToUpper(Char c) { }
	// RVA: 0x6041030 VA: 0x7598659030
	private SortKey InvariantCreateSortKey(String source, CompareOptions options) { }
	// RVA: 0x60412cc VA: 0x75986592cc
	internal Void .ctor(CultureInfo culture) { }
	// RVA: 0x6041330 VA: 0x7598659330
	public static CompareInfo GetCompareInfo(String name) { }
	// RVA: 0x60413ec VA: 0x75986593ec
	private Void OnDeserializing(StreamingContext ctx) { }
	// RVA: 0x60413f8 VA: 0x75986593f8
	private Void System.Runtime.Serialization.IDeserializationCallback.OnDeserialization(Object sender) { }
	// RVA: 0x60414ac VA: 0x75986594ac
	private Void OnDeserialized(StreamingContext ctx) { }
	// RVA: 0x60413fc VA: 0x75986593fc
	private Void OnDeserialized() { }
	// RVA: 0x60414b0 VA: 0x75986594b0
	private Void OnSerializing(StreamingContext ctx) { }
	// RVA: 0x604153c VA: 0x759865953c
	public virtual String get_Name() { }
	// RVA: 0x60415c8 VA: 0x75986595c8
	public virtual Int32 Compare(String string1, String string2) { }
	// RVA: 0x60415d8 VA: 0x75986595d8
	public virtual Int32 Compare(String string1, String string2, CompareOptions options) { }
	// RVA: 0x6041b70 VA: 0x7598659b70
	internal Int32 Compare(ReadOnlySpan`1 string1, String string2, CompareOptions options) { }
	// RVA: 0x6041f74 VA: 0x7598659f74
	internal Int32 CompareOptionIgnoreCase(ReadOnlySpan`1 string1, ReadOnlySpan`1 string2) { }
	// RVA: 0x60421a0 VA: 0x759865a1a0
	public virtual Int32 Compare(String string1, Int32 offset1, Int32 length1, String string2, Int32 offset2, Int32 length2, CompareOptions options) { }
	// RVA: 0x6042700 VA: 0x759865a700
	internal static Int32 CompareOrdinalIgnoreCase(String strA, Int32 indexA, Int32 lengthA, String strB, Int32 indexB, Int32 lengthB) { }
	// RVA: 0x6041880 VA: 0x7598659880
	internal static Int32 CompareOrdinalIgnoreCase(ReadOnlySpan`1 strA, ReadOnlySpan`1 strB) { }
	// RVA: 0x60429d4 VA: 0x759865a9d4
	public virtual Boolean IsPrefix(String source, String prefix, CompareOptions options) { }
	// RVA: 0x6042d6c VA: 0x759865ad6c
	public virtual Boolean IsSuffix(String source, String suffix, CompareOptions options) { }
	// RVA: 0x6043100 VA: 0x759865b100
	internal Boolean IsSuffix(ReadOnlySpan`1 source, ReadOnlySpan`1 suffix, CompareOptions options) { }
	// RVA: 0x6043164 VA: 0x759865b164
	public virtual Int32 IndexOf(String source, String value, CompareOptions options) { }
	// RVA: 0x60431d4 VA: 0x759865b1d4
	public virtual Int32 IndexOf(String source, String value, Int32 startIndex, Int32 count, CompareOptions options) { }
	// RVA: 0x6043498 VA: 0x759865b498
	internal Int32 IndexOfOrdinal(String source, String value, Int32 startIndex, Int32 count, Boolean ignoreCase) { }
	// RVA: 0x6043614 VA: 0x759865b614
	public virtual Int32 LastIndexOf(String source, String value, CompareOptions options) { }
	// RVA: 0x6043688 VA: 0x759865b688
	public virtual Int32 LastIndexOf(String source, String value, Int32 startIndex, Int32 count, CompareOptions options) { }
	// RVA: 0x60439e4 VA: 0x759865b9e4
	internal Int32 LastIndexOfOrdinal(String source, String value, Int32 startIndex, Int32 count, Boolean ignoreCase) { }
	// RVA: 0x6043b1c VA: 0x759865bb1c
	public virtual SortKey GetSortKey(String source, CompareOptions options) { }
	// RVA: 0x6043ca4 VA: 0x759865bca4
	public override Boolean Equals(Object value) { }
	// RVA: 0x6043d64 VA: 0x759865bd64
	public override Int32 GetHashCode() { }
	// RVA: 0x6043d8c VA: 0x759865bd8c
	internal static Int32 GetIgnoreCaseHash(String source) { }
	// RVA: 0x6044208 VA: 0x759865c208
	internal Int32 GetHashCodeOfString(String source, CompareOptions options) { }
	// RVA: 0x60443dc VA: 0x759865c3dc
	public virtual Int32 GetHashCode(String source, CompareOptions options) { }
	// RVA: 0x60444e0 VA: 0x759865c4e0
	public override String ToString() { }
	// RVA: 0x6044540 VA: 0x759865c540
	private static Boolean get_UseManagedCollation() { }
	// RVA: 0x6044684 VA: 0x759865c684
	private ISimpleCollator GetCollator() { }
	// RVA: 0x60449c4 VA: 0x759865c9c4
	private SortKey CreateSortKeyCore(String source, CompareOptions options) { }
	// RVA: 0x6044b00 VA: 0x759865cb00
	private Int32 internal_index_switch(String s1, Int32 sindex, Int32 count, String s2, CompareOptions opt, Boolean first) { }
	// RVA: 0x6041a74 VA: 0x7598659a74
	private Int32 internal_compare_switch(String str1, Int32 offset1, Int32 length1, String str2, Int32 offset2, Int32 length2, CompareOptions options) { }
	// RVA: 0x6044ed0 VA: 0x759865ced0
	private Int32 internal_compare_managed(String str1, Int32 offset1, Int32 length1, String str2, Int32 offset2, Int32 length2, CompareOptions options) { }
	// RVA: 0x6044cf0 VA: 0x759865ccf0
	private Int32 internal_index_managed(String s1, Int32 sindex, Int32 count, String s2, CompareOptions opt, Boolean first) { }
	// RVA: 0x6044fd0 VA: 0x759865cfd0
	private static Int32 internal_compare_icall(Char* str1, Int32 length1, Char* str2, Int32 length2, CompareOptions options) { }
	// RVA: 0x6044e1c VA: 0x759865ce1c
	private static Int32 internal_compare(String str1, Int32 offset1, Int32 length1, String str2, Int32 offset2, Int32 length2, CompareOptions options) { }
	// RVA: 0x6044fd4 VA: 0x759865cfd4
	private static Int32 internal_index_icall(Char* source, Int32 sindex, Int32 count, Char* value, Int32 value_length, Boolean first) { }
	// RVA: 0x6044c3c VA: 0x759865cc3c
	private static Int32 internal_index(String source, Int32 sindex, Int32 count, String value, Boolean first) { }
	// RVA: 0x6041314 VA: 0x7598659314
	private Void InitSort(CultureInfo culture) { }
	// RVA: 0x6042874 VA: 0x759865a874
	private static Int32 CompareStringOrdinalIgnoreCase(Char* pString1, Int32 length1, Char* pString2, Int32 length2) { }
	// RVA: 0x60435f4 VA: 0x759865b5f4
	internal static Int32 IndexOfOrdinalCore(String source, String value, Int32 startIndex, Int32 count, Boolean ignoreCase) { }
	// RVA: 0x6043afc VA: 0x759865bafc
	internal static Int32 LastIndexOfOrdinalCore(String source, String value, Int32 startIndex, Int32 count, Boolean ignoreCase) { }
	// RVA: 0x6043ae4 VA: 0x759865bae4
	private Int32 LastIndexOfCore(String source, String target, Int32 startIndex, Int32 count, CompareOptions options) { }
	// RVA: 0x6043598 VA: 0x759865b598
	private Int32 IndexOfCore(String source, String target, Int32 startIndex, Int32 count, CompareOptions options, Int32* matchLengthPtr) { }
	// RVA: 0x6041f10 VA: 0x7598659f10
	private Int32 CompareString(ReadOnlySpan`1 string1, String string2, CompareOptions options) { }
	// RVA: 0x60420b0 VA: 0x759865a0b0
	private Int32 CompareString(ReadOnlySpan`1 string1, ReadOnlySpan`1 string2, CompareOptions options) { }
	// RVA: 0x6043be4 VA: 0x759865bbe4
	private SortKey CreateSortKey(String source, CompareOptions options) { }
	// RVA: 0x6042bf8 VA: 0x759865abf8
	private Boolean StartsWith(String source, String prefix, CompareOptions options) { }
	// RVA: 0x6042f90 VA: 0x759865af90
	private Boolean EndsWith(String source, String suffix, CompareOptions options) { }
	// RVA: 0x6043104 VA: 0x759865b104
	private Boolean EndsWith(ReadOnlySpan`1 source, ReadOnlySpan`1 suffix, CompareOptions options) { }
	// RVA: 0x60443b0 VA: 0x759865c3b0
	internal Int32 GetHashCodeOfStringCore(String source, CompareOptions options) { }
	// RVA: 0x6044fdc VA: 0x759865cfdc
	private static Void .cctor() { }
	// RVA: 0x6045070 VA: 0x759865d070
	internal Void .ctor() { }
}
```