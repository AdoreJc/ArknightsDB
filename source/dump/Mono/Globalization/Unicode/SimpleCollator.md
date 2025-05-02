# SimpleCollator

**Namespace:** `Mono.Globalization.Unicode`


## Methods

- `Void SetCJKTable(CultureInfo, ref, ref, ref, ref, ref)`

- `Byte Category(Int32)`

- `Byte Level1(Int32)`

- `Byte Level2(Int32, ExtenderType)`

- `Contraction GetContraction(String, Int32, Int32)`

- `Contraction GetContraction(String, Int32, Int32, Contraction[])`

- `Contraction GetTailContraction(String, Int32, Int32)`

- `Contraction GetTailContraction(String, Int32, Int32, Contraction[])`

- `Int32 FilterOptions(Int32, CompareOptions)`

- `ExtenderType GetExtenderType(Int32)`

- `Int32 FilterExtender(Int32, ExtenderType, CompareOptions)`

- `Boolean IsSafe(Int32)`

- `SortKey GetSortKey(String, CompareOptions)`

- `SortKey GetSortKey(String, Int32, Int32, CompareOptions)`

- `Void GetSortKey(String, Int32, Int32, SortKeyBuffer, CompareOptions)`

- `Void FillSortKeyRaw(Int32, ExtenderType, SortKeyBuffer, CompareOptions)`

- `Void FillSurrogateSortKeyRaw(Int32, SortKeyBuffer)`

- `Void ClearBuffer(Byte*, Int32)`

- `Int32 CompareInternal(String, Int32, Int32, String, Int32, Int32, out, out, Boolean, Boolean, ref)`

- `Int32 CompareFlagPair(Boolean, Boolean)`

- `Boolean IsPrefix(String, String, CompareOptions)`

- `Boolean IsPrefix(String, String, Int32, Int32, CompareOptions)`

- `Boolean IsPrefix(String, String, Int32, Int32, Boolean, ref)`

- `Boolean IsSuffix(String, String, CompareOptions)`

- `Boolean IsSuffix(String, String, Int32, Int32, CompareOptions)`

- `Int32 QuickIndexOf(String, String, Int32, Int32, out)`

- `Int32 IndexOf(String, String, Int32, Int32, CompareOptions)`

- `Int32 IndexOfOrdinal(String, String, Int32, Int32)`

- `Int32 IndexOfOrdinal(String, Char, Int32, Int32)`

- `Int32 IndexOfSortKey(String, Int32, Int32, Byte*, Char, Int32, Boolean, ref)`

- `Int32 IndexOf(String, String, Int32, Int32, Byte*, ref)`

- `Int32 LastIndexOf(String, String, Int32, Int32, CompareOptions)`

- `Int32 LastIndexOfOrdinal(String, String, Int32, Int32)`

- `Int32 LastIndexOfSortKey(String, Int32, Int32, Int32, Byte*, Int32, Boolean, ref)`

- `Int32 LastIndexOf(String, String, Int32, Int32, Byte*, ref)`

- `Boolean MatchesForward(String, ref, Int32, Int32, Byte*, Boolean, ref)`

- `Boolean MatchesForwardCore(String, ref, Int32, Int32, Byte*, Boolean, ExtenderType, ref, ref)`

- `Boolean MatchesPrimitive(CompareOptions, Byte*, Int32, ExtenderType, Byte*, Int32, Boolean)`

- `Boolean MatchesBackward(String, ref, Int32, Int32, Int32, Byte*, Boolean, ref)`

- `Boolean MatchesBackwardCore(String, ref, Int32, Int32, Int32, Byte*, Boolean, ExtenderType, ref, ref)`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : Mono.Globalization.Unicode
internal class SimpleCollator : ISimpleCollator
{
	private static SimpleCollator invariant; // 0x0
	private readonly TextInfo textInfo; // 0x10
	private readonly CodePointIndexer cjkIndexer; // 0x18
	private readonly Contraction[] contractions; // 0x20
	private readonly Level2Map[] level2Maps; // 0x28
	private readonly Byte[] unsafeFlags; // 0x30
	private readonly Byte* cjkCatTable; // 0x38
	private readonly Byte* cjkLv1Table; // 0x40
	private readonly Byte* cjkLv2Table; // 0x48
	private readonly CodePointIndexer cjkLv2Indexer; // 0x50
	private readonly Int32 lcid; // 0x58
	private readonly Boolean frenchSort; // 0x5c


	// RVA: 0x5efde18 VA: 0x7598515e18
	public Void .ctor(CultureInfo culture) { }
	// RVA: 0x5efe164 VA: 0x7598516164
	private Void SetCJKTable(CultureInfo culture, ref CodePointIndexer cjkIndexer, ref Byte* catTable, ref Byte* lv1Table, ref CodePointIndexer lv2Indexer, ref Byte* lv2Table) { }
	// RVA: 0x5efe240 VA: 0x7598516240
	private static CultureInfo GetNeutralCulture(CultureInfo info) { }
	// RVA: 0x5efe2b0 VA: 0x75985162b0
	private Byte Category(Int32 cp) { }
	// RVA: 0x5efe344 VA: 0x7598516344
	private Byte Level1(Int32 cp) { }
	// RVA: 0x5efe3d8 VA: 0x75985163d8
	private Byte Level2(Int32 cp, ExtenderType ext) { }
	// RVA: 0x5efe504 VA: 0x7598516504
	private static Boolean IsHalfKana(Int32 cp, CompareOptions opt) { }
	// RVA: 0x5efe578 VA: 0x7598516578
	private Contraction GetContraction(String s, Int32 start, Int32 end) { }
	// RVA: 0x5efe638 VA: 0x7598516638
	private Contraction GetContraction(String s, Int32 start, Int32 end, Contraction[] clist) { }
	// RVA: 0x5efe75c VA: 0x759851675c
	private Contraction GetTailContraction(String s, Int32 start, Int32 end) { }
	// RVA: 0x5efe81c VA: 0x759851681c
	private Contraction GetTailContraction(String s, Int32 start, Int32 end, Contraction[] clist) { }
	// RVA: 0x5efea0c VA: 0x7598516a0c
	private Int32 FilterOptions(Int32 i, CompareOptions opt) { }
	// RVA: 0x5efeaf8 VA: 0x7598516af8
	private ExtenderType GetExtenderType(Int32 i) { }
	// RVA: 0x5efebfc VA: 0x7598516bfc
	private static Byte ToDashTypeValue(ExtenderType ext, CompareOptions opt) { }
	// RVA: 0x5efec1c VA: 0x7598516c1c
	private Int32 FilterExtender(Int32 i, ExtenderType ext, CompareOptions opt) { }
	// RVA: 0x5efee30 VA: 0x7598516e30
	private static Boolean IsIgnorable(Int32 i, CompareOptions opt) { }
	// RVA: 0x5efeeb4 VA: 0x7598516eb4
	private Boolean IsSafe(Int32 i) { }
	// RVA: 0x5efef14 VA: 0x7598516f14
	public SortKey GetSortKey(String s, CompareOptions options) { }
	// RVA: 0x5efef34 VA: 0x7598516f34
	public SortKey GetSortKey(String s, Int32 start, Int32 length, CompareOptions options) { }
	// RVA: 0x5eff218 VA: 0x7598517218
	private Void GetSortKey(String s, Int32 start, Int32 end, SortKeyBuffer buf, CompareOptions opt) { }
	// RVA: 0x5eff5f0 VA: 0x75985175f0
	private Void FillSortKeyRaw(Int32 i, ExtenderType ext, SortKeyBuffer buf, CompareOptions opt) { }
	// RVA: 0x5effb68 VA: 0x7598517b68
	private Void FillSurrogateSortKeyRaw(Int32 i, SortKeyBuffer buf) { }
	// RVA: 0x5effcb0 VA: 0x7598517cb0
	private Int32 System.Globalization.ISimpleCollator.Compare(String s1, Int32 idx1, Int32 len1, String s2, Int32 idx2, Int32 len2, CompareOptions options) { }
	// RVA: 0x5effcb4 VA: 0x7598517cb4
	internal Int32 Compare(String s1, Int32 idx1, Int32 len1, String s2, Int32 idx2, Int32 len2, CompareOptions options) { }
	// RVA: 0x5eff5b8 VA: 0x75985175b8
	private Void ClearBuffer(Byte* buffer, Int32 size) { }
	// RVA: 0x5effd68 VA: 0x7598517d68
	private Int32 CompareInternal(String s1, Int32 idx1, Int32 len1, String s2, Int32 idx2, Int32 len2, out Boolean targetConsumed, out Boolean sourceConsumed, Boolean skipHeadingExtenders, Boolean immediateBreakup, ref Context ctx) { }
	// RVA: 0x5f0101c VA: 0x759851901c
	private Int32 CompareFlagPair(Boolean b1, Boolean b2) { }
	// RVA: 0x5f0103c VA: 0x759851903c
	public Boolean IsPrefix(String src, String target, CompareOptions opt) { }
	// RVA: 0x5f0105c VA: 0x759851905c
	public Boolean IsPrefix(String s, String target, Int32 start, Int32 length, CompareOptions opt) { }
	// RVA: 0x5f0110c VA: 0x759851910c
	private Boolean IsPrefix(String s, String target, Int32 start, Int32 length, Boolean skipHeadingExtenders, ref Context ctx) { }
	// RVA: 0x5f01174 VA: 0x7598519174
	public Boolean IsSuffix(String src, String target, CompareOptions opt) { }
	// RVA: 0x5f01194 VA: 0x7598519194
	public Boolean IsSuffix(String s, String target, Int32 start, Int32 length, CompareOptions opt) { }
	// RVA: 0x5f013b4 VA: 0x75985193b4
	private Int32 QuickIndexOf(String s, String target, Int32 start, Int32 length, out Boolean testWasUnable) { }
	// RVA: 0x5f0151c VA: 0x759851951c
	public Int32 IndexOf(String s, String target, Int32 start, Int32 length, CompareOptions opt) { }
	// RVA: 0x5f01bac VA: 0x7598519bac
	private Int32 IndexOfOrdinal(String s, String target, Int32 start, Int32 length) { }
	// RVA: 0x5f01c84 VA: 0x7598519c84
	private Int32 IndexOfOrdinal(String s, Char target, Int32 start, Int32 length) { }
	// RVA: 0x5f01cf4 VA: 0x7598519cf4
	private Int32 IndexOfSortKey(String s, Int32 start, Int32 length, Byte* sortkey, Char target, Int32 ti, Boolean noLv4, ref Context ctx) { }
	// RVA: 0x5f01710 VA: 0x7598519710
	private Int32 IndexOf(String s, String target, Int32 start, Int32 length, Byte* targetSortKey, ref Context ctx) { }
	// RVA: 0x5f01228 VA: 0x7598519228
	public Int32 LastIndexOf(String s, String target, Int32 start, Int32 length, CompareOptions opt) { }
	// RVA: 0x5f02468 VA: 0x759851a468
	private Int32 LastIndexOfOrdinal(String s, String target, Int32 start, Int32 length) { }
	// RVA: 0x5f0259c VA: 0x759851a59c
	private Int32 LastIndexOfSortKey(String s, Int32 start, Int32 orgStart, Int32 length, Byte* sortkey, Int32 ti, Boolean noLv4, ref Context ctx) { }
	// RVA: 0x5f01f48 VA: 0x7598519f48
	private Int32 LastIndexOf(String s, String target, Int32 start, Int32 length, Byte* targetSortKey, ref Context ctx) { }
	// RVA: 0x5f01d90 VA: 0x7598519d90
	private Boolean MatchesForward(String s, ref Int32 idx, Int32 end, Int32 ti, Byte* sortkey, Boolean noLv4, ref Context ctx) { }
	// RVA: 0x5f02804 VA: 0x759851a804
	private Boolean MatchesForwardCore(String s, ref Int32 idx, Int32 end, Int32 ti, Byte* sortkey, Boolean noLv4, ExtenderType ext, ref Contraction ct, ref Context ctx) { }
	// RVA: 0x5f02b60 VA: 0x759851ab60
	private Boolean MatchesPrimitive(CompareOptions opt, Byte* source, Int32 si, ExtenderType ext, Byte* target, Int32 ti, Boolean noLv4) { }
	// RVA: 0x5f02640 VA: 0x759851a640
	private Boolean MatchesBackward(String s, ref Int32 idx, Int32 end, Int32 orgStart, Int32 ti, Byte* sortkey, Boolean noLv4, ref Context ctx) { }
	// RVA: 0x5f02d8c VA: 0x759851ad8c
	private Boolean MatchesBackwardCore(String s, ref Int32 idx, Int32 end, Int32 orgStart, Int32 ti, Byte* sortkey, Boolean noLv4, ExtenderType ext, ref Contraction ct, ref Context ctx) { }
	// RVA: 0x5f03230 VA: 0x759851b230
	private static Void .cctor() { }
}
```