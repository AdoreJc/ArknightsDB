# Foldout

**Namespace:** `UnityEngine.UIElements`


## Fields

- `Toggle m_Toggle`

- `VisualElement m_Container`

- `Boolean m_Value`


## Properties

- `String text`

- `Boolean value`


## Methods

- `Void set_text(String)`

- `Boolean get_value()`

- `Void set_value(Boolean)`

- `Void SetValueWithoutNotify(Boolean)`

- `Void OnAttachToPanel(AttachToPanelEvent)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class Foldout : BindableElement, INotifyValueChanged`1
{
	private Toggle m_Toggle; // 0x3c0
	private VisualElement m_Container; // 0x3c8
	private Boolean m_Value; // 0x3d0
	public static readonly String ussClassName; // 0x0
	public static readonly String toggleUssClassName; // 0x8
	public static readonly String contentUssClassName; // 0x10
	public static readonly String inputUssClassName; // 0x18
	public static readonly String checkmarkUssClassName; // 0x20
	public static readonly String textUssClassName; // 0x28
	internal static readonly String ussFoldoutDepthClassName; // 0x30
	internal static readonly Int32 ussFoldoutMaxDepth; // 0x38

	public override VisualElement contentContainer { get; }
	public String text { set; }
	public Boolean value { get; set; }

	// RVA: 0x69ac080 VA: 0x7598fc4080
	public override VisualElement get_contentContainer() { }
	// RVA: 0x69ac088 VA: 0x7598fc4088
	public Void set_text(String value) { }
	// RVA: 0x69ac1ac VA: 0x7598fc41ac
	public Boolean get_value() { }
	// RVA: 0x69ac1b4 VA: 0x7598fc41b4
	public Void set_value(Boolean value) { }
	// RVA: 0x69ac394 VA: 0x7598fc4394
	public Void SetValueWithoutNotify(Boolean newValue) { }
	// RVA: 0x69ac4b4 VA: 0x7598fc44b4
	internal override Void OnViewDataReady() { }
	// RVA: 0x69ac4f4 VA: 0x7598fc44f4
	public Void .ctor() { }
	// RVA: 0x69ac850 VA: 0x7598fc4850
	private Void OnAttachToPanel(AttachToPanelEvent evt) { }
	// RVA: 0x69aca10 VA: 0x7598fc4a10
	private static Void .cctor() { }
	// RVA: 0x69acc40 VA: 0x7598fc4c40
	private Void <.ctor>b__25_0(ChangeEvent`1 evt) { }
}
```