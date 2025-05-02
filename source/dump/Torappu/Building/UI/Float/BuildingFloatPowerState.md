# BuildingFloatPowerState

**Namespace:** `Torappu.Building.UI.Float`


## Fields

- `Text _powerText`

- `Text _accelLaborText`

- `SimpleLayoutContent _laborAccelLayout`

- `Color _bkgColorLaborAccel`

- `Color _textColorLaborAccel`

- `PowerRoomViewModel m_viewModel`

- `ListAdapter m_laborAccelAdapter`


## Methods

- `Void _UpdateBuffedValues(Single, Single, SimpleLayoutContent, ref)`

- `Void <>xLuaBaseProxy_OnStateUpdated(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Float
public class BuildingFloatPowerState : BuildingFloatVaultInfoState
{
	private Text _powerText; // 0xa0
	private Text _accelLaborText; // 0xa8
	private SimpleLayoutContent _laborAccelLayout; // 0xb0
	private Color _bkgColorLaborAccel; // 0xb8
	private Color _textColorLaborAccel; // 0xc8
	private PowerRoomViewModel m_viewModel; // 0xd8
	private ListAdapter m_laborAccelAdapter; // 0xe0
	private static DelegateBridge __Hotfix0_get_state; // 0x0
	private static DelegateBridge __Hotfix0_OnStateUpdated; // 0x8
	private static DelegateBridge __Hotfix0__UpdateBuffedValues; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	protected override FloatState state { get; }

	// RVA: 0x3e1f924 VA: 0x7596437924
	protected override FloatState get_state() { }
	// RVA: 0x3e1f98c VA: 0x759643798c
	protected override Void OnStateUpdated(Boolean isActive) { }
	// RVA: 0x3e1fb54 VA: 0x7596437b54
	private Void _UpdateBuffedValues(Single baseVal, Single buffVal, SimpleLayoutContent layout, ref ListAdapter refAdapter) { }
	// RVA: 0x3e1fde4 VA: 0x7596437de4
	public Void .ctor() { }
	// RVA: 0x3e1fec0 VA: 0x7596437ec0
	private Void <>xLuaBaseProxy_OnStateUpdated(Boolean P0) { }
}
```