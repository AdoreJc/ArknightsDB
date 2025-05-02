# MhPartHpHudPluginTalent

**Namespace:** `Torappu.Battle`


## Fields

- `Single _hpRatio`

- `FacePosition _facePosition`

- `String _logKey`

- `FP m_partMaxHpRatio`

- `FP m_maxPartHp`

- `FP m_partHp`

- `String m_extraBattleLogKey`


## Properties

- `FP partHpRatio`


## Methods

- `FP get_partHpRatio()`

- `Void _OnApplyedModifier(Object)`

- `Boolean _CheckDirection(Vector2)`

- `Void _OnHudCreated(Object)`

- `Void _OnPartHpZero()`

- `Boolean _CheckOwnerValidMode()`

- `Void <>xLuaBaseProxy_AssignData(TalentData, Unit, Delta)`

- `Void <>xLuaBaseProxy_DoAttach()`

- `Void <>xLuaBaseProxy_DoDetach()`

- `Void <>xLuaBaseProxy_GatherBuffs(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class MhPartHpHudPluginTalent : UIPluginTalent
{
	private Single _hpRatio; // 0x60
	private BuffData[] _buffsToTirgger; // 0x68
	private Int32[] _validModeIndices; // 0x70
	private FacePosition _facePosition; // 0x78
	private String _logKey; // 0x80
	private FP m_partMaxHpRatio; // 0x88
	private FP m_maxPartHp; // 0x90
	private FP m_partHp; // 0x98
	private String m_extraBattleLogKey; // 0xa0
	private List`1 m_buffUids; // 0xa8
	private static DelegateBridge __Hotfix0_get_type; // 0x0
	private static DelegateBridge __Hotfix0_get_partHpRatio; // 0x8
	private static DelegateBridge __Hotfix0_get_validModeIndices; // 0x10
	private static DelegateBridge __Hotfix0_LoadPlugin; // 0x18
	private static DelegateBridge __Hotfix0_AssignData; // 0x20
	private static DelegateBridge __Hotfix0_DoAttach; // 0x28
	private static DelegateBridge __Hotfix0_DoDetach; // 0x30
	private static DelegateBridge __Hotfix0_GatherBuffs; // 0x38
	private static DelegateBridge __Hotfix0__OnApplyedModifier; // 0x40
	private static DelegateBridge __Hotfix0__CheckDirection; // 0x48
	private static DelegateBridge __Hotfix0__OnHudCreated; // 0x50
	private static DelegateBridge __Hotfix0__OnPartHpZero; // 0x58
	private static DelegateBridge __Hotfix0__CheckOwnerValidMode; // 0x60
	private static DelegateBridge _c__Hotfix0_ctor; // 0x68

	public override PluginType type { get; }
	public FP partHpRatio { get; }
	public Int32[] validModeIndices { get; }

	// RVA: 0x1b86630 VA: 0x759419e630
	public override PluginType get_type() { }
	// RVA: 0x1b86694 VA: 0x759419e694
	public FP get_partHpRatio() { }
	// RVA: 0x1b8672c VA: 0x759419e72c
	public Int32[] get_validModeIndices() { }
	// RVA: 0x1b86794 VA: 0x759419e794
	protected override UnitTalentUIPlugin LoadPlugin(String pluginName) { }
	// RVA: 0x1b868b0 VA: 0x759419e8b0
	public override Void AssignData(TalentData data, Unit owner, Delta modifier) { }
	// RVA: 0x1b86b00 VA: 0x759419eb00
	protected override Void DoAttach() { }
	// RVA: 0x1b86cec VA: 0x759419ecec
	protected override Void DoDetach() { }
	// RVA: 0x1b86ebc VA: 0x759419eebc
	public override Void GatherBuffs(List`1 results) { }
	// RVA: 0x1b86f6c VA: 0x759419ef6c
	private Void _OnApplyedModifier(Object arg) { }
	// RVA: 0x1b874a8 VA: 0x759419f4a8
	private Boolean _CheckDirection(Vector2 mapDir) { }
	// RVA: 0x1b87724 VA: 0x759419f724
	private Void _OnHudCreated(Object arg) { }
	// RVA: 0x1b875bc VA: 0x759419f5bc
	private Void _OnPartHpZero() { }
	// RVA: 0x1b873c4 VA: 0x759419f3c4
	private Boolean _CheckOwnerValidMode() { }
	// RVA: 0x1b87820 VA: 0x759419f820
	public Void .ctor() { }
	// RVA: 0x1b87894 VA: 0x759419f894
	private Void <>xLuaBaseProxy_AssignData(TalentData P0, Unit P1, Delta P2) { }
	// RVA: 0x1b8789c VA: 0x759419f89c
	private Void <>xLuaBaseProxy_DoAttach() { }
	// RVA: 0x1b878a0 VA: 0x759419f8a0
	private Void <>xLuaBaseProxy_DoDetach() { }
	// RVA: 0x1b878a8 VA: 0x759419f8a8
	private Void <>xLuaBaseProxy_GatherBuffs(List`1 P0) { }
}
```