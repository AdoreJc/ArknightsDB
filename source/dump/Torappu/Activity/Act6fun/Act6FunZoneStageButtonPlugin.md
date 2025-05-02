# Act6FunZoneStageButtonPlugin

**Namespace:** `Torappu.Activity.Act6fun`


## Fields

- `GameObject _objUnlockPart`

- `GameObject _objCompletePart`

- `Text _txtStageName`

- `GameObject _objLockPart`

- `UIAnimationLocation _selectAnim`

- `CanvasGroup _canvasSelectPart`

- `Act6FunZoneMapStageButtonAchieveItemView _achieveItemView`

- `Boolean m_hasInited`

- `SelectSwitchTween m_selectSwitchTween`


## Methods

- `Void EventOnLockItemClick()`

- `Void _InitIfNot()`

- `Act6FunZoneMapStageButtonPluginViewModel _TryGetButtonPluginViewModel(ActivityCustomZoneMapViewModel, StageViewModel)`

- `Void <>xLuaBaseProxy_Render(ActivityCustomZoneMapViewModel, StageViewModel, Boolean, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act6fun
public class Act6FunZoneStageButtonPlugin : ActivityCustomZoneBaseStageButtonPlugin
{
	private GameObject _objUnlockPart; // 0x18
	private GameObject _objCompletePart; // 0x20
	private Text _txtStageName; // 0x28
	private GameObject _objLockPart; // 0x30
	private UIAnimationLocation _selectAnim; // 0x38
	private CanvasGroup _canvasSelectPart; // 0x48
	private Act6FunZoneMapStageButtonAchieveItemView _achieveItemView; // 0x50
	private Boolean m_hasInited; // 0x58
	private SelectSwitchTween m_selectSwitchTween; // 0x60
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_EventOnLockItemClick; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0__TryGetButtonPluginViewModel; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x31b4cdc VA: 0x75957cccdc
	public override Void Render(ActivityCustomZoneMapViewModel zoneModel, StageViewModel stageViewModel, Boolean isSelected, Boolean isFastMode) { }
	// RVA: 0x31b5254 VA: 0x75957cd254
	public Void EventOnLockItemClick() { }
	// RVA: 0x31b4fe4 VA: 0x75957ccfe4
	private Void _InitIfNot() { }
	// RVA: 0x31b4e80 VA: 0x75957cce80
	private Act6FunZoneMapStageButtonPluginViewModel _TryGetButtonPluginViewModel(ActivityCustomZoneMapViewModel zoneModel, StageViewModel stageViewModel) { }
	// RVA: 0x31b5384 VA: 0x75957cd384
	public Void .ctor() { }
	// RVA: 0x31b53f4 VA: 0x75957cd3f4
	private Void <>xLuaBaseProxy_Render(ActivityCustomZoneMapViewModel P0, StageViewModel P1, Boolean P2, Boolean P3) { }
}
```