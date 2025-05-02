# BuildingCharSelectMaskPlugin

**Namespace:** `Torappu.Building.UI`


## Fields

- `PanelWorking _panelWorking`

- `PanelExclusiveInfo _panelExcluInfo`

- `PanelDormLock _panelDormLock`

- `RectTransform _panelInvalid`

- `CharSelectStateBean m_stateBean`

- `IBuildingCharSelectContext m_context`

- `CharacterCardViewModel m_cacheModel`


## Properties

- `BuildingCharSelectRoomConfig roomConfig`


## Methods

- `BuildingCharSelectRoomConfig get_roomConfig()`

- `Void _RenderWorking()`

- `Void _RenderDormLock()`

- `Void _RenderExclusiveInfo()`

- `Void _RenderInvalid()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class BuildingCharSelectMaskPlugin : CharSelectCardMaskPlugin
{
	private PanelWorking _panelWorking; // 0x18
	private PanelExclusiveInfo _panelExcluInfo; // 0x20
	private PanelDormLock _panelDormLock; // 0x28
	private RectTransform _panelInvalid; // 0x30
	private CharSelectStateBean m_stateBean; // 0x38
	private IBuildingCharSelectContext m_context; // 0x40
	private CharacterCardViewModel m_cacheModel; // 0x48
	private static DelegateBridge __Hotfix0_get_roomConfig; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__RenderWorking; // 0x18
	private static DelegateBridge __Hotfix0__RenderDormLock; // 0x20
	private static DelegateBridge __Hotfix0__RenderExclusiveInfo; // 0x28
	private static DelegateBridge __Hotfix0__RenderInvalid; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public BuildingCharSelectRoomConfig roomConfig { get; }

	// RVA: 0x3d346e0 VA: 0x759634c6e0
	public BuildingCharSelectRoomConfig get_roomConfig() { }
	// RVA: 0x3d34778 VA: 0x759634c778
	public override Void Init(CharSelectCardView cardView, CharSelectStateBean stateBean, Object context) { }
	// RVA: 0x3d34854 VA: 0x759634c854
	public override Void Render(CharacterCardViewModel cardModel) { }
	// RVA: 0x3d348f8 VA: 0x759634c8f8
	private Void _RenderWorking() { }
	// RVA: 0x3d34c70 VA: 0x759634cc70
	private Void _RenderDormLock() { }
	// RVA: 0x3d34f50 VA: 0x759634cf50
	private Void _RenderExclusiveInfo() { }
	// RVA: 0x3d35bdc VA: 0x759634dbdc
	private Void _RenderInvalid() { }
	// RVA: 0x3d35d40 VA: 0x759634dd40
	public Void .ctor() { }
}
```