# ObjectCasters

**Namespace:** `XLua`


## Fields

- `ObjectTranslator translator`


## Methods

- `Object decimalCaster(IntPtr, Int32, Object)`

- `Object getBytes(IntPtr, Int32, Object)`

- `Object getIntptr(IntPtr, Int32, Object)`

- `Object getObject(IntPtr, Int32, Object)`

- `Object getLuaTable(IntPtr, Int32, Object)`

- `Object getLuaFunction(IntPtr, Int32, Object)`

- `Void AddCaster(Type, ObjectCast)`

- `ObjectCast genCaster(Type)`

- `ObjectCast genNullableCaster(ObjectCast)`

- `ObjectCast GetCaster(Type)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : XLua
public class ObjectCasters
{
	private Dictionary`2 castersMap; // 0x10
	private ObjectTranslator translator; // 0x18


	// RVA: 0x3fed524 VA: 0x7596605524
	public Void .ctor(ObjectTranslator translator) { }
	// RVA: 0x3fedec8 VA: 0x7596605ec8
	private static Object charCaster(IntPtr L, Int32 idx, Object target) { }
	// RVA: 0x3fedfb8 VA: 0x7596605fb8
	private static Object sbyteCaster(IntPtr L, Int32 idx, Object target) { }
	// RVA: 0x3fee024 VA: 0x7596606024
	private static Object byteCaster(IntPtr L, Int32 idx, Object target) { }
	// RVA: 0x3fee090 VA: 0x7596606090
	private static Object shortCaster(IntPtr L, Int32 idx, Object target) { }
	// RVA: 0x3fee0fc VA: 0x75966060fc
	private static Object ushortCaster(IntPtr L, Int32 idx, Object target) { }
	// RVA: 0x3fee168 VA: 0x7596606168
	private static Object intCaster(IntPtr L, Int32 idx, Object target) { }
	// RVA: 0x3fee1d4 VA: 0x75966061d4
	private static Object uintCaster(IntPtr L, Int32 idx, Object target) { }
	// RVA: 0x3fee2c4 VA: 0x75966062c4
	private static Object longCaster(IntPtr L, Int32 idx, Object target) { }
	// RVA: 0x3fee3b4 VA: 0x75966063b4
	private static Object ulongCaster(IntPtr L, Int32 idx, Object target) { }
	// RVA: 0x3fee4a0 VA: 0x75966064a0
	private static Object getDouble(IntPtr L, Int32 idx, Object target) { }
	// RVA: 0x3fee588 VA: 0x7596606588
	private static Object floatCaster(IntPtr L, Int32 idx, Object target) { }
	// RVA: 0x3fee5f4 VA: 0x75966065f4
	private Object decimalCaster(IntPtr L, Int32 idx, Object target) { }
	// RVA: 0x3fee6a4 VA: 0x75966066a4
	private static Object getBoolean(IntPtr L, Int32 idx, Object target) { }
	// RVA: 0x3fee7a0 VA: 0x75966067a0
	private static Object getString(IntPtr L, Int32 idx, Object target) { }
	// RVA: 0x3fee7a4 VA: 0x75966067a4
	private Object getBytes(IntPtr L, Int32 idx, Object target) { }
	// RVA: 0x3fee954 VA: 0x7596606954
	private Object getIntptr(IntPtr L, Int32 idx, Object target) { }
	// RVA: 0x3feea44 VA: 0x7596606a44
	private Object getObject(IntPtr L, Int32 idx, Object target) { }
	// RVA: 0x3feeda0 VA: 0x7596606da0
	private Object getLuaTable(IntPtr L, Int32 idx, Object target) { }
	// RVA: 0x3feeec0 VA: 0x7596606ec0
	private Object getLuaFunction(IntPtr L, Int32 idx, Object target) { }
	// RVA: 0x3fef080 VA: 0x7596607080
	public Void AddCaster(Type type, ObjectCast oc) { }
	// RVA: 0x3fef0e8 VA: 0x75966070e8
	private ObjectCast genCaster(Type type) { }
	// RVA: 0x3fef8c4 VA: 0x75966078c4
	private ObjectCast genNullableCaster(ObjectCast oc) { }
	// RVA: 0x3fef77c VA: 0x759660777c
	public ObjectCast GetCaster(Type type) { }
}
```