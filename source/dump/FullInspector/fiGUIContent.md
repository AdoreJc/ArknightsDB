# fiGUIContent

**Namespace:** `FullInspector`


## Fields

- `String _text`

- `String _tooltip`

- `Texture _image`


## Properties

- `GUIContent AsGUIContent`

- `Boolean IsEmpty`


## Methods

- `GUIContent get_AsGUIContent()`

- `Boolean get_IsEmpty()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullInspector
public class fiGUIContent
{
	public static fiGUIContent Empty; // 0x0
	private String _text; // 0x10
	private String _tooltip; // 0x18
	private Texture _image; // 0x20

	public GUIContent AsGUIContent { get; }
	public Boolean IsEmpty { get; }

	// RVA: 0x34cb500 VA: 0x7595ae3500
	public Void .ctor() { }
	// RVA: 0x34cb5b0 VA: 0x7595ae35b0
	public Void .ctor(String text) { }
	// RVA: 0x34cb60c VA: 0x7595ae360c
	public Void .ctor(String text, String tooltip) { }
	// RVA: 0x34cb550 VA: 0x7595ae3550
	public Void .ctor(String text, String tooltip, Texture image) { }
	// RVA: 0x34cb614 VA: 0x7595ae3614
	public Void .ctor(Texture image) { }
	// RVA: 0x34cb670 VA: 0x7595ae3670
	public Void .ctor(Texture image, String tooltip) { }
	// RVA: 0x34cb6d0 VA: 0x7595ae36d0
	public GUIContent get_AsGUIContent() { }
	// RVA: 0x34cb74c VA: 0x7595ae374c
	public Boolean get_IsEmpty() { }
	// RVA: 0x34cb7e0 VA: 0x7595ae37e0
	public static GUIContent op_Implicit(fiGUIContent label) { }
	// RVA: 0x34cb850 VA: 0x7595ae3850
	public static fiGUIContent op_Implicit(String text) { }
	// RVA: 0x34cb8bc VA: 0x7595ae38bc
	public static fiGUIContent op_Implicit(GUIContent label) { }
	// RVA: 0x34cb970 VA: 0x7595ae3970
	private static Void .cctor() { }
}
```