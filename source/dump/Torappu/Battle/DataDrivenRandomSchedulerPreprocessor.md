# DataDrivenRandomSchedulerPreprocessor

**Namespace:** `Torappu.Battle`


## Methods

- `Void _ConstructorImpl(List`1)`

- `Void SetSingleActionKilledCount(List`1)`

- `Void SetActionRemainCount(Dictionary`2)`

- `Void _InitValidation(LevelData)`

- `Void _DeleteInvalidActions(LevelData)`

- `Void _ProcessValidActionsViaInputResults(LevelData)`

- `Void _ProcessActionCountViaInputResults(LevelData)`

- `Void _ProcessActionSingleCountViaInputResults(LevelData)`

- `Void _ProcessEmptyActionKeys(LevelData)`

- `Void <>xLuaBaseProxy_DoPreprocess(LevelData)`

- `Void <>xLuaBaseProxy_Dispose()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class DataDrivenRandomSchedulerPreprocessor : DefaultSchedulerPreprocessor
{
	public List`1 m_validActionResults; // 0x10
	public ListDict`2 m_singleActionKilledCount; // 0x18
	public HashSet`1 m_validActionPackKeys; // 0x20
	public Dictionary`2 m_actionRemainCount; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0__ConstructorImpl; // 0x8
	private static DelegateBridge __Hotfix0_SetSingleActionKilledCount; // 0x10
	private static DelegateBridge __Hotfix0_SetActionRemainCount; // 0x18
	private static DelegateBridge __Hotfix0_DoPreprocess; // 0x20
	private static DelegateBridge __Hotfix0__InitValidation; // 0x28
	private static DelegateBridge __Hotfix0__DeleteInvalidActions; // 0x30
	private static DelegateBridge __Hotfix0__ProcessValidActionsViaInputResults; // 0x38
	private static DelegateBridge __Hotfix0__ProcessActionCountViaInputResults; // 0x40
	private static DelegateBridge __Hotfix0__ProcessActionSingleCountViaInputResults; // 0x48
	private static DelegateBridge __Hotfix0__ProcessEmptyActionKeys; // 0x50
	private static DelegateBridge __Hotfix0_Dispose; // 0x58


	// RVA: 0x40e1124 VA: 0x75966f9124
	public Void .ctor(List`1 validActionResults) { }
	// RVA: 0x40e12f8 VA: 0x75966f92f8
	private Void _ConstructorImpl(List`1 validActionResults) { }
	// RVA: 0x40e1634 VA: 0x75966f9634
	public Void SetSingleActionKilledCount(List`1 singleActionRemainCount) { }
	// RVA: 0x40e18d0 VA: 0x75966f98d0
	public Void SetActionRemainCount(Dictionary`2 actionRemainCount) { }
	// RVA: 0x40e1988 VA: 0x75966f9988
	public override Void DoPreprocess(LevelData levelData) { }
	// RVA: 0x40e1ac0 VA: 0x75966f9ac0
	private Void _InitValidation(LevelData levelData) { }
	// RVA: 0x40e2690 VA: 0x75966fa690
	private Void _DeleteInvalidActions(LevelData levelData) { }
	// RVA: 0x40e1c88 VA: 0x75966f9c88
	private Void _ProcessValidActionsViaInputResults(LevelData levelData) { }
	// RVA: 0x40e2210 VA: 0x75966fa210
	private Void _ProcessActionCountViaInputResults(LevelData levelData) { }
	// RVA: 0x40e1fe8 VA: 0x75966f9fe8
	private Void _ProcessActionSingleCountViaInputResults(LevelData levelData) { }
	// RVA: 0x40e24c0 VA: 0x75966fa4c0
	private Void _ProcessEmptyActionKeys(LevelData levelData) { }
	// RVA: 0x40e28e8 VA: 0x75966fa8e8
	public override Void Dispose() { }
	// RVA: 0x40e29c0 VA: 0x75966fa9c0
	private Void <>xLuaBaseProxy_DoPreprocess(LevelData P0) { }
	// RVA: 0x40e29c8 VA: 0x75966fa9c8
	private Void <>xLuaBaseProxy_Dispose() { }
}
```