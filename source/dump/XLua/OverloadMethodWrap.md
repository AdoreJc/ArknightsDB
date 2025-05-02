# OverloadMethodWrap

**Namespace:** `XLua`


## Fields

- `ObjectTranslator translator`

- `Type targetType`

- `MethodBase method`

- `Boolean isVoid`

- `Int32 luaStackPosStart`

- `Boolean targetNeeded`

- `Type paramsType`

- `Boolean <HasDefalutValue>k__BackingField`


## Properties

- `Boolean HasDefalutValue`


## Methods

- `Boolean get_HasDefalutValue()`

- `Void set_HasDefalutValue(Boolean)`

- `Void Init(ObjectCheckers, ObjectCasters)`

- `Boolean Check(IntPtr)`

- `Int32 Call(IntPtr)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : XLua
public class OverloadMethodWrap
{
	private ObjectTranslator translator; // 0x10
	private Type targetType; // 0x18
	private MethodBase method; // 0x20
	private ObjectCheck[] checkArray; // 0x28
	private ObjectCast[] castArray; // 0x30
	private Int32[] inPosArray; // 0x38
	private Int32[] outPosArray; // 0x40
	private Boolean[] isOptionalArray; // 0x48
	private Object[] defaultValueArray; // 0x50
	private Boolean isVoid; // 0x58
	private Int32 luaStackPosStart; // 0x5c
	private Boolean targetNeeded; // 0x60
	private Object[] args; // 0x68
	private Int32[] refPos; // 0x70
	private Type paramsType; // 0x78
	private Boolean <HasDefalutValue>k__BackingField; // 0x80

	public Boolean HasDefalutValue { get; set; }

	// RVA: 0x3edd590 VA: 0x75964f5590
	public Boolean get_HasDefalutValue() { }
	// RVA: 0x3edd598 VA: 0x75964f5598
	private Void set_HasDefalutValue(Boolean value) { }
	// RVA: 0x3edd5a4 VA: 0x75964f55a4
	public Void .ctor(ObjectTranslator translator, Type targetType, MethodBase method) { }
	// RVA: 0x3edd618 VA: 0x75964f5618
	public Void Init(ObjectCheckers objCheckers, ObjectCasters objCasters) { }
	// RVA: 0x3ede408 VA: 0x75964f6408
	public Boolean Check(IntPtr L) { }
	// RVA: 0x3ede600 VA: 0x75964f6600
	public Int32 Call(IntPtr L) { }
}
```