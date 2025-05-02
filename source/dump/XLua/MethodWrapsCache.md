# MethodWrapsCache

**Namespace:** `XLua`


## Fields

- `ObjectTranslator translator`

- `ObjectCheckers objCheckers`

- `ObjectCasters objCasters`


## Methods

- `lua_CSFunction GetConstructorWrap(Type)`

- `lua_CSFunction GetMethodWrap(Type, String)`

- `lua_CSFunction GetMethodWrapInCache(Type, String)`

- `lua_CSFunction GetDelegateWrap(Type)`

- `lua_CSFunction GetEventWrap(Type, String)`

- `MethodWrap _GenMethodWrap(Type, String, IEnumerable`1, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : XLua
public class MethodWrapsCache
{
	private ObjectTranslator translator; // 0x10
	private ObjectCheckers objCheckers; // 0x18
	private ObjectCasters objCasters; // 0x20
	private Dictionary`2 constructorCache; // 0x28
	private Dictionary`2 methodsCache; // 0x30
	private Dictionary`2 delegateCache; // 0x38


	// RVA: 0x3fe9638 VA: 0x7596601638
	public Void .ctor(ObjectTranslator translator, ObjectCheckers objCheckers, ObjectCasters objCasters) { }
	// RVA: 0x3fe978c VA: 0x759660178c
	public lua_CSFunction GetConstructorWrap(Type type) { }
	// RVA: 0x3fea12c VA: 0x759660212c
	public lua_CSFunction GetMethodWrap(Type type, String methodName) { }
	// RVA: 0x3fea380 VA: 0x7596602380
	public lua_CSFunction GetMethodWrapInCache(Type type, String methodName) { }
	// RVA: 0x3fea4e4 VA: 0x75966024e4
	public lua_CSFunction GetDelegateWrap(Type type) { }
	// RVA: 0x3fea734 VA: 0x7596602734
	public lua_CSFunction GetEventWrap(Type type, String eventName) { }
	// RVA: 0x3fe9c40 VA: 0x7596601c40
	public MethodWrap _GenMethodWrap(Type type, String methodName, IEnumerable`1 methodBases, Boolean forceCheck) { }
	// RVA: 0x3feab80 VA: 0x7596602b80
	private static Boolean tryMakeGenericMethod(ref MethodBase method) { }
}
```