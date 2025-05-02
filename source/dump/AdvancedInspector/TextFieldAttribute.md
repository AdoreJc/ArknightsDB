# TextFieldAttribute

**Namespace:** `AdvancedInspector`


## Fields

- `String title`

- `String path`

- `String extension`

- `TextFieldType type`


## Properties

- `String Title`

- `String Path`

- `String Extension`

- `TextFieldType Type`


## Methods

- `String get_Title()`

- `Void set_Title(String)`

- `String get_Path()`

- `Void set_Path(String)`

- `String get_Extension()`

- `Void set_Extension(String)`

- `TextFieldType get_Type()`

- `Void set_Type(TextFieldType)`


## Dump
```C#
// Dll : Assembly-CSharp-firstpass.dll
// Namespace : AdvancedInspector
public class TextFieldAttribute : Attribute, IListAttribute
{
	private const String TITLE; // 0x0
	private const String PATH; // 0x0
	private const String EXTENSION; // 0x0
	private String title; // 0x10
	private String path; // 0x18
	private String extension; // 0x20
	private TextFieldType type; // 0x28

	public String Title { get; set; }
	public String Path { get; set; }
	public String Extension { get; set; }
	public TextFieldType Type { get; set; }

	// RVA: 0x1b1b250 VA: 0x7594133250
	public String get_Title() { }
	// RVA: 0x1b1b258 VA: 0x7594133258
	public Void set_Title(String value) { }
	// RVA: 0x1b1b260 VA: 0x7594133260
	public String get_Path() { }
	// RVA: 0x1b1b268 VA: 0x7594133268
	public Void set_Path(String value) { }
	// RVA: 0x1b1b270 VA: 0x7594133270
	public String get_Extension() { }
	// RVA: 0x1b1b278 VA: 0x7594133278
	public Void set_Extension(String value) { }
	// RVA: 0x1b1b280 VA: 0x7594133280
	public TextFieldType get_Type() { }
	// RVA: 0x1b1b288 VA: 0x7594133288
	public Void set_Type(TextFieldType value) { }
	// RVA: 0x1b1b290 VA: 0x7594133290
	public Void .ctor(TextFieldType type) { }
	// RVA: 0x1b1b3f8 VA: 0x75941333f8
	public Void .ctor(TextFieldType type, String title) { }
	// RVA: 0x1b1b45c VA: 0x759413345c
	public Void .ctor(TextFieldType type, String title, String path) { }
	// RVA: 0x1b1b304 VA: 0x7594133304
	public Void .ctor(TextFieldType type, String title, String path, String extension) { }
}
```