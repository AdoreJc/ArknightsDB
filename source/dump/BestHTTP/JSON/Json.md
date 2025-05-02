# Json

**Namespace:** `BestHTTP.JSON`


## Dump
```C#
// Dll : ThirdPartyAssembly.dll
// Namespace : BestHTTP.JSON
public class Json
{
	private const Int32 TOKEN_NONE; // 0x0
	private const Int32 TOKEN_CURLY_OPEN; // 0x0
	private const Int32 TOKEN_CURLY_CLOSE; // 0x0
	private const Int32 TOKEN_SQUARED_OPEN; // 0x0
	private const Int32 TOKEN_SQUARED_CLOSE; // 0x0
	private const Int32 TOKEN_COLON; // 0x0
	private const Int32 TOKEN_COMMA; // 0x0
	private const Int32 TOKEN_STRING; // 0x0
	private const Int32 TOKEN_NUMBER; // 0x0
	private const Int32 TOKEN_TRUE; // 0x0
	private const Int32 TOKEN_FALSE; // 0x0
	private const Int32 TOKEN_NULL; // 0x0
	private const Int32 BUILDER_CAPACITY; // 0x0


	// RVA: 0x6619364 VA: 0x7598c31364
	public static Object Decode(String json) { }
	// RVA: 0x6619380 VA: 0x7598c31380
	public static Object Decode(String json, ref Boolean success) { }
	// RVA: 0x661951c VA: 0x7598c3151c
	public static String Encode(Object json) { }
	// RVA: 0x66197f4 VA: 0x7598c317f4
	protected static Dictionary`2 ParseObject(Char[] json, ref Int32 index, ref Boolean success) { }
	// RVA: 0x6619e78 VA: 0x7598c31e78
	protected static List`1 ParseArray(Char[] json, ref Int32 index, ref Boolean success) { }
	// RVA: 0x66193c0 VA: 0x7598c313c0
	protected static Object ParseValue(Char[] json, ref Int32 index, ref Boolean success) { }
	// RVA: 0x6619bb8 VA: 0x7598c31bb8
	protected static String ParseString(Char[] json, ref Int32 index, ref Boolean success) { }
	// RVA: 0x6619fe4 VA: 0x7598c31fe4
	protected static Double ParseNumber(Char[] json, ref Int32 index, ref Boolean success) { }
	// RVA: 0x661a15c VA: 0x7598c3215c
	protected static Int32 GetLastIndexOfNumber(Char[] json, Int32 index) { }
	// RVA: 0x661a0bc VA: 0x7598c320bc
	protected static Void EatWhitespace(Char[] json, ref Int32 index) { }
	// RVA: 0x6619ba0 VA: 0x7598c31ba0
	protected static Int32 LookAhead(Char[] json, Int32 index) { }
	// RVA: 0x6619940 VA: 0x7598c31940
	protected static Int32 NextToken(Char[] json, ref Int32 index) { }
	// RVA: 0x66195a8 VA: 0x7598c315a8
	protected static Boolean SerializeValue(Object value, StringBuilder builder) { }
	// RVA: 0x661a49c VA: 0x7598c3249c
	protected static Boolean SerializeObject(IDictionary anObject, StringBuilder builder) { }
	// RVA: 0x661a788 VA: 0x7598c32788
	protected static Boolean SerializeArray(IList anArray, StringBuilder builder) { }
	// RVA: 0x661a204 VA: 0x7598c32204
	protected static Boolean SerializeString(String aString, StringBuilder builder) { }
	// RVA: 0x661a968 VA: 0x7598c32968
	protected static Boolean SerializeNumber(Double number, StringBuilder builder) { }
	// RVA: 0x661aa24 VA: 0x7598c32a24
	public Void .ctor() { }
}
```