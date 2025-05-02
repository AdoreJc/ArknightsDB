# GUIContent

**Namespace:** `UnityEngine`


## Fields

- `String m_Text`

- `Texture m_Image`

- `String m_Tooltip`


## Properties

- `String text`

- `Texture image`

- `String tooltip`


## Methods

- `String get_text()`

- `Void set_text(String)`

- `Texture get_image()`

- `Void set_image(Texture)`

- `String get_tooltip()`

- `Void set_tooltip(String)`


## Dump
```C#
// Dll : UnityEngine.IMGUIModule.dll
// Namespace : UnityEngine
public class GUIContent
{
	private String m_Text; // 0x10
	private Texture m_Image; // 0x18
	private String m_Tooltip; // 0x20
	private static readonly GUIContent s_Text; // 0x0
	private static readonly GUIContent s_Image; // 0x8
	private static readonly GUIContent s_TextImage; // 0x10
	public static GUIContent none; // 0x18

	public String text { get; set; }
	public Texture image { get; set; }
	public String tooltip { get; set; }

	// RVA: 0x68b0ee4 VA: 0x7598ec8ee4
	public String get_text() { }
	// RVA: 0x68b142c VA: 0x7598ec942c
	public Void set_text(String value) { }
	// RVA: 0x68b8040 VA: 0x7598ed0040
	public Texture get_image() { }
	// RVA: 0x68b8048 VA: 0x7598ed0048
	public Void set_image(Texture value) { }
	// RVA: 0x68b37c4 VA: 0x7598ecb7c4
	public String get_tooltip() { }
	// RVA: 0x68b8050 VA: 0x7598ed0050
	public Void set_tooltip(String value) { }
	// RVA: 0x68b8058 VA: 0x7598ed0058
	public Void .ctor() { }
	// RVA: 0x68b80d0 VA: 0x7598ed00d0
	public Void .ctor(String text) { }
	// RVA: 0x68b8200 VA: 0x7598ed0200
	public Void .ctor(Texture image) { }
	// RVA: 0x68b8134 VA: 0x7598ed0134
	public Void .ctor(String text, Texture image, String tooltip) { }
	// RVA: 0x68b8264 VA: 0x7598ed0264
	public Void .ctor(GUIContent src) { }
	// RVA: 0x68aed7c VA: 0x7598ec6d7c
	internal static GUIContent Temp(String t) { }
	// RVA: 0x68b0510 VA: 0x7598ec8510
	internal static GUIContent Temp(Texture i) { }
	// RVA: 0x68b8328 VA: 0x7598ed0328
	internal static Void ClearStaticCache() { }
	// RVA: 0x68b8440 VA: 0x7598ed0440
	internal static GUIContent[] Temp(String[] texts) { }
	// RVA: 0x68b8568 VA: 0x7598ed0568
	internal static GUIContent[] Temp(Texture[] images) { }
	// RVA: 0x68b8690 VA: 0x7598ed0690
	public override String ToString() { }
	// RVA: 0x68b86b0 VA: 0x7598ed06b0
	private static Void .cctor() { }
}
```