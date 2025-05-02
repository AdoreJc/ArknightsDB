# UIBattleSandboxCharacterInfoStatusSubPanel

**Namespace:** `Torappu.Battle.UI.Sandbox`


## Fields

- `UICharacterInfoSubPanel _trapSubPanelPrefab`

- `Text _packedResAmount`

- `Text _maxPackedResAmount`

- `Color _noResItemColor`

- `Color _haveResItemColor`

- `UIBattleSandboxResItem _sandboxResItemPrefab`

- `GameObject _sandboxNoResItem`

- `Transform _sandboxResItemTransform`

- `SandboxGameMode m_gameMode`

- `UICharacterInfoSubPanel m_trapStatusSubPanel`


## Methods

- `Void _SetPackedResAmount(Int32)`

- `Void _SetTrapData(ObjectPtr`1, ModeType, Card)`

- `Void _UpdateTrapData(ObjectPtr`1, ModeType, Card)`

- `Void _ActiveSelf(Boolean)`

- `Void <>xLuaBaseProxy_OnInit(UICharacterInfoPanel)`

- `Void <>xLuaBaseProxy_SetData(ObjectPtr`1, ModeType, Card)`

- `Void <>xLuaBaseProxy_UpdateData(ObjectPtr`1, ModeType, Card)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Sandbox
public class UIBattleSandboxCharacterInfoStatusSubPanel : UICharacterInfoStatusSubPanel
{
	private UICharacterInfoSubPanel _trapSubPanelPrefab; // 0xb0
	private Text _packedResAmount; // 0xb8
	private Text _maxPackedResAmount; // 0xc0
	private Color _noResItemColor; // 0xc8
	private Color _haveResItemColor; // 0xd8
	private UIBattleSandboxResItem _sandboxResItemPrefab; // 0xe8
	private GameObject _sandboxNoResItem; // 0xf0
	private Transform _sandboxResItemTransform; // 0xf8
	private Int32[] m_resInPack; // 0x100
	private SandboxGameMode m_gameMode; // 0x108
	private List`1 m_resItemList; // 0x110
	private UICharacterInfoSubPanel m_trapStatusSubPanel; // 0x118
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_SetData; // 0x8
	private static DelegateBridge __Hotfix0__SetPackedResAmount; // 0x10
	private static DelegateBridge __Hotfix0_UpdateData; // 0x18
	private static DelegateBridge __Hotfix0__SetTrapData; // 0x20
	private static DelegateBridge __Hotfix0__UpdateTrapData; // 0x28
	private static DelegateBridge __Hotfix0__ActiveSelf; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2092414 VA: 0x75946aa414
	public override Void OnInit(UICharacterInfoPanel parent) { }
	// RVA: 0x2092a94 VA: 0x75946aaa94
	public override Void SetData(ObjectPtr`1 characterPtr, ModeType mode, Card card) { }
	// RVA: 0x2093148 VA: 0x75946ab148
	private Void _SetPackedResAmount(Int32 amount) { }
	// RVA: 0x209329c VA: 0x75946ab29c
	public override Void UpdateData(ObjectPtr`1 characterPtr, ModeType mode, Card card) { }
	// RVA: 0x2093088 VA: 0x75946ab088
	private Void _SetTrapData(ObjectPtr`1 characterPtr, ModeType mode, Card card) { }
	// RVA: 0x20936e4 VA: 0x75946ab6e4
	private Void _UpdateTrapData(ObjectPtr`1 characterPtr, ModeType mode, Card card) { }
	// RVA: 0x2092f8c VA: 0x75946aaf8c
	private Void _ActiveSelf(Boolean setActive) { }
	// RVA: 0x20937a4 VA: 0x75946ab7a4
	public Void .ctor() { }
	// RVA: 0x2093868 VA: 0x75946ab868
	private Void <>xLuaBaseProxy_OnInit(UICharacterInfoPanel P0) { }
	// RVA: 0x2093870 VA: 0x75946ab870
	private Void <>xLuaBaseProxy_SetData(ObjectPtr`1 P0, ModeType P1, Card P2) { }
	// RVA: 0x2093878 VA: 0x75946ab878
	private Void <>xLuaBaseProxy_UpdateData(ObjectPtr`1 P0, ModeType P1, Card P2) { }
}
```