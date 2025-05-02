# UIBattleSandboxTrapInfoStatusSubPanel

**Namespace:** `Torappu.Battle.UI.Sandbox`


## Fields

- `Text _trapResName`

- `GameObject _trapResPanel`

- `UIBattleSandboxResItem _trapResItem`

- `Sprite _buildingTrapIcon`

- `Sprite _resTrapIcon`

- `Sprite _NPCTrapIcon`

- `SandboxGameMode m_gameMode`


## Methods

- `Void <>xLuaBaseProxy_OnInit(UICharacterInfoPanel)`

- `Void <>xLuaBaseProxy_SetData(ObjectPtr`1, ModeType, Card)`

- `Void <>xLuaBaseProxy_UpdateData(ObjectPtr`1, ModeType, Card)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Sandbox
public class UIBattleSandboxTrapInfoStatusSubPanel : UICharacterInfoStatusSubPanel
{
	private Text _trapResName; // 0xb0
	private GameObject _trapResPanel; // 0xb8
	private UIBattleSandboxResItem _trapResItem; // 0xc0
	private Sprite _buildingTrapIcon; // 0xc8
	private Sprite _resTrapIcon; // 0xd0
	private Sprite _NPCTrapIcon; // 0xd8
	private SandboxGameMode m_gameMode; // 0xe0
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_SetData; // 0x8
	private static DelegateBridge __Hotfix0_UpdateData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x209db88 VA: 0x75946b5b88
	public override Void OnInit(UICharacterInfoPanel parent) { }
	// RVA: 0x209dcd8 VA: 0x75946b5cd8
	public override Void SetData(ObjectPtr`1 characterPtr, ModeType mode, Card card) { }
	// RVA: 0x209e100 VA: 0x75946b6100
	public override Void UpdateData(ObjectPtr`1 characterPtr, ModeType mode, Card card) { }
	// RVA: 0x209e2d0 VA: 0x75946b62d0
	public Void .ctor() { }
	// RVA: 0x209e340 VA: 0x75946b6340
	private Void <>xLuaBaseProxy_OnInit(UICharacterInfoPanel P0) { }
	// RVA: 0x209e348 VA: 0x75946b6348
	private Void <>xLuaBaseProxy_SetData(ObjectPtr`1 P0, ModeType P1, Card P2) { }
	// RVA: 0x209e350 VA: 0x75946b6350
	private Void <>xLuaBaseProxy_UpdateData(ObjectPtr`1 P0, ModeType P1, Card P2) { }
}
```