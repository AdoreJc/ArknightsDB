# DescriptorAttribute

**Namespace:** `AdvancedInspector`


## Fields

- `String name`

- `String comment`

- `String url`

- `Texture icon`

- `Color color`

- `String methodName`


## Properties

- `String Name`

- `String Comment`

- `String URL`

- `Texture Icon`

- `Color Color`

- `String MethodName`

- `Type Template`

- `Type TemplateStatic`


## Methods

- `String get_Name()`

- `Void set_Name(String)`

- `String get_Comment()`

- `Void set_Comment(String)`

- `String get_URL()`

- `Void set_URL(String)`

- `Texture get_Icon()`

- `Void set_Icon(Texture)`

- `Color get_Color()`

- `Void set_Color(Color)`

- `Description GetDescription(Object[], Object[])`

- `String get_MethodName()`

- `Type get_Template()`

- `Type get_TemplateStatic()`

- `Void set_Delegates(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp-firstpass.dll
// Namespace : AdvancedInspector
public class DescriptorAttribute : Attribute, IRuntimeAttribute, IDescriptor
{
	private static Color TRANSPARENT; // 0x0
	private String name; // 0x10
	private String comment; // 0x18
	private String url; // 0x20
	private Texture icon; // 0x28
	private Color color; // 0x30
	private String methodName; // 0x40
	private List`1 delegates; // 0x48

	public String Name { get; set; }
	public String Comment { get; set; }
	public String URL { get; set; }
	public Texture Icon { get; set; }
	public Color Color { get; set; }
	public String MethodName { get; }
	public Type Template { get; }
	public Type TemplateStatic { get; }
	public List`1 Delegates { get; set; }

	// RVA: 0x1b13c9c VA: 0x759412bc9c
	public String get_Name() { }
	// RVA: 0x1b13ca4 VA: 0x759412bca4
	public Void set_Name(String value) { }
	// RVA: 0x1b13cac VA: 0x759412bcac
	public String get_Comment() { }
	// RVA: 0x1b13cb4 VA: 0x759412bcb4
	public Void set_Comment(String value) { }
	// RVA: 0x1b13cbc VA: 0x759412bcbc
	public String get_URL() { }
	// RVA: 0x1b13cc4 VA: 0x759412bcc4
	public Void set_URL(String value) { }
	// RVA: 0x1b13ccc VA: 0x759412bccc
	public Texture get_Icon() { }
	// RVA: 0x1b13cd4 VA: 0x759412bcd4
	public Void set_Icon(Texture value) { }
	// RVA: 0x1b13cdc VA: 0x759412bcdc
	public Color get_Color() { }
	// RVA: 0x1b13ce8 VA: 0x759412bce8
	public Void set_Color(Color value) { }
	// RVA: 0x1b13cf4 VA: 0x759412bcf4
	public Description GetDescription(Object[] instances, Object[] values) { }
	// RVA: 0x1b1428c VA: 0x759412c28c
	public String get_MethodName() { }
	// RVA: 0x1b14294 VA: 0x759412c294
	public Type get_Template() { }
	// RVA: 0x1b14300 VA: 0x759412c300
	public Type get_TemplateStatic() { }
	// RVA: 0x1b1436c VA: 0x759412c36c
	public List`1 get_Delegates() { }
	// RVA: 0x1b14374 VA: 0x759412c374
	public Void set_Delegates(List`1 value) { }
	// RVA: 0x1b1437c VA: 0x759412c37c
	public Void .ctor() { }
	// RVA: 0x1b14464 VA: 0x759412c464
	public Void .ctor(String name) { }
	// RVA: 0x1b14564 VA: 0x759412c564
	public Void .ctor(Single r, Single g, Single b) { }
	// RVA: 0x1b1474c VA: 0x759412c74c
	public Void .ctor(String name, String description) { }
	// RVA: 0x1b147bc VA: 0x759412c7bc
	public Void .ctor(String name, String description, String url) { }
	// RVA: 0x1b147d0 VA: 0x759412c7d0
	public Void .ctor(String name, String description, String url, Single r, Single g, Single b) { }
	// RVA: 0x1b145e0 VA: 0x759412c5e0
	private Void .ctor(String name, String description, String url, Single r, Single g, Single b, Single a) { }
	// RVA: 0x1b147d8 VA: 0x759412c7d8
	public Void .ctor(String name, String description, Texture icon) { }
	// RVA: 0x1b14864 VA: 0x759412c864
	public Void .ctor(String name, String description, Texture icon, Color color) { }
	// RVA: 0x1b149cc VA: 0x759412c9cc
	public static Description GetDescriptor(Type type) { }
	// RVA: 0x1b14b2c VA: 0x759412cb2c
	public static List`1 GetDescriptors(List`1 types) { }
	// RVA: 0x1b14d58 VA: 0x759412cd58
	private static Void .cctor() { }
}
```