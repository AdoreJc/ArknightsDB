# LoadAdditiveModuleInstruction

**Namespace:** ` `


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class LoadAdditiveModuleInstruction : CustomYieldInstruction
{
	private List`1 m_loadTasks; // 0x10

	public override Boolean keepWaiting { get; }

	// RVA: 0x3f7219c VA: 0x759658a19c
	public override Boolean get_keepWaiting() { }
	// RVA: 0x3f72310 VA: 0x759658a310
	private Void .ctor() { }
	// RVA: 0x3f72318 VA: 0x759658a318
	public static LoadAdditiveModuleInstruction Create(BattleLoader loader, BattleInOut battleInOut) { }
	// RVA: 0x3f723cc VA: 0x759658a3cc
	private static List`1 _CreateAdditiveLoadTasks(BattleLoader loader, BattleInOut battleInOut) { }
	// RVA: 0x3f72560 VA: 0x759658a560
	private static CustomYieldInstruction _CreateLoadUISystem(BattleLoader loader, BattleInOut battleInOut) { }
	// RVA: 0x3f72720 VA: 0x759658a720
	private static IEnumerator _LoadUISystemCoroutine() { }
}
```