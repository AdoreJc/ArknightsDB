# MhWeaknessHudPlugin

**Namespace:** `Torappu.Battle.UI`


## Fields

- `GameObject _rootObj`

- `GameObject _rotationObj`

- `Animator _animator`

- `String _triggerKey`

- `MhWeaknessHudPluginTalent m_hudTalent`

- `Int32 m_trigger`


## Methods

- `Void Update()`

- `Boolean _CheckOwnerValidMode()`

- `Void <>xLuaBaseProxy_DoAttach(Unit, UIPluginTalent)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class MhWeaknessHudPlugin : UnitTalentUIPlugin
{
	private GameObject _rootObj; // 0x30
	private GameObject _rotationObj; // 0x38
	private Animator _animator; // 0x40
	private String _triggerKey; // 0x48
	private MhWeaknessHudPluginTalent m_hudTalent; // 0x50
	private Int32 m_trigger; // 0x58
	private static DelegateBridge __Hotfix0_DoAttach; // 0x0
	private static DelegateBridge __Hotfix0_Update; // 0x8
	private static DelegateBridge __Hotfix0__CheckOwnerValidMode; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x201b234 VA: 0x7594633234
	protected override Void DoAttach(Unit owner, UIPluginTalent uiTalent) { }
	// RVA: 0x201b368 VA: 0x7594633368
	private Void Update() { }
	// RVA: 0x201b568 VA: 0x7594633568
	private Boolean _CheckOwnerValidMode() { }
	// RVA: 0x201b65c VA: 0x759463365c
	public Void .ctor() { }
	// RVA: 0x201b6cc VA: 0x75946336cc
	private Void <>xLuaBaseProxy_DoAttach(Unit P0, UIPluginTalent P1) { }
}
```