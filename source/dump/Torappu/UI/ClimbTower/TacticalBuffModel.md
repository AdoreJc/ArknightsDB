# TacticalBuffModel

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `ProfessionCategory m_profession`

- `Int32 m_selectIdx`


## Properties

- `ProfessionCategory profession`

- `String currentBuffId`

- `Int32 currentIdx`

- `Boolean isToggle`


## Methods

- `Void SelectBuff(String)`

- `Void ToggleBuff()`

- `ProfessionCategory get_profession()`

- `String get_currentBuffId()`

- `Int32 get_currentIdx()`

- `Boolean get_isToggle()`

- `String GetProfessionIconName()`

- `String GetCurrentDesc()`

- `String GetCurrentBuffName()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class TacticalBuffModel : IHotfixable
{
	private ProfessionCategory m_profession; // 0x10
	private List`1 m_buffItemList; // 0x18
	private Int32 m_selectIdx; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_SelectBuff; // 0x8
	private static DelegateBridge __Hotfix0_ToggleBuff; // 0x10
	private static DelegateBridge __Hotfix0_get_profession; // 0x18
	private static DelegateBridge __Hotfix0_get_buffList; // 0x20
	private static DelegateBridge __Hotfix0_get_currentBuffId; // 0x28
	private static DelegateBridge __Hotfix0_get_currentIdx; // 0x30
	private static DelegateBridge __Hotfix0_get_isToggle; // 0x38
	private static DelegateBridge __Hotfix0_GetProfessionIconName; // 0x40
	private static DelegateBridge __Hotfix0_GetCurrentDesc; // 0x48
	private static DelegateBridge __Hotfix0_GetCurrentBuffName; // 0x50

	public ProfessionCategory profession { get; }
	public List`1 buffList { get; }
	public String currentBuffId { get; }
	public Int32 currentIdx { get; }
	public Boolean isToggle { get; }

	// RVA: 0x2c8bd60 VA: 0x75952a3d60
	public Void .ctor(ProfessionCategory profession, List`1 buffList, Boolean hasTowerPass) { }
	// RVA: 0x2c8c0fc VA: 0x75952a40fc
	public Void SelectBuff(String tacticalId) { }
	// RVA: 0x2c8c21c VA: 0x75952a421c
	public Void ToggleBuff() { }
	// RVA: 0x2c890a0 VA: 0x75952a10a0
	public ProfessionCategory get_profession() { }
	// RVA: 0x2c8c4d0 VA: 0x75952a44d0
	public List`1 get_buffList() { }
	// RVA: 0x2c8a670 VA: 0x75952a2670
	public String get_currentBuffId() { }
	// RVA: 0x2c8c538 VA: 0x75952a4538
	public Int32 get_currentIdx() { }
	// RVA: 0x2c89308 VA: 0x75952a1308
	public Boolean get_isToggle() { }
	// RVA: 0x2c88fc4 VA: 0x75952a0fc4
	public String GetProfessionIconName() { }
	// RVA: 0x2c89108 VA: 0x75952a1108
	public String GetCurrentDesc() { }
	// RVA: 0x2c891cc VA: 0x75952a11cc
	public String GetCurrentBuffName() { }
}
```