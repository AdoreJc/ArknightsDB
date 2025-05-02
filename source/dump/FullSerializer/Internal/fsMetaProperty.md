# fsMetaProperty

**Namespace:** `FullSerializer.Internal`


## Fields

- `MemberInfo _memberInfo`

- `Type <StorageType>k__BackingField`

- `Type <OverrideConverterType>k__BackingField`

- `Boolean <CanRead>k__BackingField`

- `Boolean <CanWrite>k__BackingField`

- `String <JsonName>k__BackingField`

- `String <MemberName>k__BackingField`

- `Boolean <IsPublic>k__BackingField`


## Properties

- `Type StorageType`

- `Type OverrideConverterType`

- `Boolean CanRead`

- `Boolean CanWrite`

- `String JsonName`

- `String MemberName`

- `Boolean IsPublic`


## Methods

- `Void CommonInitialize(fsConfig)`

- `Type get_StorageType()`

- `Void set_StorageType(Type)`

- `Type get_OverrideConverterType()`

- `Void set_OverrideConverterType(Type)`

- `Boolean get_CanRead()`

- `Void set_CanRead(Boolean)`

- `Boolean get_CanWrite()`

- `Void set_CanWrite(Boolean)`

- `String get_JsonName()`

- `Void set_JsonName(String)`

- `String get_MemberName()`

- `Void set_MemberName(String)`

- `Boolean get_IsPublic()`

- `Void set_IsPublic(Boolean)`

- `Void Write(Object, Object)`

- `Object Read(Object)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : FullSerializer.Internal
public class fsMetaProperty
{
	private MemberInfo _memberInfo; // 0x10
	private Type <StorageType>k__BackingField; // 0x18
	private Type <OverrideConverterType>k__BackingField; // 0x20
	private Boolean <CanRead>k__BackingField; // 0x28
	private Boolean <CanWrite>k__BackingField; // 0x29
	private String <JsonName>k__BackingField; // 0x30
	private String <MemberName>k__BackingField; // 0x38
	private Boolean <IsPublic>k__BackingField; // 0x40

	public Type StorageType { get; set; }
	public Type OverrideConverterType { get; set; }
	public Boolean CanRead { get; set; }
	public Boolean CanWrite { get; set; }
	public String JsonName { get; set; }
	public String MemberName { get; set; }
	public Boolean IsPublic { get; set; }

	// RVA: 0x34bae08 VA: 0x7595ad2e08
	internal Void .ctor(fsConfig config, FieldInfo field) { }
	// RVA: 0x34baaa8 VA: 0x7595ad2aa8
	internal Void .ctor(fsConfig config, PropertyInfo property) { }
	// RVA: 0x34c5c74 VA: 0x7595addc74
	private Void CommonInitialize(fsConfig config) { }
	// RVA: 0x34c5d74 VA: 0x7595addd74
	public Type get_StorageType() { }
	// RVA: 0x34c5d7c VA: 0x7595addd7c
	private Void set_StorageType(Type value) { }
	// RVA: 0x34c5d84 VA: 0x7595addd84
	public Type get_OverrideConverterType() { }
	// RVA: 0x34c5d8c VA: 0x7595addd8c
	private Void set_OverrideConverterType(Type value) { }
	// RVA: 0x34c5d94 VA: 0x7595addd94
	public Boolean get_CanRead() { }
	// RVA: 0x34c5d9c VA: 0x7595addd9c
	private Void set_CanRead(Boolean value) { }
	// RVA: 0x34c5da8 VA: 0x7595addda8
	public Boolean get_CanWrite() { }
	// RVA: 0x34c5db0 VA: 0x7595adddb0
	private Void set_CanWrite(Boolean value) { }
	// RVA: 0x34c5dbc VA: 0x7595adddbc
	public String get_JsonName() { }
	// RVA: 0x34c5dc4 VA: 0x7595adddc4
	private Void set_JsonName(String value) { }
	// RVA: 0x34c5dcc VA: 0x7595adddcc
	public String get_MemberName() { }
	// RVA: 0x34c5dd4 VA: 0x7595adddd4
	private Void set_MemberName(String value) { }
	// RVA: 0x34c5ddc VA: 0x7595addddc
	public Boolean get_IsPublic() { }
	// RVA: 0x34c5de4 VA: 0x7595addde4
	private Void set_IsPublic(Boolean value) { }
	// RVA: 0x34bf504 VA: 0x7595ad7504
	public Void Write(Object context, Object value) { }
	// RVA: 0x34bf268 VA: 0x7595ad7268
	public Object Read(Object context) { }
}
```