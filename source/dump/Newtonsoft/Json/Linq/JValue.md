# JValue

**Namespace:** `Newtonsoft.Json.Linq`


## Fields

- `JTokenType _valueType`

- `Object _value`


## Properties

- `Object Value`


## Methods

- `Object get_Value()`

- `Boolean Equals(JValue)`

- `String ToString(IFormatProvider)`

- `String ToString(String, IFormatProvider)`

- `Int32 CompareTo(JValue)`


## Dump
```C#
// Dll : Newtonsoft.Json.dll
// Namespace : Newtonsoft.Json.Linq
public class JValue : JToken, IFormattable, IComparable, IConvertible
{
	private JTokenType _valueType; // 0x30
	private Object _value; // 0x38

	public override Boolean HasValues { get; }
	public override JTokenType Type { get; }
	public Object Value { get; }

	// RVA: 0x618970c VA: 0x75987a170c
	internal Void .ctor(Object value, JTokenType type) { }
	// RVA: 0x6189688 VA: 0x75987a1688
	public Void .ctor(JValue other) { }
	// RVA: 0x6198b24 VA: 0x75987b0b24
	public Void .ctor(Int64 value) { }
	// RVA: 0x6198c54 VA: 0x75987b0c54
	public Void .ctor(String value) { }
	// RVA: 0x618dacc VA: 0x75987a5acc
	public Void .ctor(Object value) { }
	// RVA: 0x619bc54 VA: 0x75987b3c54
	internal override Boolean DeepEquals(JToken node) { }
	// RVA: 0x619bd4c VA: 0x75987b3d4c
	public override Boolean get_HasValues() { }
	// RVA: 0x619bd54 VA: 0x75987b3d54
	internal static Int32 Compare(JTokenType valueType, Object objA, Object objB) { }
	// RVA: 0x619c688 VA: 0x75987b4688
	private static Int32 CompareFloat(Object objA, Object objB) { }
	// RVA: 0x619c784 VA: 0x75987b4784
	internal override JToken CloneToken() { }
	// RVA: 0x618e0a0 VA: 0x75987a60a0
	public static JValue CreateComment(String value) { }
	// RVA: 0x618be98 VA: 0x75987a3e98
	public static JValue CreateNull() { }
	// RVA: 0x618e104 VA: 0x75987a6104
	public static JValue CreateUndefined() { }
	// RVA: 0x619b840 VA: 0x75987b3840
	private static JTokenType GetValueType(Nullable`1 current, Object value) { }
	// RVA: 0x619c7e4 VA: 0x75987b47e4
	private static JTokenType GetStringValueType(Nullable`1 current) { }
	// RVA: 0x619c860 VA: 0x75987b4860
	public override JTokenType get_Type() { }
	// RVA: 0x619c868 VA: 0x75987b4868
	public Object get_Value() { }
	// RVA: 0x619c870 VA: 0x75987b4870
	public override Void WriteTo(JsonWriter writer, JsonConverter[] converters) { }
	// RVA: 0x619cfd0 VA: 0x75987b4fd0
	internal override Int32 GetDeepHashCode() { }
	// RVA: 0x619bcf0 VA: 0x75987b3cf0
	private static Boolean ValuesEquals(JValue v1, JValue v2) { }
	// RVA: 0x619d024 VA: 0x75987b5024
	public Boolean Equals(JValue other) { }
	// RVA: 0x619d034 VA: 0x75987b5034
	public override Boolean Equals(Object obj) { }
	// RVA: 0x619d0d8 VA: 0x75987b50d8
	public override Int32 GetHashCode() { }
	// RVA: 0x619d0f0 VA: 0x75987b50f0
	public override String ToString() { }
	// RVA: 0x619d158 VA: 0x75987b5158
	public String ToString(IFormatProvider formatProvider) { }
	// RVA: 0x619d164 VA: 0x75987b5164
	public String ToString(String format, IFormatProvider formatProvider) { }
	// RVA: 0x619d27c VA: 0x75987b527c
	private Int32 System.IComparable.CompareTo(Object obj) { }
	// RVA: 0x619d310 VA: 0x75987b5310
	public Int32 CompareTo(JValue obj) { }
	// RVA: 0x619d330 VA: 0x75987b5330
	private TypeCode System.IConvertible.GetTypeCode() { }
	// RVA: 0x619d3ec VA: 0x75987b53ec
	private Boolean System.IConvertible.ToBoolean(IFormatProvider provider) { }
	// RVA: 0x619d440 VA: 0x75987b5440
	private Char System.IConvertible.ToChar(IFormatProvider provider) { }
	// RVA: 0x619d494 VA: 0x75987b5494
	private SByte System.IConvertible.ToSByte(IFormatProvider provider) { }
	// RVA: 0x619d4e8 VA: 0x75987b54e8
	private Byte System.IConvertible.ToByte(IFormatProvider provider) { }
	// RVA: 0x619d53c VA: 0x75987b553c
	private Int16 System.IConvertible.ToInt16(IFormatProvider provider) { }
	// RVA: 0x619d590 VA: 0x75987b5590
	private UInt16 System.IConvertible.ToUInt16(IFormatProvider provider) { }
	// RVA: 0x619d5e4 VA: 0x75987b55e4
	private Int32 System.IConvertible.ToInt32(IFormatProvider provider) { }
	// RVA: 0x619d638 VA: 0x75987b5638
	private UInt32 System.IConvertible.ToUInt32(IFormatProvider provider) { }
	// RVA: 0x619d68c VA: 0x75987b568c
	private Int64 System.IConvertible.ToInt64(IFormatProvider provider) { }
	// RVA: 0x619d6e0 VA: 0x75987b56e0
	private UInt64 System.IConvertible.ToUInt64(IFormatProvider provider) { }
	// RVA: 0x619d734 VA: 0x75987b5734
	private Single System.IConvertible.ToSingle(IFormatProvider provider) { }
	// RVA: 0x619d788 VA: 0x75987b5788
	private Double System.IConvertible.ToDouble(IFormatProvider provider) { }
	// RVA: 0x619d7dc VA: 0x75987b57dc
	private Decimal System.IConvertible.ToDecimal(IFormatProvider provider) { }
	// RVA: 0x619d830 VA: 0x75987b5830
	private DateTime System.IConvertible.ToDateTime(IFormatProvider provider) { }
	// RVA: 0x619d884 VA: 0x75987b5884
	private Object System.IConvertible.ToType(Type conversionType, IFormatProvider provider) { }
}
```