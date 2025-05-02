# RadioButton

**Namespace:** `UnityEngine.UIElements`


## Fields

- `VisualElement m_CheckmarkBackground`


## Methods

- `Void SetSelected(Boolean)`

- `Void UpdateCheckmark()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class RadioButton : BaseBoolField, IGroupBoxOption
{
	public static readonly String ussClassName; // 0x0
	public static readonly String labelUssClassName; // 0x8
	public static readonly String inputUssClassName; // 0x10
	public static readonly String checkmarkBackgroundUssClassName; // 0x18
	public static readonly String checkmarkUssClassName; // 0x20
	public static readonly String textUssClassName; // 0x28
	private VisualElement m_CheckmarkBackground; // 0x428

	public override Boolean value { get; set; }

	// RVA: 0x69ba454 VA: 0x7598fd2454
	public override Boolean get_value() { }
	// RVA: 0x69ba49c VA: 0x7598fd249c
	public override Void set_value(Boolean value) { }
	// RVA: 0x69ba670 VA: 0x7598fd2670
	public Void .ctor() { }
	// RVA: 0x69ba678 VA: 0x7598fd2678
	public Void .ctor(String label) { }
	// RVA: 0x69ba86c VA: 0x7598fd286c
	protected override Void InitLabel() { }
	// RVA: 0x69ba8e8 VA: 0x7598fd28e8
	protected override Void ToggleValue() { }
	// RVA: 0x69ba928 VA: 0x7598fd2928
	public Void SetSelected(Boolean selected) { }
	// RVA: 0x69ba93c VA: 0x7598fd293c
	public override Void SetValueWithoutNotify(Boolean newValue) { }
	// RVA: 0x69ba57c VA: 0x7598fd257c
	private Void UpdateCheckmark() { }
	// RVA: 0x69ba95c VA: 0x7598fd295c
	protected override Void UpdateMixedValueContent() { }
	// RVA: 0x69baa00 VA: 0x7598fd2a00
	private static Void .cctor() { }
}
```