# Description

**Namespace:** `AdvancedInspector`


## Fields

- `String name`

- `String comment`

- `String url`

- `Texture icon`

- `Color color`


## Properties

- `String Name`

- `String Comment`

- `String URL`

- `Texture Icon`

- `Color Color`


## Methods

- `String get_Name()`

- `String get_Comment()`

- `String get_URL()`

- `Texture get_Icon()`

- `Color get_Color()`


## Dump
```C#
// Dll : Assembly-CSharp-firstpass.dll
// Namespace : AdvancedInspector
public class Description
{
	private String name; // 0x10
	private String comment; // 0x18
	private String url; // 0x20
	private Texture icon; // 0x28
	private Color color; // 0x30

	public String Name { get; }
	public String Comment { get; }
	public String URL { get; }
	public Texture Icon { get; }
	public Color Color { get; }

	// RVA: 0x1b2158c VA: 0x759413958c
	public String get_Name() { }
	// RVA: 0x1b21594 VA: 0x7594139594
	public String get_Comment() { }
	// RVA: 0x1b2159c VA: 0x759413959c
	public String get_URL() { }
	// RVA: 0x1b215a4 VA: 0x75941395a4
	public Texture get_Icon() { }
	// RVA: 0x1b215ac VA: 0x75941395ac
	public Color get_Color() { }
	// RVA: 0x1b215b8 VA: 0x75941395b8
	public Void .ctor(String name) { }
	// RVA: 0x1b21628 VA: 0x7594139628
	public Void .ctor(String name, Texture icon) { }
	// RVA: 0x1b2169c VA: 0x759413969c
	public Void .ctor(String name, Color color) { }
	// RVA: 0x1b2172c VA: 0x759413972c
	public Void .ctor(String name, Texture icon, Color color) { }
	// RVA: 0x1b1c8ac VA: 0x75941348ac
	public Void .ctor(String name, String comment) { }
	// RVA: 0x1b217c0 VA: 0x75941397c0
	public Void .ctor(String name, String comment, Texture icon) { }
	// RVA: 0x1b21840 VA: 0x7594139840
	public Void .ctor(String name, String comment, Color color) { }
	// RVA: 0x1b218d4 VA: 0x75941398d4
	public Void .ctor(String name, String comment, Texture icon, Color color) { }
	// RVA: 0x1b21974 VA: 0x7594139974
	public Void .ctor(String name, String comment, String url) { }
	// RVA: 0x1b2198c VA: 0x759413998c
	public Void .ctor(String name, String comment, String url, Texture icon) { }
	// RVA: 0x1b219a0 VA: 0x75941399a0
	public Void .ctor(String name, String comment, String url, Color color) { }
	// RVA: 0x1b14164 VA: 0x759412c164
	public Void .ctor(String name, String comment, String url, Texture icon, Color color) { }
}
```