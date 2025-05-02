# XmlConvert

**Namespace:** `System.Xml`


## Dump
```C#
// Dll : System.Xml.dll
// Namespace : System.Xml
public class XmlConvert
{
	private static XmlCharType xmlCharType; // 0x0
	internal static Char[] crt; // 0x8
	private static readonly Int32 c_EncodedCharLength; // 0x10
	private static Regex c_EncodeCharPattern; // 0x18
	private static Regex c_DecodeCharPattern; // 0x20
	internal static readonly Char[] WhitespaceChars; // 0x28


	// RVA: 0x62c42dc VA: 0x75988dc2dc
	public static String EncodeName(String name) { }
	// RVA: 0x62c4d08 VA: 0x75988dcd08
	public static String DecodeName(String name) { }
	// RVA: 0x62c4338 VA: 0x75988dc338
	private static String EncodeName(String name, Boolean first, Boolean local) { }
	// RVA: 0x62c5634 VA: 0x75988dd634
	private static Int32 FromHex(Char digit) { }
	// RVA: 0x62c5664 VA: 0x75988dd664
	internal static Byte[] FromBinHexString(String s, Boolean allowOddCount) { }
	// RVA: 0x62c56d4 VA: 0x75988dd6d4
	internal static String ToBinHexString(Byte[] inArray) { }
	// RVA: 0x62c573c VA: 0x75988dd73c
	public static String VerifyName(String name) { }
	// RVA: 0x62c5958 VA: 0x75988dd958
	internal static Exception TryVerifyName(String name) { }
	// RVA: 0x62c5ac4 VA: 0x75988ddac4
	internal static String VerifyQName(String name, ExceptionType exceptionType) { }
	// RVA: 0x62c5cd8 VA: 0x75988ddcd8
	public static String VerifyNCName(String name) { }
	// RVA: 0x62c5d30 VA: 0x75988ddd30
	internal static String VerifyNCName(String name, ExceptionType exceptionType) { }
	// RVA: 0x62c5e88 VA: 0x75988dde88
	internal static Exception TryVerifyNCName(String name) { }
	// RVA: 0x62c5f28 VA: 0x75988ddf28
	internal static Exception TryVerifyTOKEN(String token) { }
	// RVA: 0x62c6064 VA: 0x75988de064
	internal static Exception TryVerifyNMTOKEN(String name) { }
	// RVA: 0x62c61a4 VA: 0x75988de1a4
	internal static Exception TryVerifyNormalizedString(String str) { }
	// RVA: 0x62c6270 VA: 0x75988de270
	public static String ToString(Boolean value) { }
	// RVA: 0x62c62d8 VA: 0x75988de2d8
	public static String ToString(Decimal value) { }
	// RVA: 0x62c6374 VA: 0x75988de374
	public static String ToString(SByte value) { }
	// RVA: 0x62c63a0 VA: 0x75988de3a0
	public static String ToString(Int16 value) { }
	// RVA: 0x62c63cc VA: 0x75988de3cc
	public static String ToString(Int32 value) { }
	// RVA: 0x62c63f8 VA: 0x75988de3f8
	public static String ToString(Int64 value) { }
	// RVA: 0x62c6424 VA: 0x75988de424
	public static String ToString(Byte value) { }
	// RVA: 0x62c6450 VA: 0x75988de450
	public static String ToString(UInt16 value) { }
	// RVA: 0x62c647c VA: 0x75988de47c
	public static String ToString(UInt32 value) { }
	// RVA: 0x62c64a8 VA: 0x75988de4a8
	public static String ToString(UInt64 value) { }
	// RVA: 0x62c64d4 VA: 0x75988de4d4
	public static String ToString(Single value) { }
	// RVA: 0x62c6644 VA: 0x75988de644
	public static String ToString(Double value) { }
	// RVA: 0x62c6740 VA: 0x75988de740
	public static String ToString(TimeSpan value) { }
	// RVA: 0x62c6798 VA: 0x75988de798
	public static String ToString(DateTime value, XmlDateTimeSerializationMode dateTimeOption) { }
	// RVA: 0x62c6b80 VA: 0x75988deb80
	public static String ToString(DateTimeOffset value) { }
	// RVA: 0x62c6c08 VA: 0x75988dec08
	public static Boolean ToBoolean(String s) { }
	// RVA: 0x62c6e44 VA: 0x75988dee44
	internal static Exception TryToBoolean(String s, out Boolean result) { }
	// RVA: 0x62c7090 VA: 0x75988df090
	public static Char ToChar(String s) { }
	// RVA: 0x62c7158 VA: 0x75988df158
	internal static Exception TryToChar(String s, out Char result) { }
	// RVA: 0x62c72f4 VA: 0x75988df2f4
	public static Decimal ToDecimal(String s) { }
	// RVA: 0x62c7364 VA: 0x75988df364
	internal static Exception TryToDecimal(String s, out Decimal result) { }
	// RVA: 0x62c7518 VA: 0x75988df518
	internal static Decimal ToInteger(String s) { }
	// RVA: 0x62c7588 VA: 0x75988df588
	internal static Exception TryToInteger(String s, out Decimal result) { }
	// RVA: 0x62c773c VA: 0x75988df73c
	internal static Exception TryToSByte(String s, out SByte result) { }
	// RVA: 0x62c78bc VA: 0x75988df8bc
	internal static Exception TryToInt16(String s, out Int16 result) { }
	// RVA: 0x62c7a3c VA: 0x75988dfa3c
	public static Int32 ToInt32(String s) { }
	// RVA: 0x62c7a64 VA: 0x75988dfa64
	internal static Exception TryToInt32(String s, out Int32 result) { }
	// RVA: 0x62c7be4 VA: 0x75988dfbe4
	public static Int64 ToInt64(String s) { }
	// RVA: 0x62c7c0c VA: 0x75988dfc0c
	internal static Exception TryToInt64(String s, out Int64 result) { }
	// RVA: 0x62c7d8c VA: 0x75988dfd8c
	internal static Exception TryToByte(String s, out Byte result) { }
	// RVA: 0x62c7f0c VA: 0x75988dff0c
	internal static Exception TryToUInt16(String s, out UInt16 result) { }
	// RVA: 0x62c808c VA: 0x75988e008c
	internal static Exception TryToUInt32(String s, out UInt32 result) { }
	// RVA: 0x62c820c VA: 0x75988e020c
	internal static Exception TryToUInt64(String s, out UInt64 result) { }
	// RVA: 0x62c838c VA: 0x75988e038c
	public static Single ToSingle(String s) { }
	// RVA: 0x62c84a4 VA: 0x75988e04a4
	internal static Exception TryToSingle(String s, out Single result) { }
	// RVA: 0x62c8704 VA: 0x75988e0704
	public static Double ToDouble(String s) { }
	// RVA: 0x62c881c VA: 0x75988e081c
	internal static Exception TryToDouble(String s, out Double result) { }
	// RVA: 0x62c8a7c VA: 0x75988e0a7c
	internal static Exception TryToTimeSpan(String s, out TimeSpan result) { }
	// RVA: 0x62c8b28 VA: 0x75988e0b28
	public static Guid ToGuid(String s) { }
	// RVA: 0x62c8b54 VA: 0x75988e0b54
	internal static Exception TryToGuid(String s, out Guid result) { }
	// RVA: 0x62c69c8 VA: 0x75988de9c8
	private static DateTime SwitchToLocalTime(DateTime value) { }
	// RVA: 0x62c6a9c VA: 0x75988dea9c
	private static DateTime SwitchToUtcTime(DateTime value) { }
	// RVA: 0x62c8d50 VA: 0x75988e0d50
	internal static Uri ToUri(String s) { }
	// RVA: 0x62c8f0c VA: 0x75988e0f0c
	internal static Exception TryToUri(String s, out Uri result) { }
	// RVA: 0x62c9158 VA: 0x75988e1158
	internal static Boolean StrEqual(Char[] chars, Int32 strPos1, Int32 strLen1, String str2) { }
	// RVA: 0x62c6dd8 VA: 0x75988dedd8
	internal static String TrimString(String value) { }
	// RVA: 0x62c9220 VA: 0x75988e1220
	internal static String TrimStringStart(String value) { }
	// RVA: 0x62c928c VA: 0x75988e128c
	internal static String TrimStringEnd(String value) { }
	// RVA: 0x62c92f8 VA: 0x75988e12f8
	internal static String[] SplitString(String value) { }
	// RVA: 0x62c65d0 VA: 0x75988de5d0
	internal static Boolean IsNegativeZero(Double value) { }
	// RVA: 0x62c9368 VA: 0x75988e1368
	private static Int64 DoubleToInt64Bits(Double value) { }
	// RVA: 0x62c9370 VA: 0x75988e1370
	internal static Exception CreateException(String res, String arg, ExceptionType exceptionType, Int32 lineNo, Int32 linePos) { }
	// RVA: 0x62c9588 VA: 0x75988e1588
	internal static Exception CreateException(String res, String[] args, ExceptionType exceptionType) { }
	// RVA: 0x62c5bf4 VA: 0x75988ddbf4
	internal static Exception CreateException(String res, String[] args, ExceptionType exceptionType, Int32 lineNo, Int32 linePos) { }
	// RVA: 0x62c9610 VA: 0x75988e1610
	internal static Exception CreateInvalidSurrogatePairException(Char low, Char hi) { }
	// RVA: 0x62c9678 VA: 0x75988e1678
	internal static Exception CreateInvalidSurrogatePairException(Char low, Char hi, ExceptionType exceptionType) { }
	// RVA: 0x62c96ec VA: 0x75988e16ec
	internal static Exception CreateInvalidSurrogatePairException(Char low, Char hi, ExceptionType exceptionType, Int32 lineNo, Int32 linePos) { }
	// RVA: 0x62c98bc VA: 0x75988e18bc
	internal static Exception CreateInvalidHighSurrogateCharException(Char hi) { }
	// RVA: 0x62c9914 VA: 0x75988e1914
	internal static Exception CreateInvalidHighSurrogateCharException(Char hi, ExceptionType exceptionType) { }
	// RVA: 0x62c9980 VA: 0x75988e1980
	internal static Exception CreateInvalidHighSurrogateCharException(Char hi, ExceptionType exceptionType, Int32 lineNo, Int32 linePos) { }
	// RVA: 0x62c9a7c VA: 0x75988e1a7c
	internal static Exception CreateInvalidCharException(Char invChar, Char nextChar) { }
	// RVA: 0x62c9ae4 VA: 0x75988e1ae4
	internal static Exception CreateInvalidCharException(Char invChar, Char nextChar, ExceptionType exceptionType) { }
	// RVA: 0x62c5894 VA: 0x75988dd894
	internal static Exception CreateInvalidNameCharException(String name, Int32 index, ExceptionType exceptionType) { }
	// RVA: 0x62c9e88 VA: 0x75988e1e88
	internal static ArgumentException CreateInvalidNameArgumentException(String name, String argumentName) { }
	// RVA: 0x62c9f44 VA: 0x75988e1f44
	private static Void .cctor() { }
}
```