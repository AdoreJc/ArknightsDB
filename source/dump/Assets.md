# Assets

**Namespace:** ` `


## Fields

- `Int32 m_groupId`


## Methods

- `T LoadAsset(String)`

- `Object LoadAsset(String)`

- `Boolean TryLoadAsset(String, out)`

- `Void UnloadAsset(Object)`

- `Void UnloadAssets()`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : 
public class Assets : IAssets, ILoadAsset, IHotfixable
{
	private Int32 m_groupId; // 0x10
	private static __XLua_Gen_Delegate1 _c__Hotfix0_ctor; // 0x0
	private static __XLua_Gen_Delegate143 __Hotfix0_Create; // 0x8
	private static __XLua_Gen_Delegate144 __Hotfix0_LoadAsset; // 0x10
	private static __XLua_Gen_Delegate0 __Hotfix0_UnloadAsset; // 0x18
	private static __XLua_Gen_Delegate1 __Hotfix0_UnloadAssets; // 0x20


	// RVA: 0x6797068 VA: 0x7598daf068
	private Void .ctor() { }
	// RVA: 0x67970e0 VA: 0x7598daf0e0
	public static Assets Create(Int32 groupId) { }
	// RVA: 0x VA: 0x0
	public T LoadAsset(String path) { }
	// RVA: 0x679717c VA: 0x7598daf17c
	public Object LoadAsset(String path) { }
	// RVA: 0x VA: 0x0
	public Boolean TryLoadAsset(String path, out T obj) { }
	// RVA: 0x679721c VA: 0x7598daf21c
	public Void UnloadAsset(Object asset) { }
	// RVA: 0x67972bc VA: 0x7598daf2bc
	public Void UnloadAssets() { }
}
```