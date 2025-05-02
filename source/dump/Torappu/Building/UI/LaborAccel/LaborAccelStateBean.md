# LaborAccelStateBean

**Namespace:** `Torappu.Building.UI.LaborAccel`


## Fields

- `Input m_input`

- `CountDownTask m_remainTimeCountDown`

- `BuildingLaborViewModel m_laborModel`

- `StringProperty m_remainTimeProp`

- `StringProperty m_curLaborProp`

- `StringProperty m_wasteTimeAlert`

- `AccelResultProperty m_accelResultProp`

- `Int32 m_accelCount`

- `Boolean m_isShowingWasteTimeAlert`

- `Action eventOnCountInvalid`

- `Int64 <costLabor>k__BackingField`

- `String <accelTimeText>k__BackingField`

- `Boolean <isMaxReached>k__BackingField`

- `Boolean <isMinReached>k__BackingField`

- `IPlugin <statePlugin>k__BackingField`


## Properties

- `Int32 accelCount`

- `Int64 costLabor`

- `Int32 accelTime`

- `String accelTimeText`

- `String descTitle`

- `Boolean isMaxReached`

- `Boolean isMinReached`

- `StringProperty remainTimeProp`

- `StringProperty curLaborProp`

- `StringProperty wasteTimeProp`

- `AccelResultProperty accelResultProp`

- `IPlugin statePlugin`


## Methods

- `Int32 get_accelCount()`

- `Void set_accelCount(Int32)`

- `Int64 get_costLabor()`

- `Void set_costLabor(Int64)`

- `Int32 get_accelTime()`

- `String get_accelTimeText()`

- `Void set_accelTimeText(String)`

- `String get_descTitle()`

- `Boolean get_isMaxReached()`

- `Void set_isMaxReached(Boolean)`

- `Boolean get_isMinReached()`

- `Void set_isMinReached(Boolean)`

- `StringProperty get_remainTimeProp()`

- `StringProperty get_curLaborProp()`

- `StringProperty get_wasteTimeProp()`

- `AccelResultProperty get_accelResultProp()`

- `Void Tick()`

- `Void SetInput(Input)`

- `IPlugin get_statePlugin()`

- `Void set_statePlugin(IPlugin)`

- `Void ClearInput()`

- `Void UpdateData()`

- `Void _OnCurLaborChanged(BuildingLaborViewModel)`

- `Void _OnRemainTimeChanged(TickValue)`

- `RemainTimeContext _CalcRemainTime()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.LaborAccel
public class LaborAccelStateBean : IStateBean, IHotfixable
{
	private const String TIME_FORMAT; // 0x0
	private Input m_input; // 0x10
	private CountDownTask m_remainTimeCountDown; // 0x48
	private BuildingLaborViewModel m_laborModel; // 0x50
	private StringProperty m_remainTimeProp; // 0x58
	private StringProperty m_curLaborProp; // 0x60
	private StringProperty m_wasteTimeAlert; // 0x68
	private AccelResultProperty m_accelResultProp; // 0x70
	private Int32 m_accelCount; // 0x78
	private Boolean m_isShowingWasteTimeAlert; // 0x7c
	public Action eventOnCountInvalid; // 0x80
	private Int64 <costLabor>k__BackingField; // 0x88
	private String <accelTimeText>k__BackingField; // 0x90
	private Boolean <isMaxReached>k__BackingField; // 0x98
	private Boolean <isMinReached>k__BackingField; // 0x99
	private IPlugin <statePlugin>k__BackingField; // 0xa0
	private static DelegateBridge __Hotfix0_get_accelCount; // 0x0
	private static DelegateBridge __Hotfix0_set_accelCount; // 0x8
	private static DelegateBridge __Hotfix0_get_costLabor; // 0x10
	private static DelegateBridge __Hotfix0_set_costLabor; // 0x18
	private static DelegateBridge __Hotfix0_get_accelTime; // 0x20
	private static DelegateBridge __Hotfix0_get_accelTimeText; // 0x28
	private static DelegateBridge __Hotfix0_set_accelTimeText; // 0x30
	private static DelegateBridge __Hotfix0_get_descTitle; // 0x38
	private static DelegateBridge __Hotfix0_get_isMaxReached; // 0x40
	private static DelegateBridge __Hotfix0_set_isMaxReached; // 0x48
	private static DelegateBridge __Hotfix0_get_isMinReached; // 0x50
	private static DelegateBridge __Hotfix0_set_isMinReached; // 0x58
	private static DelegateBridge __Hotfix0_get_remainTimeProp; // 0x60
	private static DelegateBridge __Hotfix0_get_curLaborProp; // 0x68
	private static DelegateBridge __Hotfix0_get_wasteTimeProp; // 0x70
	private static DelegateBridge __Hotfix0_get_accelResultProp; // 0x78
	private static DelegateBridge __Hotfix0_Tick; // 0x80
	private static DelegateBridge __Hotfix0_SetInput; // 0x88
	private static DelegateBridge __Hotfix0_get_statePlugin; // 0x90
	private static DelegateBridge __Hotfix0_set_statePlugin; // 0x98
	private static DelegateBridge __Hotfix0_ClearInput; // 0xa0
	private static DelegateBridge __Hotfix0_UpdateData; // 0xa8
	private static DelegateBridge __Hotfix0__OnCurLaborChanged; // 0xb0
	private static DelegateBridge __Hotfix0__OnRemainTimeChanged; // 0xb8
	private static DelegateBridge __Hotfix0__CalcRemainTime; // 0xc0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xc8

	public Int32 accelCount { get; set; }
	public Int64 costLabor { get; set; }
	public Int32 accelTime { get; }
	public String accelTimeText { get; set; }
	public String descTitle { get; }
	public Boolean isMaxReached { get; set; }
	public Boolean isMinReached { get; set; }
	public StringProperty remainTimeProp { get; }
	public StringProperty curLaborProp { get; }
	public StringProperty wasteTimeProp { get; }
	public AccelResultProperty accelResultProp { get; }
	public IPlugin statePlugin { get; set; }

	// RVA: 0x3e10808 VA: 0x7596428808
	public Int32 get_accelCount() { }
	// RVA: 0x3e10428 VA: 0x7596428428
	public Void set_accelCount(Int32 value) { }
	// RVA: 0x3e10180 VA: 0x7596428180
	public Int64 get_costLabor() { }
	// RVA: 0x3e10d08 VA: 0x7596428d08
	private Void set_costLabor(Int64 value) { }
	// RVA: 0x3e10d84 VA: 0x7596428d84
	public Int32 get_accelTime() { }
	// RVA: 0x3e10118 VA: 0x7596428118
	public String get_accelTimeText() { }
	// RVA: 0x3e10df4 VA: 0x7596428df4
	private Void set_accelTimeText(String value) { }
	// RVA: 0x3e0fe20 VA: 0x7596427e20
	public String get_descTitle() { }
	// RVA: 0x3e101e8 VA: 0x75964281e8
	public Boolean get_isMaxReached() { }
	// RVA: 0x3e10e78 VA: 0x7596428e78
	private Void set_isMaxReached(Boolean value) { }
	// RVA: 0x3e10250 VA: 0x7596428250
	public Boolean get_isMinReached() { }
	// RVA: 0x3e10ef8 VA: 0x7596428ef8
	private Void set_isMinReached(Boolean value) { }
	// RVA: 0x3e0f53c VA: 0x759642753c
	public StringProperty get_remainTimeProp() { }
	// RVA: 0x3e0f4d4 VA: 0x75964274d4
	public StringProperty get_curLaborProp() { }
	// RVA: 0x3e0f5a4 VA: 0x75964275a4
	public StringProperty get_wasteTimeProp() { }
	// RVA: 0x3e0f60c VA: 0x759642760c
	public AccelResultProperty get_accelResultProp() { }
	// RVA: 0x3e10328 VA: 0x7596428328
	public Void Tick() { }
	// RVA: 0x3e10f78 VA: 0x7596428f78
	public Void SetInput(Input input) { }
	// RVA: 0x3e106a4 VA: 0x75964286a4
	public IPlugin get_statePlugin() { }
	// RVA: 0x3e11164 VA: 0x7596429164
	private Void set_statePlugin(IPlugin value) { }
	// RVA: 0x3e1000c VA: 0x759642800c
	public Void ClearInput() { }
	// RVA: 0x3e0f674 VA: 0x7596427674
	public Void UpdateData() { }
	// RVA: 0x3e111e8 VA: 0x75964291e8
	private Void _OnCurLaborChanged(BuildingLaborViewModel laborModel) { }
	// RVA: 0x3e115b4 VA: 0x75964295b4
	private Void _OnRemainTimeChanged(TickValue tick) { }
	// RVA: 0x3e112f0 VA: 0x75964292f0
	private RemainTimeContext _CalcRemainTime() { }
	// RVA: 0x3e10a58 VA: 0x7596428a58
	public Void .ctor() { }
}
```