# BuildingFloatVaultControlState

**Namespace:** `Torappu.Building.UI.Float`


## Fields

- `Text _textMpCost`

- `Text _textMpReduce`

- `SimpleLayoutContent _mpCostLayout`

- `SimpleLayoutContent _mpReduceLayout`

- `GameObject _assistTrackpoint`

- `ListAdapter m_mpCostAdapter`

- `ListAdapter m_mpReduceAdapter`

- `ControlRoomViewModel m_viewModel`

- `String m_colorCode`


## Methods

- `Void _UpdateMpBuff(Int64, SimpleLayoutContent, ref, Color, Color)`

- `Void EventOnBuildingAssistClicked()`

- `Void <>xLuaBaseProxy_OnStateUpdated(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Float
public class BuildingFloatVaultControlState : BuildingFloatVaultInfoState
{
	private Text _textMpCost; // 0xa0
	private Text _textMpReduce; // 0xa8
	private SimpleLayoutContent _mpCostLayout; // 0xb0
	private SimpleLayoutContent _mpReduceLayout; // 0xb8
	private GameObject _assistTrackpoint; // 0xc0
	private ListAdapter m_mpCostAdapter; // 0xc8
	private ListAdapter m_mpReduceAdapter; // 0xd0
	private ControlRoomViewModel m_viewModel; // 0xd8
	private String m_colorCode; // 0xe0
	private static DelegateBridge __Hotfix0_get_state; // 0x0
	private static DelegateBridge __Hotfix0_OnStateUpdated; // 0x8
	private static DelegateBridge __Hotfix0__UpdateMpBuff; // 0x10
	private static DelegateBridge __Hotfix0_EventOnBuildingAssistClicked; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	protected override FloatState state { get; }

	// RVA: 0x3e258d4 VA: 0x759643d8d4
	protected override FloatState get_state() { }
	// RVA: 0x3e2593c VA: 0x759643d93c
	protected override Void OnStateUpdated(Boolean isActive) { }
	// RVA: 0x3e25bdc VA: 0x759643dbdc
	private Void _UpdateMpBuff(Int64 buffVal, SimpleLayoutContent layout, ref ListAdapter refAdapter, Color bkgColor, Color textColor) { }
	// RVA: 0x3e25e40 VA: 0x759643de40
	public Void EventOnBuildingAssistClicked() { }
	// RVA: 0x3e25ec0 VA: 0x759643dec0
	public Void .ctor() { }
	// RVA: 0x3e25f98 VA: 0x759643df98
	private Void <>xLuaBaseProxy_OnStateUpdated(Boolean P0) { }
}
```