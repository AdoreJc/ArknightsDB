# Roguelike2SchedulerPreprocessor

**Namespace:** `Torappu.Battle`


## Fields

- `Roguelike2RetainData m_retainData`


## Methods

- `Void <>xLuaBaseProxy_DoPreprocess(LevelData)`

- `Void <>xLuaBaseProxy_Dispose()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class Roguelike2SchedulerPreprocessor : RoguelikeSchedulerPreprocessor
{
	private Roguelike2RetainData m_retainData; // 0x40
	private Dictionary`2 m_rogue2TrapGroups; // 0x50
	private readonly HashSet`1 m_actionPacksToDelete; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_DoPreprocess; // 0x8
	private static DelegateBridge __Hotfix0_Dispose; // 0x10


	// RVA: 0x40c8cc0 VA: 0x75966e0cc0
	public Void .ctor(RoguelikeInput input) { }
	// RVA: 0x40c8e24 VA: 0x75966e0e24
	public override Void DoPreprocess(LevelData levelData) { }
	// RVA: 0x40cadc4 VA: 0x75966e2dc4
	public override Void Dispose() { }
	// RVA: 0x40cae7c VA: 0x75966e2e7c
	private Void <>xLuaBaseProxy_DoPreprocess(LevelData P0) { }
	// RVA: 0x40cae84 VA: 0x75966e2e84
	private Void <>xLuaBaseProxy_Dispose() { }
}
```