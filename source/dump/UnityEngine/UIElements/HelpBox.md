# HelpBox

**Namespace:** `UnityEngine.UIElements`


## Fields

- `HelpBoxMessageType m_HelpBoxMessageType`

- `VisualElement m_Icon`

- `String m_IconClass`

- `Label m_Label`


## Properties

- `String text`

- `HelpBoxMessageType messageType`


## Methods

- `Void set_text(String)`

- `Void set_messageType(HelpBoxMessageType)`

- `String GetIconClass(HelpBoxMessageType)`

- `Void UpdateIcon(HelpBoxMessageType)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class HelpBox : VisualElement
{
	public static readonly String ussClassName; // 0x0
	public static readonly String labelUssClassName; // 0x8
	public static readonly String iconUssClassName; // 0x10
	public static readonly String iconInfoUssClassName; // 0x18
	public static readonly String iconwarningUssClassName; // 0x20
	public static readonly String iconErrorUssClassName; // 0x28
	private HelpBoxMessageType m_HelpBoxMessageType; // 0x3b0
	private VisualElement m_Icon; // 0x3b8
	private String m_IconClass; // 0x3c0
	private Label m_Label; // 0x3c8

	public String text { set; }
	public HelpBoxMessageType messageType { set; }

	// RVA: 0x69afd44 VA: 0x7598fc7d44
	public Void set_text(String value) { }
	// RVA: 0x69afd68 VA: 0x7598fc7d68
	public Void set_messageType(HelpBoxMessageType value) { }
	// RVA: 0x69afe3c VA: 0x7598fc7e3c
	public Void .ctor() { }
	// RVA: 0x69afe90 VA: 0x7598fc7e90
	public Void .ctor(String text, HelpBoxMessageType messageType) { }
	// RVA: 0x69afffc VA: 0x7598fc7ffc
	private String GetIconClass(HelpBoxMessageType messageType) { }
	// RVA: 0x69afd80 VA: 0x7598fc7d80
	private Void UpdateIcon(HelpBoxMessageType messageType) { }
	// RVA: 0x69b00b4 VA: 0x7598fc80b4
	private static Void .cctor() { }
}
```