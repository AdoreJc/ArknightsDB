# DeepSeaRPSquadHomeTechTreePluginView

**Namespace:** `Torappu.UI.DeepSeaRP`


## Fields

- `Boolean m_canEdit`

- `Boolean m_isRetro`

- `String m_groupId`

- `String m_stageId`


## Methods

- `Void _TryTriggerAVG(List`1)`

- `Void EventOnEditTechTreeBtnClick()`

- `String _GetRetroGroupIdByStageId(String)`

- `TechData _TryGetPlayerData(String)`

- `Boolean <>xLuaBaseProxy_ShowSquadLeftArrow()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.DeepSeaRP
public class DeepSeaRPSquadHomeTechTreePluginView : SquadHomePluginView
{
	private List`1 _techItems; // 0x30
	private Boolean m_canEdit; // 0x38
	private Boolean m_isRetro; // 0x39
	private String m_groupId; // 0x40
	private String m_stageId; // 0x48
	private Dictionary`2 m_dicTechPlayerData; // 0x50
	private static DelegateBridge __Hotfix0_ShowSquadLeftArrow; // 0x0
	private static DelegateBridge __Hotfix0_Show; // 0x8
	private static DelegateBridge __Hotfix0__TryTriggerAVG; // 0x10
	private static DelegateBridge __Hotfix0_EventOnEditTechTreeBtnClick; // 0x18
	private static DelegateBridge __Hotfix0__GetRetroGroupIdByStageId; // 0x20
	private static DelegateBridge __Hotfix0__RefreshTechInfoList; // 0x28
	private static DelegateBridge __Hotfix0__TryGetPlayerData; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x29dfbb4 VA: 0x7594ff7bb4
	public override Boolean ShowSquadLeftArrow() { }
	// RVA: 0x29dfc18 VA: 0x7594ff7c18
	public override Void Show(PluginInputParams param) { }
	// RVA: 0x29e074c VA: 0x7594ff874c
	private Void _TryTriggerAVG(List`1 techInfos) { }
	// RVA: 0x29e08a0 VA: 0x7594ff88a0
	public Void EventOnEditTechTreeBtnClick() { }
	// RVA: 0x29dff34 VA: 0x7594ff7f34
	private String _GetRetroGroupIdByStageId(String stageId) { }
	// RVA: 0x29e002c VA: 0x7594ff802c
	private List`1 _RefreshTechInfoList(PluginInputParams param) { }
	// RVA: 0x29e09ec VA: 0x7594ff89ec
	private TechData _TryGetPlayerData(String techId) { }
	// RVA: 0x29e0b1c VA: 0x7594ff8b1c
	public Void .ctor() { }
	// RVA: 0x29e0be0 VA: 0x7594ff8be0
	private Boolean <>xLuaBaseProxy_ShowSquadLeftArrow() { }
}
```