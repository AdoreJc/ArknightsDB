# Act25sideSquadHomePluginView

**Namespace:** `Torappu.Activity.Act25side.UI`


## Fields

- `UIAtlasObject _atlasObject`

- `Boolean m_isRetro`

- `String m_groupId`

- `String m_stageId`

- `StageData m_stageData`

- `Boolean m_showStatus`

- `Boolean m_canEdit`


## Methods

- `Void _Render(Dictionary`2)`

- `Void _TryUpdateLeftArrowStatus(SquadGroupViewModel)`

- `Void OnShowDetailClicked()`

- `Boolean <>xLuaBaseProxy_ShowSquadLeftArrow()`

- `Void <>xLuaBaseProxy_OnSquadGroupChanged(SquadGroupViewModel)`

- `SquadHomeStartBattleServicePluginBase <>xLuaBaseProxy_CreateStartBattlePlugin()`

- `SquadHomeFinishBattleServicePluginBase <>xLuaBaseProxy_CreateFinishBattlePlugin()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side.UI
public class Act25sideSquadHomePluginView : SquadHomePluginView
{
	private SlotItem[] _slotItems; // 0x30
	private UIAtlasObject _atlasObject; // 0x38
	private String[] _techTypeConfigs; // 0x40
	private String[] _techRarityBkgConfigs; // 0x48
	private Boolean m_isRetro; // 0x50
	private String m_groupId; // 0x58
	private String m_stageId; // 0x60
	private StageData m_stageData; // 0x68
	private Boolean m_showStatus; // 0x70
	private Boolean m_canEdit; // 0x71
	private static DelegateBridge __Hotfix0_ShowSquadLeftArrow; // 0x0
	private static DelegateBridge __Hotfix0_OnSquadGroupChanged; // 0x8
	private static DelegateBridge __Hotfix0_Show; // 0x10
	private static DelegateBridge __Hotfix0__Render; // 0x18
	private static DelegateBridge __Hotfix0__TryUpdateLeftArrowStatus; // 0x20
	private static DelegateBridge __Hotfix0_OnShowDetailClicked; // 0x28
	private static DelegateBridge __Hotfix0_CreateStartBattlePlugin; // 0x30
	private static DelegateBridge __Hotfix0_CreateFinishBattlePlugin; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x328a69c VA: 0x75958a269c
	public override Boolean ShowSquadLeftArrow() { }
	// RVA: 0x328a700 VA: 0x75958a2700
	protected override Void OnSquadGroupChanged(SquadGroupViewModel groupModel) { }
	// RVA: 0x328a880 VA: 0x75958a2880
	public override Void Show(PluginInputParams param) { }
	// RVA: 0x328ad78 VA: 0x75958a2d78
	private Void _Render(Dictionary`2 slotData) { }
	// RVA: 0x328a79c VA: 0x75958a279c
	private Void _TryUpdateLeftArrowStatus(SquadGroupViewModel squadGroupModel) { }
	// RVA: 0x328b0c4 VA: 0x75958a30c4
	public Void OnShowDetailClicked() { }
	// RVA: 0x328b204 VA: 0x75958a3204
	public override SquadHomeStartBattleServicePluginBase CreateStartBattlePlugin() { }
	// RVA: 0x328b29c VA: 0x75958a329c
	public override SquadHomeFinishBattleServicePluginBase CreateFinishBattlePlugin() { }
	// RVA: 0x328b334 VA: 0x75958a3334
	public Void .ctor() { }
	// RVA: 0x328b3a4 VA: 0x75958a33a4
	private Boolean <>xLuaBaseProxy_ShowSquadLeftArrow() { }
	// RVA: 0x328b3ac VA: 0x75958a33ac
	private Void <>xLuaBaseProxy_OnSquadGroupChanged(SquadGroupViewModel P0) { }
	// RVA: 0x328b3b4 VA: 0x75958a33b4
	private SquadHomeStartBattleServicePluginBase <>xLuaBaseProxy_CreateStartBattlePlugin() { }
	// RVA: 0x328b3bc VA: 0x75958a33bc
	private SquadHomeFinishBattleServicePluginBase <>xLuaBaseProxy_CreateFinishBattlePlugin() { }
}
```