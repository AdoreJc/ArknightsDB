# EnemyDuelPageRoutePolicy

**Namespace:** ` `


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class EnemyDuelPageRoutePolicy : ActivityEntryPageRoutePolicy, IHotfixable
{
	private static DelegateBridge __Hotfix0_GenerateEntryPageRoutePath; // 0x0
	private static DelegateBridge __Hotfix0_GenerateRoutePathsOverEntry; // 0x8
	private static DelegateBridge __Hotfix0_GetActType; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x29458a4 VA: 0x7594f5d8a4
	protected override ActivityPageRoutePath GenerateEntryPageRoutePath(CommonEntryRouteInput param) { }
	// RVA: 0x29459c8 VA: 0x7594f5d9c8
	protected override List`1 GenerateRoutePathsOverEntry(String actId, BattleOutRouteInput param) { }
	// RVA: 0x2945c9c VA: 0x7594f5dc9c
	protected override ActivityType GetActType() { }
	// RVA: 0x2945d04 VA: 0x7594f5dd04
	public Void .ctor() { }
	// RVA: 0x2945d74 VA: 0x7594f5dd74
	private List`1 <>xLuaBaseProxy_GenerateRoutePathsOverEntry(String P0, BattleOutRouteInput P1) { }
}
```