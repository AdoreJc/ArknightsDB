# MSCompatUnicodeTable

**Namespace:** `Mono.Globalization.Unicode`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : Mono.Globalization.Unicode
internal class MSCompatUnicodeTable
{
	public static Int32 MaxExpansionLength; // 0x0
	private static readonly Byte* ignorableFlags; // 0x8
	private static readonly Byte* categories; // 0x10
	private static readonly Byte* level1; // 0x18
	private static readonly Byte* level2; // 0x20
	private static readonly Byte* level3; // 0x28
	private static Byte* cjkCHScategory; // 0x30
	private static Byte* cjkCHTcategory; // 0x38
	private static Byte* cjkJAcategory; // 0x40
	private static Byte* cjkKOcategory; // 0x48
	private static Byte* cjkCHSlv1; // 0x50
	private static Byte* cjkCHTlv1; // 0x58
	private static Byte* cjkJAlv1; // 0x60
	private static Byte* cjkKOlv1; // 0x68
	private static Byte* cjkKOlv2; // 0x70
	private static readonly Char[] tailoringArr; // 0x78
	private static readonly TailoringInfo[] tailoringInfos; // 0x80
	private static Object forLock; // 0x88
	public static readonly Boolean isReady; // 0x90

	public static Boolean IsReady { get; }

	// RVA: 0x5efb624 VA: 0x7598513624
	public static TailoringInfo GetTailoringInfo(Int32 lcid) { }
	// RVA: 0x5efb728 VA: 0x7598513728
	public static Void BuildTailoringTables(CultureInfo culture, TailoringInfo t, ref Contraction[] contractions, ref Level2Map[] diacriticals) { }
	// RVA: 0x5efbea8 VA: 0x7598513ea8
	private static Void SetCJKReferences(String name, ref CodePointIndexer cjkIndexer, ref Byte* catTable, ref Byte* lv1Table, ref CodePointIndexer lv2Indexer, ref Byte* lv2Table) { }
	// RVA: 0x5efc104 VA: 0x7598514104
	public static Byte Category(Int32 cp) { }
	// RVA: 0x5efc1a8 VA: 0x75985141a8
	public static Byte Level1(Int32 cp) { }
	// RVA: 0x5efc24c VA: 0x759851424c
	public static Byte Level2(Int32 cp) { }
	// RVA: 0x5efc2f0 VA: 0x75985142f0
	public static Byte Level3(Int32 cp) { }
	// RVA: 0x5efc394 VA: 0x7598514394
	public static Boolean IsIgnorable(Int32 cp, Byte flag) { }
	// RVA: 0x5efc4ac VA: 0x75985144ac
	public static Boolean IsIgnorableNonSpacing(Int32 cp) { }
	// RVA: 0x5efc504 VA: 0x7598514504
	public static Int32 ToKanaTypeInsensitive(Int32 i) { }
	// RVA: 0x5efc524 VA: 0x7598514524
	public static Int32 ToWidthCompat(Int32 i) { }
	// RVA: 0x5efc6b0 VA: 0x75985146b0
	public static Boolean HasSpecialWeight(Char c) { }
	// RVA: 0x5efc730 VA: 0x7598514730
	public static Boolean IsHalfWidthKana(Char c) { }
	// RVA: 0x5efc744 VA: 0x7598514744
	public static Boolean IsHiragana(Char c) { }
	// RVA: 0x5efc75c VA: 0x759851475c
	public static Boolean IsJapaneseSmallLetter(Char c) { }
	// RVA: 0x5efc844 VA: 0x7598514844
	public static Boolean get_IsReady() { }
	// RVA: 0x5efc89c VA: 0x759851489c
	private static IntPtr GetResource(String name) { }
	// RVA: 0x5efc954 VA: 0x7598514954
	private static UInt32 UInt32FromBytePtr(Byte* raw, UInt32 idx) { }
	// RVA: 0x5efc984 VA: 0x7598514984
	private static Void .cctor() { }
	// RVA: 0x5efce64 VA: 0x7598514e64
	public static Void FillCJK(String culture, ref CodePointIndexer cjkIndexer, ref Byte* catTable, ref Byte* lv1Table, ref CodePointIndexer lv2Indexer, ref Byte* lv2Table) { }
	// RVA: 0x5efcfc8 VA: 0x7598514fc8
	private static Void FillCJKCore(String culture, ref CodePointIndexer cjkIndexer, ref Byte* catTable, ref Byte* lv1Table, ref CodePointIndexer cjkLv2Indexer, ref Byte* lv2Table) { }
}
```