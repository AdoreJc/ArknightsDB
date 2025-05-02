# MhPartHpHudPlugin

**Namespace:** `Torappu.Battle.UI`


## Fields

- `UIFollowSlider _partHpSlider`

- `GameObject _rootObj`

- `Animator _animator`

- `String _triggerKey`

- `MhPartHpHudPluginTalent m_hudTalent`

- `Single m_currentPartHpRatio`

- `Int32 m_trigger`


## Methods

- `Boolean _CheckOwnerValidMode()`

- `Void Update()`

- `Void <>xLuaBaseProxy_DoAttach(Unit, UIPluginTalent)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class MhPartHpHudPlugin : UnitTalentUIPlugin
{
	private UIFollowSlider _partHpSlider; // 0x30
	private GameObject _rootObj; // 0x38
	private Animator _animator; // 0x40
	private String _triggerKey; // 0x48
	private MhPartHpHudPluginTalent m_hudTalent; // 0x50
	private Single m_currentPartHpRatio; // 0x58
	private Int32 m_trigger; // 0x5c
	private static DelegateBridge __Hotfix0_DoAttach; // 0x0
	private static DelegateBridge __Hotfix0__CheckOwnerValidMode; // 0x8
	private static DelegateBridge __Hotfix0_Update; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x201ac9c VA: 0x7594632c9c
	protected override Void DoAttach(Unit owner, UIPluginTalent uiTalent) { }
	// RVA: 0x201ae24 VA: 0x7594632e24
	private Boolean _CheckOwnerValidMode() { }
	// RVA: 0x201af18 VA: 0x7594632f18
	private Void Update() { }
	// RVA: 0x201b1bc VA: 0x75946331bc
	public Void .ctor() { }
	// RVA: 0x201b22c VA: 0x759463322c
	private Void <>xLuaBaseProxy_DoAttach(Unit P0, UIPluginTalent P1) { }
}
```