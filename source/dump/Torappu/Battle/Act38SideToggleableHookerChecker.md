# Act38SideToggleableHookerChecker

**Namespace:** `Torappu.Battle`


## Fields

- `Int32 _level`

- `String _eventSystemKey`

- `Act38SideBattleManager m_manager`


## Properties

- `Act38SideBattleManager manager`


## Methods

- `Act38SideBattleManager get_manager()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class Act38SideToggleableHookerChecker : ToggleableHookerChecker
{
	private Int32 _level; // 0x18
	private String _eventSystemKey; // 0x20
	private Act38SideBattleManager m_manager; // 0x28
	private static DelegateBridge __Hotfix0_get_manager; // 0x0
	private static DelegateBridge __Hotfix0_CheckValidity; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Act38SideBattleManager manager { get; }

	// RVA: 0x3f5f4e0 VA: 0x75965774e0
	public Act38SideBattleManager get_manager() { }
	// RVA: 0x3f5f5dc VA: 0x75965775dc
	public override Boolean CheckValidity() { }
	// RVA: 0x3f5f664 VA: 0x7596577664
	public Void .ctor() { }
}
```