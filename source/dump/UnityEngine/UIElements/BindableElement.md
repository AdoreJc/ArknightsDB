# BindableElement

**Namespace:** `UnityEngine.UIElements`


## Fields

- `IBinding <binding>k__BackingField`

- `String <bindingPath>k__BackingField`


## Properties

- `IBinding binding`

- `String bindingPath`


## Methods

- `IBinding get_binding()`

- `Void set_bindingPath(String)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : UnityEngine.UIElements
public class BindableElement : VisualElement, IBindable
{
	private IBinding <binding>k__BackingField; // 0x3b0
	private String <bindingPath>k__BackingField; // 0x3b8

	public IBinding binding { get; }
	public String bindingPath { set; }

	// RVA: 0x692e7b4 VA: 0x7598f467b4
	public IBinding get_binding() { }
	// RVA: 0x692e7bc VA: 0x7598f467bc
	public Void set_bindingPath(String value) { }
	// RVA: 0x692e7cc VA: 0x7598f467cc
	public Void .ctor() { }
}
```