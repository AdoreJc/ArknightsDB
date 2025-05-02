# BuildingFloatManufactState

**Namespace:** `Torappu.Building.UI.Float`


## Fields

- `BuildingFloatManufactInfoView _manufactInfo`

- `FloatManufactViewProperty m_manufactProperty`


## Methods

- `Void EventOnManufactClick()`

- `Void _LoadData()`

- `Void <>xLuaBaseProxy_Start()`

- `Void <>xLuaBaseProxy_OnPlayerDataChanged(Object)`

- `Void <>xLuaBaseProxy_OnStateUpdated(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Float
public class BuildingFloatManufactState : BuildingFloatVaultInfoState
{
	private BuildingFloatManufactInfoView _manufactInfo; // 0xa0
	private FloatManufactViewProperty m_manufactProperty; // 0xa8
	private static DelegateBridge __Hotfix0_get_state; // 0x0
	private static DelegateBridge __Hotfix0_Start; // 0x8
	private static DelegateBridge __Hotfix0_OnPlayerDataChanged; // 0x10
	private static DelegateBridge __Hotfix0_OnStateUpdated; // 0x18
	private static DelegateBridge __Hotfix0_EventOnManufactClick; // 0x20
	private static DelegateBridge __Hotfix0__LoadData; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	protected override FloatState state { get; }

	// RVA: 0x3e1d840 VA: 0x7596435840
	protected override FloatState get_state() { }
	// RVA: 0x3e1d8a8 VA: 0x75964358a8
	protected override Void Start() { }
	// RVA: 0x3e1d980 VA: 0x7596435980
	protected override Void OnPlayerDataChanged(Object args) { }
	// RVA: 0x3e1dc50 VA: 0x7596435c50
	protected override Void OnStateUpdated(Boolean isActive) { }
	// RVA: 0x3e1dcf0 VA: 0x7596435cf0
	public Void EventOnManufactClick() { }
	// RVA: 0x3e1da0c VA: 0x7596435a0c
	private Void _LoadData() { }
	// RVA: 0x3e1de14 VA: 0x7596435e14
	public Void .ctor() { }
	// RVA: 0x3e1def0 VA: 0x7596435ef0
	private Void <>xLuaBaseProxy_Start() { }
	// RVA: 0x3e1def8 VA: 0x7596435ef8
	private Void <>xLuaBaseProxy_OnPlayerDataChanged(Object P0) { }
	// RVA: 0x3e1df00 VA: 0x7596435f00
	private Void <>xLuaBaseProxy_OnStateUpdated(Boolean P0) { }
}
```