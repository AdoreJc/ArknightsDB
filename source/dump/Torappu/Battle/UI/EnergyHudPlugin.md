# EnergyHudPlugin

**Namespace:** `Torappu.Battle.UI`


## Fields

- `UIBulletBar _energyBar`

- `UITextSlider _energyCastSlider`

- `EnergyHudPluginTalent m_hudTalent`


## Methods

- `Void Update()`

- `Void <>xLuaBaseProxy_DoAttach(Unit, UIPluginTalent)`

- `Void <>xLuaBaseProxy_DoDetach()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class EnergyHudPlugin : UnitTalentUIPlugin
{
	private UIBulletBar _energyBar; // 0x30
	private UITextSlider _energyCastSlider; // 0x38
	private EnergyHudPluginTalent m_hudTalent; // 0x40
	private static DelegateBridge __Hotfix0_DoAttach; // 0x0
	private static DelegateBridge __Hotfix0_DoDetach; // 0x8
	private static DelegateBridge __Hotfix0_Update; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2019cb8 VA: 0x7594631cb8
	protected override Void DoAttach(Unit owner, UIPluginTalent talent) { }
	// RVA: 0x2019dc4 VA: 0x7594631dc4
	protected override Void DoDetach() { }
	// RVA: 0x2019e34 VA: 0x7594631e34
	private Void Update() { }
	// RVA: 0x201a0f0 VA: 0x75946320f0
	public Void .ctor() { }
	// RVA: 0x201a160 VA: 0x7594632160
	private Void <>xLuaBaseProxy_DoAttach(Unit P0, UIPluginTalent P1) { }
	// RVA: 0x201a168 VA: 0x7594632168
	private Void <>xLuaBaseProxy_DoDetach() { }
}
```