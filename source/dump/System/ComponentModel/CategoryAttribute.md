# CategoryAttribute

**Namespace:** `System.ComponentModel`


## Fields

- `Boolean localized`

- `String categoryValue`


## Properties

- `String Category`


## Methods

- `String get_Category()`


## Dump
```C#
// Dll : System.dll
// Namespace : System.ComponentModel
public class CategoryAttribute : Attribute
{
	private static CategoryAttribute appearance; // 0x0
	private static CategoryAttribute asynchronous; // 0x8
	private static CategoryAttribute behavior; // 0x10
	private static CategoryAttribute data; // 0x18
	private static CategoryAttribute design; // 0x20
	private static CategoryAttribute action; // 0x28
	private static CategoryAttribute format; // 0x30
	private static CategoryAttribute layout; // 0x38
	private static CategoryAttribute mouse; // 0x40
	private static CategoryAttribute key; // 0x48
	private static CategoryAttribute focus; // 0x50
	private static CategoryAttribute windowStyle; // 0x58
	private static CategoryAttribute dragDrop; // 0x60
	private static CategoryAttribute defAttr; // 0x68
	private Boolean localized; // 0x10
	private String categoryValue; // 0x18

	public static CategoryAttribute Action { get; }
	public static CategoryAttribute Appearance { get; }
	public static CategoryAttribute Asynchronous { get; }
	public static CategoryAttribute Behavior { get; }
	public static CategoryAttribute Data { get; }
	public static CategoryAttribute Default { get; }
	public static CategoryAttribute Design { get; }
	public static CategoryAttribute DragDrop { get; }
	public static CategoryAttribute Focus { get; }
	public static CategoryAttribute Format { get; }
	public static CategoryAttribute Key { get; }
	public static CategoryAttribute Layout { get; }
	public static CategoryAttribute Mouse { get; }
	public static CategoryAttribute WindowStyle { get; }
	public String Category { get; }

	// RVA: 0x63dbcc0 VA: 0x75989f3cc0
	public static CategoryAttribute get_Action() { }
	// RVA: 0x63dbdbc VA: 0x75989f3dbc
	public static CategoryAttribute get_Appearance() { }
	// RVA: 0x63dbe88 VA: 0x75989f3e88
	public static CategoryAttribute get_Asynchronous() { }
	// RVA: 0x63dbf4c VA: 0x75989f3f4c
	public static CategoryAttribute get_Behavior() { }
	// RVA: 0x63dc010 VA: 0x75989f4010
	public static CategoryAttribute get_Data() { }
	// RVA: 0x63dc0d4 VA: 0x75989f40d4
	public static CategoryAttribute get_Default() { }
	// RVA: 0x63dc1cc VA: 0x75989f41cc
	public static CategoryAttribute get_Design() { }
	// RVA: 0x63dc290 VA: 0x75989f4290
	public static CategoryAttribute get_DragDrop() { }
	// RVA: 0x63dc354 VA: 0x75989f4354
	public static CategoryAttribute get_Focus() { }
	// RVA: 0x63dc418 VA: 0x75989f4418
	public static CategoryAttribute get_Format() { }
	// RVA: 0x63dc4dc VA: 0x75989f44dc
	public static CategoryAttribute get_Key() { }
	// RVA: 0x63dc5a0 VA: 0x75989f45a0
	public static CategoryAttribute get_Layout() { }
	// RVA: 0x63dc664 VA: 0x75989f4664
	public static CategoryAttribute get_Mouse() { }
	// RVA: 0x63dc728 VA: 0x75989f4728
	public static CategoryAttribute get_WindowStyle() { }
	// RVA: 0x63dc168 VA: 0x75989f4168
	public Void .ctor() { }
	// RVA: 0x63dbd84 VA: 0x75989f3d84
	public Void .ctor(String category) { }
	// RVA: 0x63dc7ec VA: 0x75989f47ec
	public String get_Category() { }
	// RVA: 0x63dc844 VA: 0x75989f4844
	public override Boolean Equals(Object obj) { }
	// RVA: 0x63dc934 VA: 0x75989f4934
	public override Int32 GetHashCode() { }
	// RVA: 0x63dc954 VA: 0x75989f4954
	protected virtual String GetLocalizedString(String value) { }
	// RVA: 0x63dccc0 VA: 0x75989f4cc0
	public override Boolean IsDefaultAttribute() { }
}
```