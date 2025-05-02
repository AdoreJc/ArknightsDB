# UIBattleSandboxConstructCharacterMenuPanel

**Namespace:** `Torappu.Battle.UI.Sandbox`


## Fields

- `Follower2D _follower`

- `Transform _repairRoot`

- `UIBattleSandboxConstructMenuItemList _repairList`

- `Transform _upgradeRoot`

- `UIBattleSandboxConstructMenuItemList _upgradeList`

- `Transform _withdrawRoot`

- `UIBattleSandboxConstructMenuItemList _withdrawList`

- `String _repairEffectKey`

- `String _repairEffectCommonKey`

- `String _upgradeEffect`

- `String _upgradeCommonEffect`

- `BattleSandboxConstructItemListModel m_repairModel`

- `BattleSandboxConstructItemListModel m_upgradeModel`

- `BattleSandboxConstructItemListModel m_withdrawModel`

- `Boolean m_inited`

- `Boolean m_operationExecuted`

- `ConstructLandManager m_manager`

- `OnConstructMenuHide onHide`

- `String m_buildingOrBasePortTrapId`

- `Boolean m_isOpen`


## Properties

- `SandboxV2Data dataTable`

- `String topicId`

- `ConstructLandManager manager`


## Methods

- `SandboxV2Data get_dataTable()`

- `String get_topicId()`

- `ConstructLandManager get_manager()`

- `Void OnUpgradeButtonClicked()`

- `Void OnWithdrawButtonClicked()`

- `Void OnRepairButtonClicked()`

- `Void Show(Character)`

- `Void Hide()`

- `Void _InitIfNot()`

- `Void _SetData(Character)`

- `Void _DoUpdateRangeToShow(Character)`

- `Void _DoRenderWithdraw(Character, String)`

- `Void _DoRenderRepair(Character)`

- `Void _DoRenderUpgrade(Character, String)`

- `Boolean _IsResEnoughToUpgrade(BattleSandboxConstructItemListModel, String)`

- `Void _CreateEffectToSelectedCharacter(String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Sandbox
public class UIBattleSandboxConstructCharacterMenuPanel : MonoBehaviour, IUICharacterMenuPanel, IHotfixable
{
	private Follower2D _follower; // 0x18
	private Transform _repairRoot; // 0x20
	private UIBattleSandboxConstructMenuItemList _repairList; // 0x28
	private Transform _upgradeRoot; // 0x30
	private UIBattleSandboxConstructMenuItemList _upgradeList; // 0x38
	private Transform _withdrawRoot; // 0x40
	private UIBattleSandboxConstructMenuItemList _withdrawList; // 0x48
	private String _repairEffectKey; // 0x50
	private String _repairEffectCommonKey; // 0x58
	private String _upgradeEffect; // 0x60
	private String _upgradeCommonEffect; // 0x68
	private BattleSandboxConstructItemListModel m_repairModel; // 0x70
	private BattleSandboxConstructItemListModel m_upgradeModel; // 0x78
	private BattleSandboxConstructItemListModel m_withdrawModel; // 0x80
	private ListDict`2 m_upgradeCostCache; // 0x88
	private Boolean m_inited; // 0x90
	private Boolean m_operationExecuted; // 0x91
	private ConstructLandManager m_manager; // 0x98
	public OnConstructMenuHide onHide; // 0xa0
	public Action`1 onCharacterClicked; // 0xa8
	private ObjectPtr`1 m_character; // 0xb0
	private String m_buildingOrBasePortTrapId; // 0xc0
	private Boolean m_isOpen; // 0xc8
	private static DelegateBridge __Hotfix0_get_dataTable; // 0x0
	private static DelegateBridge __Hotfix0_get_topicId; // 0x8
	private static DelegateBridge __Hotfix0_get_manager; // 0x10
	private static DelegateBridge __Hotfix0_OnUpgradeButtonClicked; // 0x18
	private static DelegateBridge __Hotfix0_OnWithdrawButtonClicked; // 0x20
	private static DelegateBridge __Hotfix0_OnRepairButtonClicked; // 0x28
	private static DelegateBridge __Hotfix0_Show; // 0x30
	private static DelegateBridge __Hotfix0_Hide; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x40
	private static DelegateBridge __Hotfix0__SetData; // 0x48
	private static DelegateBridge __Hotfix0__DoUpdateRangeToShow; // 0x50
	private static DelegateBridge __Hotfix0__DoRenderWithdraw; // 0x58
	private static DelegateBridge __Hotfix0__DoRenderRepair; // 0x60
	private static DelegateBridge __Hotfix0__DoRenderUpgrade; // 0x68
	private static DelegateBridge __Hotfix0__IsResEnoughToUpgrade; // 0x70
	private static DelegateBridge __Hotfix0__CreateEffectToSelectedCharacter; // 0x78
	private static DelegateBridge _c__Hotfix0_ctor; // 0x80

	private SandboxV2Data dataTable { get; }
	private String topicId { get; }
	private ConstructLandManager manager { get; }

	// RVA: 0x209812c VA: 0x75946b012c
	private SandboxV2Data get_dataTable() { }
	// RVA: 0x20981c4 VA: 0x75946b01c4
	private String get_topicId() { }
	// RVA: 0x2098244 VA: 0x75946b0244
	private ConstructLandManager get_manager() { }
	// RVA: 0x2098308 VA: 0x75946b0308
	public Void OnUpgradeButtonClicked() { }
	// RVA: 0x2098818 VA: 0x75946b0818
	public Void OnWithdrawButtonClicked() { }
	// RVA: 0x20989e8 VA: 0x75946b09e8
	public Void OnRepairButtonClicked() { }
	// RVA: 0x2098bf4 VA: 0x75946b0bf4
	public Void Show(Character character) { }
	// RVA: 0x2099ad8 VA: 0x75946b1ad8
	public Void Hide() { }
	// RVA: 0x2098dac VA: 0x75946b0dac
	private Void _InitIfNot() { }
	// RVA: 0x2098e54 VA: 0x75946b0e54
	private Void _SetData(Character character) { }
	// RVA: 0x2098ff0 VA: 0x75946b0ff0
	private Void _DoUpdateRangeToShow(Character character) { }
	// RVA: 0x2099380 VA: 0x75946b1380
	private Void _DoRenderWithdraw(Character character, String buildingId) { }
	// RVA: 0x20990e8 VA: 0x75946b10e8
	private Void _DoRenderRepair(Character character) { }
	// RVA: 0x2099700 VA: 0x75946b1700
	private Void _DoRenderUpgrade(Character character, String buildingId) { }
	// RVA: 0x2099bcc VA: 0x75946b1bcc
	private Boolean _IsResEnoughToUpgrade(BattleSandboxConstructItemListModel model, String buildingId) { }
	// RVA: 0x20985d8 VA: 0x75946b05d8
	private Void _CreateEffectToSelectedCharacter(String commonKey, String giantOnlyKey) { }
	// RVA: 0x2099e1c VA: 0x75946b1e1c
	public Void .ctor() { }
}
```