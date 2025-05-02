# StateStackContext

**Namespace:** ` `


## Methods

- `Void UpdateCache(Stack`1)`

- `Boolean CheckOpenByDungeonStateInPredicatedStack(Type)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class StateStackContext : IHotfixable
{
	private static readonly Type DUNGEON_STATE_TYPE; // 0x0
	private Stack`1 m_stateStack; // 0x10
	private static DelegateBridge __Hotfix0_UpdateCache; // 0x8
	private static DelegateBridge __Hotfix0_CheckOpenByDungeonStateInPredicatedStack; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2aa90ac VA: 0x75950c10ac
	public Void UpdateCache(Stack`1 statePredicatedStack) { }
	// RVA: 0x2aabb74 VA: 0x75950c3b74
	public Boolean CheckOpenByDungeonStateInPredicatedStack(Type targetStateType) { }
	// RVA: 0x2aacd74 VA: 0x75950c4d74
	public Void .ctor() { }
	// RVA: 0x2aad00c VA: 0x75950c500c
	private static Void .cctor() { }
}
```