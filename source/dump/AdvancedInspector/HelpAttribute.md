# HelpAttribute

**Namespace:** `AdvancedInspector`


## Fields

- `HelpType type`

- `String message`

- `HelpPosition position`

- `String regex`

- `String methodName`


## Properties

- `HelpType Type`

- `String Message`

- `HelpPosition Position`

- `String Regex`

- `String MethodName`

- `Type Template`

- `Type TemplateStatic`


## Methods

- `HelpType get_Type()`

- `Void set_Type(HelpType)`

- `String get_Message()`

- `Void set_Message(String)`

- `HelpPosition get_Position()`

- `Void set_Position(HelpPosition)`

- `String get_Regex()`

- `Void set_Regex(String)`

- `String get_MethodName()`

- `Type get_Template()`

- `Type get_TemplateStatic()`

- `Void set_Delegates(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp-firstpass.dll
// Namespace : AdvancedInspector
public class HelpAttribute : Attribute, IRuntimeAttribute, IHelp
{
	public const String IsNull; // 0x0
	public const String IsNullOrEmpty; // 0x0
	public const String IsMatch; // 0x0
	private HelpType type; // 0x10
	private String message; // 0x18
	private HelpPosition position; // 0x20
	private String regex; // 0x28
	private String methodName; // 0x30
	private List`1 delegates; // 0x38

	public HelpType Type { get; set; }
	public String Message { get; set; }
	public HelpPosition Position { get; set; }
	public String Regex { get; set; }
	public String MethodName { get; }
	public Type Template { get; }
	public Type TemplateStatic { get; }
	public List`1 Delegates { get; set; }

	// RVA: 0x1b15908 VA: 0x759412d908
	public HelpType get_Type() { }
	// RVA: 0x1b15910 VA: 0x759412d910
	public Void set_Type(HelpType value) { }
	// RVA: 0x1b15918 VA: 0x759412d918
	public String get_Message() { }
	// RVA: 0x1b15920 VA: 0x759412d920
	public Void set_Message(String value) { }
	// RVA: 0x1b15928 VA: 0x759412d928
	public HelpPosition get_Position() { }
	// RVA: 0x1b15930 VA: 0x759412d930
	public Void set_Position(HelpPosition value) { }
	// RVA: 0x1b15938 VA: 0x759412d938
	public String get_Regex() { }
	// RVA: 0x1b15940 VA: 0x759412d940
	public Void set_Regex(String value) { }
	// RVA: 0x1b15948 VA: 0x759412d948
	public IList`1 GetHelp(Object[] instances, Object[] values) { }
	// RVA: 0x1b15fe4 VA: 0x759412dfe4
	public String get_MethodName() { }
	// RVA: 0x1b15fec VA: 0x759412dfec
	public Type get_Template() { }
	// RVA: 0x1b16058 VA: 0x759412e058
	public Type get_TemplateStatic() { }
	// RVA: 0x1b160c4 VA: 0x759412e0c4
	public List`1 get_Delegates() { }
	// RVA: 0x1b160cc VA: 0x759412e0cc
	public Void set_Delegates(List`1 value) { }
	// RVA: 0x1b160d4 VA: 0x759412e0d4
	public Void .ctor(String methodName) { }
	// RVA: 0x1b16234 VA: 0x759412e234
	public Void .ctor(String methodName, HelpType type, String message) { }
	// RVA: 0x1b16240 VA: 0x759412e240
	public Void .ctor(HelpType type, String message) { }
	// RVA: 0x1b162a4 VA: 0x759412e2a4
	public Void .ctor(HelpType type, HelpPosition position, String message) { }
	// RVA: 0x1b16134 VA: 0x759412e134
	public Void .ctor(String methodName, HelpType type, HelpPosition position, String message) { }
	// RVA: 0x1b16314 VA: 0x759412e314
	public Void .ctor(Delegate method) { }
	// RVA: 0x1b16454 VA: 0x759412e454
	private static HelpItem IsValueNull(HelpAttribute help, Object instance, Object value) { }
	// RVA: 0x1b165c4 VA: 0x759412e5c4
	private static HelpItem IsStringNullOrEmpty(HelpAttribute help, Object instance, Object value) { }
	// RVA: 0x1b16690 VA: 0x759412e690
	private static HelpItem IsRegexMatch(HelpAttribute help, Object instance, Object value) { }
}
```