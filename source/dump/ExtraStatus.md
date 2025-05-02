# ExtraStatus

**Namespace:** ` `


## Fields

- `Text _battleEndTimeText`

- `UICooperateLagDisplay _lagDisplay`

- `UILifePoint _mateLifePoint`

- `UILifeLostGroup _mateLifeLostGroup`

- `UIInfoToastPanel _toastPanel`

- `Single m_ticker`

- `Int64 m_forceEndTimestamp`

- `UIInfoToastPanel m_toastPanel`

- `PlayerSide m_mateSide`


## Methods

- `Void InitData()`

- `Void OnCreate()`

- `Void UpdateData()`

- `Void HideMateHPInfo()`

- `Void RestoreMateHPInfo()`

- `Void _UpdateTopBar(Boolean)`

- `Void _UpdateBattleEndTime()`

- `Void _UpdateLagDisplay()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ExtraStatus
{
	private const Single TICK_INTERVAL; // 0x0
	private Text _battleEndTimeText; // 0x10
	private UICooperateLagDisplay _lagDisplay; // 0x18
	private UILifePoint _mateLifePoint; // 0x20
	private UILifeLostGroup _mateLifeLostGroup; // 0x28
	private UIInfoToastPanel _toastPanel; // 0x30
	private Single m_ticker; // 0x38
	private Int64 m_forceEndTimestamp; // 0x40
	private UIInfoToastPanel m_toastPanel; // 0x48
	private PlayerSide m_mateSide; // 0x50


	// RVA: 0x20e7f28 VA: 0x75946fff28
	public Void InitData() { }
	// RVA: 0x20e8204 VA: 0x7594700204
	public Void OnCreate() { }
	// RVA: 0x20e80c4 VA: 0x75947000c4
	public Void UpdateData() { }
	// RVA: 0x20e857c VA: 0x759470057c
	public Void HideMateHPInfo() { }
	// RVA: 0x20e85a4 VA: 0x75947005a4
	public Void RestoreMateHPInfo() { }
	// RVA: 0x20e8144 VA: 0x7594700144
	private Void _UpdateTopBar(Boolean force) { }
	// RVA: 0x20e8364 VA: 0x7594700364
	private Void _UpdateBattleEndTime() { }
	// RVA: 0x20e84a4 VA: 0x75947004a4
	private Void _UpdateLagDisplay() { }
	// RVA: 0x20e8798 VA: 0x7594700798
	public Void .ctor() { }
}
```