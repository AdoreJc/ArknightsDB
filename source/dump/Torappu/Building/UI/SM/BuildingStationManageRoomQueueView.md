# BuildingStationManageRoomQueueView

**Namespace:** `Torappu.Building.UI.SM`


## Fields

- `UIAnimationLocation _animSwitchQueue`

- `Boolean m_isInited`

- `CharAdapterForEditRoom m_charAdapter`

- `Tween m_switchQueueAnimTween`

- `IntHashSet prefCharsInstIdSet`


## Methods

- `Void _InitIfNot()`

- `Void Render(StationManageEditRoomQueueStructModel)`

- `Void _TryPlayQueueUpdateAnim(StationManageEditRoomQueueStructModel)`

- `Boolean _GetIsQueueChanged(StationCharStructModel[])`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.SM
public class BuildingStationManageRoomQueueView : BuildingStationManageQueueBaseView, IHotfixable
{
	private UIAnimationLocation _animSwitchQueue; // 0x40
	private Boolean m_isInited; // 0x50
	private CharAdapterForEditRoom m_charAdapter; // 0x58
	private Tween m_switchQueueAnimTween; // 0x60
	private IntHashSet prefCharsInstIdSet; // 0x68
	private static DelegateBridge __Hotfix0_get_charAdapter; // 0x0
	private static DelegateBridge __Hotfix0_InitAdapter; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0__TryPlayQueueUpdateAnim; // 0x20
	private static DelegateBridge __Hotfix0__GetIsQueueChanged; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	protected override CharAdapter charAdapter { get; }

	// RVA: 0x3db2adc VA: 0x75963caadc
	protected override CharAdapter get_charAdapter() { }
	// RVA: 0x3db2ba4 VA: 0x75963caba4
	protected override Void InitAdapter() { }
	// RVA: 0x3db2cd4 VA: 0x75963cacd4
	private Void _InitIfNot() { }
	// RVA: 0x3db2d7c VA: 0x75963cad7c
	public Void Render(StationManageEditRoomQueueStructModel queueStructModel) { }
	// RVA: 0x3db2e74 VA: 0x75963cae74
	private Void _TryPlayQueueUpdateAnim(StationManageEditRoomQueueStructModel queueStructModel) { }
	// RVA: 0x3db2fd4 VA: 0x75963cafd4
	private Boolean _GetIsQueueChanged(StationCharStructModel[] newQueue) { }
	// RVA: 0x3db3274 VA: 0x75963cb274
	public Void .ctor() { }
}
```