# DropdownField

**Namespace:** `UnityEngine.UIElements`


## Fields

- `TextElement m_TextElement`

- `VisualElement m_ArrowElement`

- `Int32 m_Index`


## Properties

- `TextElement textElement`

- `Int32 index`


## Methods

- `TextElement get_textElement()`

- `Void set_index(Int32)`

- `Void ChangeValueFromMenu(String)`

- `Void ShowMenu()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class DropdownField : BaseField`1
{
	internal List`1 m_Choices; // 0x408
	private TextElement m_TextElement; // 0x410
	private VisualElement m_ArrowElement; // 0x418
	internal Func`2 m_FormatSelectedValueCallback; // 0x420
	internal Func`2 m_FormatListItemCallback; // 0x428
	internal Func`1 createMenuCallback; // 0x430
	private Int32 m_Index; // 0x438
	internal static readonly String ussClassNameBasePopupField; // 0x0
	internal static readonly String textUssClassNameBasePopupField; // 0x8
	internal static readonly String arrowUssClassNameBasePopupField; // 0x10
	internal static readonly String labelUssClassNameBasePopupField; // 0x18
	internal static readonly String inputUssClassNameBasePopupField; // 0x20
	internal static readonly String ussClassNamePopupField; // 0x28
	internal static readonly String labelUssClassNamePopupField; // 0x30
	internal static readonly String inputUssClassNamePopupField; // 0x38

	protected TextElement textElement { get; }
	public Int32 index { set; }
	public virtual List`1 choices { set; }
	public override String value { get; set; }

	// RVA: 0x69aa8dc VA: 0x7598fc28dc
	protected TextElement get_textElement() { }
	// RVA: 0x69aa8e4 VA: 0x7598fc28e4
	internal String GetValueToDisplay() { }
	// RVA: 0x69aa970 VA: 0x7598fc2970
	internal String GetListItemToDisplay(String value) { }
	// RVA: 0x69aaa1c VA: 0x7598fc2a1c
	public Void set_index(Int32 value) { }
	// RVA: 0x69aaab8 VA: 0x7598fc2ab8
	public Void .ctor() { }
	// RVA: 0x69aaac0 VA: 0x7598fc2ac0
	public Void .ctor(String label) { }
	// RVA: 0x69aae10 VA: 0x7598fc2e10
	internal Void AddMenuItems(IGenericMenu menu) { }
	// RVA: 0x69ab148 VA: 0x7598fc3148
	private Void ChangeValueFromMenu(String menuItem) { }
	// RVA: 0x69ab158 VA: 0x7598fc3158
	public virtual Void set_choices(List`1 value) { }
	// RVA: 0x69ab1d4 VA: 0x7598fc31d4
	public override String get_value() { }
	// RVA: 0x69ab21c VA: 0x7598fc321c
	public override Void set_value(String value) { }
	// RVA: 0x69ab2a0 VA: 0x7598fc32a0
	public override Void SetValueWithoutNotify(String newValue) { }
	// RVA: 0x69ab3b0 VA: 0x7598fc33b0
	protected override Void ExecuteDefaultActionAtTarget(EventBase evt) { }
	// RVA: 0x69ab530 VA: 0x7598fc3530
	private Void ShowMenu() { }
	// RVA: 0x69ab9e8 VA: 0x7598fc39e8
	protected override Void UpdateMixedValueContent() { }
	// RVA: 0x69abaa8 VA: 0x7598fc3aa8
	private static Void .cctor() { }
}
```