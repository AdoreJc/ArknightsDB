# ObjectCheckers

**Namespace:** `XLua`


## Fields

- `ObjectTranslator translator`


## Methods

- `Boolean luaTableCheck(IntPtr, Int32)`

- `Boolean numberCheck(IntPtr, Int32)`

- `Boolean decimalCheck(IntPtr, Int32)`

- `Boolean strCheck(IntPtr, Int32)`

- `Boolean bytesCheck(IntPtr, Int32)`

- `Boolean boolCheck(IntPtr, Int32)`

- `Boolean int64Check(IntPtr, Int32)`

- `Boolean uint64Check(IntPtr, Int32)`

- `Boolean luaFunctionCheck(IntPtr, Int32)`

- `Boolean intptrCheck(IntPtr, Int32)`

- `ObjectCheck genChecker(Type)`

- `ObjectCheck genNullableChecker(ObjectCheck)`

- `ObjectCheck GetChecker(Type)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : XLua
public class ObjectCheckers
{
	private Dictionary`2 checkersMap; // 0x10
	private ObjectTranslator translator; // 0x18


	// RVA: 0x3febc7c VA: 0x7596603c7c
	public Void .ctor(ObjectTranslator translator) { }
	// RVA: 0x3fec580 VA: 0x7596604580
	private static Boolean objectCheck(IntPtr L, Int32 idx) { }
	// RVA: 0x3fec588 VA: 0x7596604588
	private Boolean luaTableCheck(IntPtr L, Int32 idx) { }
	// RVA: 0x3fec720 VA: 0x7596604720
	private Boolean numberCheck(IntPtr L, Int32 idx) { }
	// RVA: 0x3fec740 VA: 0x7596604740
	private Boolean decimalCheck(IntPtr L, Int32 idx) { }
	// RVA: 0x3fec79c VA: 0x759660479c
	private Boolean strCheck(IntPtr L, Int32 idx) { }
	// RVA: 0x3fec7e8 VA: 0x75966047e8
	private Boolean bytesCheck(IntPtr L, Int32 idx) { }
	// RVA: 0x3fec8ac VA: 0x75966048ac
	private Boolean boolCheck(IntPtr L, Int32 idx) { }
	// RVA: 0x3fec8cc VA: 0x75966048cc
	private Boolean int64Check(IntPtr L, Int32 idx) { }
	// RVA: 0x3fec9a0 VA: 0x75966049a0
	private Boolean uint64Check(IntPtr L, Int32 idx) { }
	// RVA: 0x3feca70 VA: 0x7596604a70
	private Boolean luaFunctionCheck(IntPtr L, Int32 idx) { }
	// RVA: 0x3fecb6c VA: 0x7596604b6c
	private Boolean intptrCheck(IntPtr L, Int32 idx) { }
	// RVA: 0x3fecb8c VA: 0x7596604b8c
	private ObjectCheck genChecker(Type type) { }
	// RVA: 0x3fecf10 VA: 0x7596604f10
	public ObjectCheck genNullableChecker(ObjectCheck oc) { }
	// RVA: 0x3fecfcc VA: 0x7596604fcc
	public ObjectCheck GetChecker(Type type) { }
}
```