# BuildingCharCtrlRoomTitleView

**Namespace:** `Torappu.Building.UI`


## Fields

- `GameObject _panelDefault`

- `GameObject _panelNormal`

- `Image _imgRoomIcon`

- `String m_cachedSlotId`


## Methods

- `Void _RenderInVisitMode()`

- `Void _RenderNormalRoomTitle(BasicRoomInfoModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class BuildingCharCtrlRoomTitleView : AbstractBuildingUIRoomTitle`2
{
	private List`1 _extraRoomConfigs; // 0x38
	private GameObject _panelDefault; // 0x40
	private GameObject _panelNormal; // 0x48
	private Image _imgRoomIcon; // 0x50
	private String m_cachedSlotId; // 0x58
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x0
	private static DelegateBridge __Hotfix0__RenderInVisitMode; // 0x8
	private static DelegateBridge __Hotfix0__RenderNormalRoomTitle; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3d33600 VA: 0x759634b600
	public override Void OnValueChanged(CommonBasicRoomViewProperty property) { }
	// RVA: 0x3d337a8 VA: 0x759634b7a8
	private Void _RenderInVisitMode() { }
	// RVA: 0x3d33a5c VA: 0x759634ba5c
	private Void _RenderNormalRoomTitle(BasicRoomInfoModel basicInfo) { }
	// RVA: 0x3d340d8 VA: 0x759634c0d8
	public Void .ctor() { }
}
```