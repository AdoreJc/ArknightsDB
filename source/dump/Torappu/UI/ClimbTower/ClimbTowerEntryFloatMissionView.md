# ClimbTowerEntryFloatMissionView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `SimpleLayoutContent _content`

- `GameObject _panelTrackPoint`

- `Boolean m_hasInited`

- `Int32 m_missionSumCount`

- `Int32 m_missionCompleteCount`

- `Adapter m_adapter`

- `UIPage <page>k__BackingField`

- `Action <onClicked>k__BackingField`


## Properties

- `UIPage page`

- `Action onClicked`


## Methods

- `UIPage get_page()`

- `Void set_page(UIPage)`

- `Action get_onClicked()`

- `Void set_onClicked(Action)`

- `Void Render(ClimbTowerEntryFloatPanelViewModel)`

- `Void OnClick()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerEntryFloatMissionView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _content; // 0x18
	private GameObject _panelTrackPoint; // 0x20
	private Boolean m_hasInited; // 0x28
	private Int32 m_missionSumCount; // 0x2c
	private Int32 m_missionCompleteCount; // 0x30
	private Adapter m_adapter; // 0x38
	private UIPage <page>k__BackingField; // 0x40
	private Action <onClicked>k__BackingField; // 0x48
	private static DelegateBridge __Hotfix0_get_page; // 0x0
	private static DelegateBridge __Hotfix0_set_page; // 0x8
	private static DelegateBridge __Hotfix0_get_onClicked; // 0x10
	private static DelegateBridge __Hotfix0_set_onClicked; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0_OnClick; // 0x28
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private UIPage page { get; set; }
	private Action onClicked { get; set; }

	// RVA: 0x2c63b40 VA: 0x759527bb40
	private UIPage get_page() { }
	// RVA: 0x2c63ba8 VA: 0x759527bba8
	public Void set_page(UIPage value) { }
	// RVA: 0x2c63c2c VA: 0x759527bc2c
	private Action get_onClicked() { }
	// RVA: 0x2c63c94 VA: 0x759527bc94
	public Void set_onClicked(Action value) { }
	// RVA: 0x2c63d18 VA: 0x759527bd18
	public Void Render(ClimbTowerEntryFloatPanelViewModel viewModel) { }
	// RVA: 0x2c63e98 VA: 0x759527be98
	public Void OnClick() { }
	// RVA: 0x2c63dc8 VA: 0x759527bdc8
	private Void _InitIfNot() { }
	// RVA: 0x2c63fc8 VA: 0x759527bfc8
	public Void .ctor() { }
}
```