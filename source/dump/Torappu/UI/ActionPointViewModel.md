# ActionPointViewModel

**Namespace:** `Torappu.UI`


## Fields

- `IntProperty apProperty`

- `IntProperty maxApProperty`

- `APInfoProperty apInfoProperty`

- `Single m_timeAccum`

- `DateTime m_lastApAddTime`

- `Int32 m_apRegenMinutes`


## Properties

- `Int32 apRegenMinutes`

- `Int32 apRegenSeconds`

- `DateTime lastApAddTime`

- `Boolean isApFull`


## Methods

- `Int32 get_apRegenMinutes()`

- `Int32 get_apRegenSeconds()`

- `DateTime get_lastApAddTime()`

- `Boolean get_isApFull()`

- `Boolean CheckIfDataChanged(PlayerDataModel, PlayerDataModel, PlayerDataDelta)`

- `Void OnPlayerDataChanged()`

- `Void UpdateTime(Single)`

- `Void _UpdateCurrentAp()`

- `Void <>xLuaBaseProxy_OnCreate()`

- `Void <>xLuaBaseProxy_OnStart()`

- `Void <>xLuaBaseProxy_OnStop()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class ActionPointViewModel : PageSingleComponent, ITimeWatcher, IPlayerDataListener, IHotfixable, IDataBindWrapper
{
	private const Single UPDATE_INTERVAL; // 0x0
	public IntProperty apProperty; // 0x20
	public IntProperty maxApProperty; // 0x28
	public APInfoProperty apInfoProperty; // 0x30
	private Single m_timeAccum; // 0x38
	private DateTime m_lastApAddTime; // 0x40
	private Int32 m_apRegenMinutes; // 0x48
	private static DelegateBridge __Hotfix0_get_apRegenMinutes; // 0x0
	private static DelegateBridge __Hotfix0_get_apRegenSeconds; // 0x8
	private static DelegateBridge __Hotfix0_get_lastApAddTime; // 0x10
	private static DelegateBridge __Hotfix0_get_isApFull; // 0x18
	private static DelegateBridge __Hotfix0_CheckIfDataChanged; // 0x20
	private static DelegateBridge __Hotfix0_OnPlayerDataChanged; // 0x28
	private static DelegateBridge __Hotfix0_UpdateTime; // 0x30
	private static DelegateBridge __Hotfix0_OnCreate; // 0x38
	private static DelegateBridge __Hotfix0_OnStart; // 0x40
	private static DelegateBridge __Hotfix0_OnStop; // 0x48
	private static DelegateBridge __Hotfix0__UpdateCurrentAp; // 0x50
	private static DelegateBridge __Hotfix0_UpdateApInfo; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	protected Int32 apRegenMinutes { get; }
	public Int32 apRegenSeconds { get; }
	public DateTime lastApAddTime { get; }
	public Boolean isApFull { get; }

	// RVA: 0x220074c VA: 0x759481874c
	protected Int32 get_apRegenMinutes() { }
	// RVA: 0x22007e8 VA: 0x75948187e8
	public Int32 get_apRegenSeconds() { }
	// RVA: 0x220085c VA: 0x759481885c
	public DateTime get_lastApAddTime() { }
	// RVA: 0x22008c4 VA: 0x75948188c4
	public Boolean get_isApFull() { }
	// RVA: 0x2200958 VA: 0x7594818958
	public Boolean CheckIfDataChanged(PlayerDataModel prevData, PlayerDataModel curData, PlayerDataDelta delta) { }
	// RVA: 0x2200a70 VA: 0x7594818a70
	public Void OnPlayerDataChanged() { }
	// RVA: 0x2200ea0 VA: 0x7594818ea0
	public Void UpdateTime(Single deltaTime) { }
	// RVA: 0x2200f48 VA: 0x7594818f48
	protected override Void OnCreate() { }
	// RVA: 0x2200fd4 VA: 0x7594818fd4
	protected override Void OnStart() { }
	// RVA: 0x2201050 VA: 0x7594819050
	protected override Void OnStop() { }
	// RVA: 0x2200be4 VA: 0x7594818be4
	private Void _UpdateCurrentAp() { }
	// RVA: 0x22010c8 VA: 0x75948190c8
	protected virtual Void UpdateApInfo() { }
	// RVA: 0x220112c VA: 0x759481912c
	public Void .ctor() { }
	// RVA: 0x2201244 VA: 0x7594819244
	private Void <>xLuaBaseProxy_OnCreate() { }
	// RVA: 0x220124c VA: 0x759481924c
	private Void <>xLuaBaseProxy_OnStart() { }
	// RVA: 0x2201254 VA: 0x7594819254
	private Void <>xLuaBaseProxy_OnStop() { }
}
```