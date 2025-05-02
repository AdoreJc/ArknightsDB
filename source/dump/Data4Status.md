# Data4Status

**Namespace:** ` `


## Fields

- `ServiceAntiDataSDK m_activeInst`

- `Data4State m_state`

- `Data4Cache m_cache`

- `Double m_startScanTs`


## Methods

- `Void NotifyEnterGame(ServiceAntiDataSDK)`

- `Void NotifyServiceResp(String)`

- `Void Tick(Single)`

- `Void _SetState(Data4State)`

- `Void _OnStateChanged(Data4State, Data4State)`


## Dump
```C#
// Dll : Torappu.Common.dll
// Namespace : 
protected class Data4Status
{
	private ServiceAntiDataSDK m_activeInst; // 0x10
	private Data4State m_state; // 0x18
	private Data4Cache m_cache; // 0x20
	private Double m_startScanTs; // 0x50
	private ListSet`1 m_uploadedUIDs; // 0x58


	// RVA: 0x6791c2c VA: 0x7598da9c2c
	public Void NotifyEnterGame(ServiceAntiDataSDK sdkInst) { }
	// RVA: 0x6791ab4 VA: 0x7598da9ab4
	public Void NotifyServiceResp(String serviceCode) { }
	// RVA: 0x67919c4 VA: 0x7598da99c4
	public Byte[] ConsumeData4(String serviceCode) { }
	// RVA: 0x6791fa0 VA: 0x7598da9fa0
	public Void Tick(Single timeDelta) { }
	// RVA: 0x6792528 VA: 0x7598daa528
	private Void _SetState(Data4State target) { }
	// RVA: 0x6792544 VA: 0x7598daa544
	private Void _OnStateChanged(Data4State prev, Data4State curr) { }
	// RVA: 0x6792498 VA: 0x7598daa498
	public Void .ctor() { }
}
```