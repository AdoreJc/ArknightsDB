# Normalization

**Namespace:** `System.Text`


## Dump
```C#
// Dll : mscorlib.dll
// Namespace : System.Text
internal class Normalization
{
	private static Byte* props; // 0x0
	private static Int32* mappedChars; // 0x8
	private static Int16* charMapIndex; // 0x10
	private static Int16* helperIndex; // 0x18
	private static UInt16* mapIdxToComposite; // 0x20
	private static Byte* combiningClass; // 0x28
	private static Object forLock; // 0x30
	public static readonly Boolean isReady; // 0x38


	// RVA: 0x5f3d6c8 VA: 0x75985556c8
	private static UInt32 PropValue(Int32 cp) { }
	// RVA: 0x5f3d75c VA: 0x759855575c
	private static Int32 CharMapIdx(Int32 cp) { }
	// RVA: 0x5f3d7f0 VA: 0x75985557f0
	private static Byte GetCombiningClass(Int32 c) { }
	// RVA: 0x5f3d898 VA: 0x7598555898
	private static Int32 GetPrimaryCompositeFromMapIndex(Int32 src) { }
	// RVA: 0x5f3d940 VA: 0x7598555940
	private static Int32 GetPrimaryCompositeHelperIndex(Int32 cp) { }
	// RVA: 0x5f3d9e8 VA: 0x75985559e8
	private static String Compose(String source, Int32 checkType) { }
	// RVA: 0x5f3dbfc VA: 0x7598555bfc
	private static StringBuilder Combine(String source, Int32 start, Int32 checkType) { }
	// RVA: 0x5f3dd38 VA: 0x7598555d38
	private static Void Combine(StringBuilder sb, Int32 i, Int32 checkType) { }
	// RVA: 0x5f3df64 VA: 0x7598555f64
	private static Int32 CombineHangul(StringBuilder sb, String s, Int32 current) { }
	// RVA: 0x5f3e35c VA: 0x759855635c
	private static Int32 Fetch(StringBuilder sb, String s, Int32 i) { }
	// RVA: 0x5f3e128 VA: 0x7598556128
	private static Int32 TryComposeWithPreviousStarter(StringBuilder sb, String s, Int32 current) { }
	// RVA: 0x5f3e398 VA: 0x7598556398
	private static Int32 TryCompose(Int32 i, Int32 starter, Int32 candidate) { }
	// RVA: 0x5f3e4b0 VA: 0x75985564b0
	private static String Decompose(String source, Int32 checkType) { }
	// RVA: 0x5f3dac8 VA: 0x7598555ac8
	private static Void Decompose(String source, ref StringBuilder sb, Int32 checkType) { }
	// RVA: 0x5f3e730 VA: 0x7598556730
	private static Void ReorderCanonical(String src, ref StringBuilder sb, Int32 start) { }
	// RVA: 0x5f3e53c VA: 0x759855653c
	private static Void DecomposeChar(ref StringBuilder sb, ref Int32[] buf, String s, Int32 i, Int32 checkType, ref Int32 start) { }
	// RVA: 0x5f3de48 VA: 0x7598555e48
	public static NormalizationCheck QuickCheck(Char c, Int32 type) { }
	// RVA: 0x5f3eb68 VA: 0x7598556b68
	private static Int32 GetCanonicalHangul(Int32 s, Int32[] buf, Int32 bufIdx) { }
	// RVA: 0x5f3e9b0 VA: 0x75985569b0
	private static Int32 GetCanonical(Int32 c, Int32[] buf, Int32 bufIdx, Int32 checkType) { }
	// RVA: 0x5f3ec54 VA: 0x7598556c54
	public static String Normalize(String source, NormalizationForm normalizationForm) { }
	// RVA: 0x5f3ed10 VA: 0x7598556d10
	public static String Normalize(String source, Int32 type) { }
	// RVA: 0x5f3eda8 VA: 0x7598556da8
	private static Void load_normalization_resource(out IntPtr props, out IntPtr mappedChars, out IntPtr charMapIndex, out IntPtr helperIndex, out IntPtr mapIdxToComposite, out IntPtr combiningClass) { }
	// RVA: 0x5f3edac VA: 0x7598556dac
	private static Void .cctor() { }
}
```