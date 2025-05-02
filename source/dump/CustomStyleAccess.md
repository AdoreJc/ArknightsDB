# CustomStyleAccess

**Namespace:** ` `


## Fields

- `Single m_DpiScaling`


## Methods

- `Void SetContext(Dictionary`2, Single)`

- `Boolean TryGetValue(CustomStyleProperty`1, out)`

- `Boolean TryGetValue(CustomStyleProperty`1, out)`

- `Boolean TryGetValue(CustomStyleProperty`1, out)`

- `Boolean TryGetValue(CustomStyleProperty`1, out)`

- `Boolean TryGetValue(CustomStyleProperty`1, out)`

- `Boolean TryGetValue(CustomStyleProperty`1, out)`

- `Boolean TryGetValue(CustomStyleProperty`1, out)`

- `Boolean TryGetValue(String, StyleValueType, out)`


## Dump
```C#
// Dll : UnityEngine.UIElementsModule.dll
// Namespace : 
internal class CustomStyleAccess : ICustomStyle
{
	private Dictionary`2 m_CustomProperties; // 0x10
	private Single m_DpiScaling; // 0x18


	// RVA: 0x69535dc VA: 0x7598f6b5dc
	public Void SetContext(Dictionary`2 customProperties, Single dpiScaling) { }
	// RVA: 0x69556c8 VA: 0x7598f6d6c8
	public Boolean TryGetValue(CustomStyleProperty`1 property, out Single value) { }
	// RVA: 0x695581c VA: 0x7598f6d81c
	public Boolean TryGetValue(CustomStyleProperty`1 property, out Int32 value) { }
	// RVA: 0x69558dc VA: 0x7598f6d8dc
	public Boolean TryGetValue(CustomStyleProperty`1 property, out Color value) { }
	// RVA: 0x6955b2c VA: 0x7598f6db2c
	public Boolean TryGetValue(CustomStyleProperty`1 property, out Texture2D value) { }
	// RVA: 0x6955c40 VA: 0x7598f6dc40
	public Boolean TryGetValue(CustomStyleProperty`1 property, out Sprite value) { }
	// RVA: 0x6955d54 VA: 0x7598f6dd54
	public Boolean TryGetValue(CustomStyleProperty`1 property, out VectorImage value) { }
	// RVA: 0x6955e68 VA: 0x7598f6de68
	public Boolean TryGetValue(CustomStyleProperty`1 property, out String value) { }
	// RVA: 0x6955764 VA: 0x7598f6d764
	private Boolean TryGetValue(String propertyName, StyleValueType valueType, out StylePropertyValue customProp) { }
	// RVA: 0x6955a28 VA: 0x7598f6da28
	private static Void LogCustomPropertyWarning(String propertyName, StyleValueType valueType, StylePropertyValue customProp) { }
	// RVA: 0x69541e8 VA: 0x7598f6c1e8
	public Void .ctor() { }
}
```