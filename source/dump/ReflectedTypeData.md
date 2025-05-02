# ReflectedTypeData

**Namespace:** ` `


## Fields

- `Type _type`

- `AttributeCollection _attributes`

- `EventDescriptorCollection _events`

- `PropertyDescriptorCollection _properties`

- `TypeConverter _converter`

- `Int32 _editorCount`


## Methods

- `Type GetTypeFromName(String)`


## Dump
```C#
// Dll : System.dll
// Namespace : 
private class ReflectedTypeData
{
	private Type _type; // 0x10
	private AttributeCollection _attributes; // 0x18
	private EventDescriptorCollection _events; // 0x20
	private PropertyDescriptorCollection _properties; // 0x28
	private TypeConverter _converter; // 0x30
	private Object[] _editors; // 0x38
	private Type[] _editorTypes; // 0x40
	private Int32 _editorCount; // 0x48

	internal Boolean IsPopulated { get; }

	// RVA: 0x63effa4 VA: 0x7598a07fa4
	internal Void .ctor(Type type) { }
	// RVA: 0x63effd4 VA: 0x7598a07fd4
	internal Boolean get_IsPopulated() { }
	// RVA: 0x63efff0 VA: 0x7598a07ff0
	internal AttributeCollection GetAttributes() { }
	// RVA: 0x63f0930 VA: 0x7598a08930
	internal String GetClassName(Object instance) { }
	// RVA: 0x63f0954 VA: 0x7598a08954
	internal String GetComponentName(Object instance) { }
	// RVA: 0x63f0b00 VA: 0x7598a08b00
	internal TypeConverter GetConverter(Object instance) { }
	// RVA: 0x63f11ac VA: 0x7598a091ac
	internal EventDescriptor GetDefaultEvent(Object instance) { }
	// RVA: 0x63f1508 VA: 0x7598a09508
	internal PropertyDescriptor GetDefaultProperty(Object instance) { }
	// RVA: 0x63f1860 VA: 0x7598a09860
	internal Object GetEditor(Object instance, Type editorBaseType) { }
	// RVA: 0x63f1e60 VA: 0x7598a09e60
	private static EditorAttribute GetEditorAttribute(AttributeCollection attributes, Type editorBaseType) { }
	// RVA: 0x63f2228 VA: 0x7598a0a228
	internal EventDescriptorCollection GetEvents() { }
	// RVA: 0x63f2538 VA: 0x7598a0a538
	internal PropertyDescriptorCollection GetProperties() { }
	// RVA: 0x63f1004 VA: 0x7598a09004
	private Type GetTypeFromName(String typeName) { }
	// RVA: 0x63f2848 VA: 0x7598a0a848
	internal Void Refresh() { }
}
```