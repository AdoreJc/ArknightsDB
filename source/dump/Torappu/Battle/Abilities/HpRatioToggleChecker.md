# HpRatioToggleChecker

**Namespace:** `Torappu.Battle.Abilities`


## Fields

- `Single _minHpRatio`

- `Single _maxHpRatio`

- `Boolean _useLTForMax`

- `Single _restoreDelay`

- `Boolean _toggleOnce`

- `Boolean _setInitialToggle`

- `Boolean _initialToggle`

- `Boolean _loadMinHpRatioFromBlackboard`

- `Single m_minHpRatio`

- `Single m_maxHpRatio`

- `Single m_restoreDelay`

- `Boolean m_hasToggleChanged`


## Properties

- `Boolean setInitialToggle`


## Methods

- `Boolean get_setInitialToggle()`

- `Boolean _CheckCondition()`

- `Single <>xLuaBaseProxy_get_restoreDelay()`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Abilities
public class HpRatioToggleChecker : Checker
{
	private Single _minHpRatio; // 0x20
	private Single _maxHpRatio; // 0x24
	private Boolean _useLTForMax; // 0x28
	private Single _restoreDelay; // 0x2c
	private Boolean _toggleOnce; // 0x30
	private Boolean _setInitialToggle; // 0x31
	private Boolean _initialToggle; // 0x32
	private Boolean _loadMinHpRatioFromBlackboard; // 0x33
	private Single m_minHpRatio; // 0x34
	private Single m_maxHpRatio; // 0x38
	private Single m_restoreDelay; // 0x3c
	private Boolean m_hasToggleChanged; // 0x40
	private static DelegateBridge __Hotfix0_get_restoreDelay; // 0x0
	private static DelegateBridge __Hotfix0_get_setInitialToggle; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge __Hotfix0_CheckInitialToggled; // 0x18
	private static DelegateBridge __Hotfix0_OnTick; // 0x20
	private static DelegateBridge __Hotfix0__CheckCondition; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public override Single restoreDelay { get; }
	private Boolean setInitialToggle { get; }

	// RVA: 0x1e5ce54 VA: 0x7594474e54
	public override Single get_restoreDelay() { }
	// RVA: 0x1e5cebc VA: 0x7594474ebc
	private Boolean get_setInitialToggle() { }
	// RVA: 0x1e5cf24 VA: 0x7594474f24
	protected override Void LoadData(Blackboard blackboard) { }
	// RVA: 0x1e5d03c VA: 0x759447503c
	public override Boolean CheckInitialToggled() { }
	// RVA: 0x1e5d2c4 VA: 0x75944752c4
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x1e5d0bc VA: 0x75944750bc
	private Boolean _CheckCondition() { }
	// RVA: 0x1e5d3a4 VA: 0x75944753a4
	public Void .ctor() { }
	// RVA: 0x1e5d420 VA: 0x7594475420
	private Single <>xLuaBaseProxy_get_restoreDelay() { }
	// RVA: 0x1e5d424 VA: 0x7594475424
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```