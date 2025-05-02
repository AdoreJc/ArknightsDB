# RadioButtonGroup

**Namespace:** `UnityEngine.UIElements`


## Methods

- `Void set_choices(IEnumerable`1)`

- `Void RadioButtonValueChangedCallback(ChangeEvent`1)`

- `Void UpdateRadioButtons()`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class RadioButtonGroup : BaseField`1, IGroupBox
{
	public static readonly String ussClassName; // 0x0
	private IEnumerable`1 m_Choices; // 0x408
	private List`1 m_RadioButtons; // 0x410
	private EventCallback`1 m_RadioButtonValueChangedCallback; // 0x418

	public IEnumerable`1 choices { set; }

	// RVA: 0x69badf0 VA: 0x7598fd2df0
	public Void set_choices(IEnumerable`1 value) { }
	// RVA: 0x69bb58c VA: 0x7598fd358c
	public Void .ctor() { }
	// RVA: 0x69bb598 VA: 0x7598fd3598
	public Void .ctor(String label, List`1 radioButtonChoices) { }
	// RVA: 0x69bb768 VA: 0x7598fd3768
	private Void RadioButtonValueChangedCallback(ChangeEvent`1 evt) { }
	// RVA: 0x69bb860 VA: 0x7598fd3860
	public override Void SetValueWithoutNotify(Int32 newValue) { }
	// RVA: 0x69bb3a0 VA: 0x7598fd33a0
	private Void UpdateRadioButtons() { }
	// RVA: 0x69bb8c0 VA: 0x7598fd38c0
	private static Void .cctor() { }
}
```