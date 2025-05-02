# TimeSyncPeriodicTimer

**Namespace:** `Torappu`


## Fields

- `FP m_periodTime`

- `Int32 m_lastSyncCnt`


## Methods

- `Boolean Update(out)`

- `Boolean UpdateAndNext(out)`

- `Boolean TryNext(Int32, Boolean)`

- `Int32 _GetSyncCnt()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class TimeSyncPeriodicTimer
{
	private FP m_periodTime; // 0x10
	private Func`1 m_getTimeFunc; // 0x18
	private Int32 m_lastSyncCnt; // 0x20


	// RVA: 0x3103ce4 VA: 0x759571bce4
	public Void .ctor(FP periodTime, Boolean waitFirstPeriod, Func`1 getTimeFunc) { }
	// RVA: 0x3103e08 VA: 0x759571be08
	public Boolean Update(out Int32 updateDeltaCnt) { }
	// RVA: 0x3103e3c VA: 0x759571be3c
	public Boolean UpdateAndNext(out Int32 updateDeltaCnt) { }
	// RVA: 0x3103e80 VA: 0x759571be80
	public Boolean TryNext(Int32 updateDeltaCnt, Boolean force) { }
	// RVA: 0x3103d4c VA: 0x759571bd4c
	private Int32 _GetSyncCnt() { }
}
```