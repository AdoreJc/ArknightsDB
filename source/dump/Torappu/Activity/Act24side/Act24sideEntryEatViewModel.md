# Act24sideEntryEatViewModel

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `Boolean isHaveChance`

- `Boolean isHaveBuff`

- `Boolean timeOut`

- `String upItemId`

- `PlayerAct24SideActivity m_actData`

- `Int64 m_endTime`

- `Boolean m_isInited`


## Methods

- `Void LoadData(String)`

- `Void _InitData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideEntryEatViewModel : IHotfixable
{
	public Boolean isHaveChance; // 0x10
	public Boolean isHaveBuff; // 0x11
	public Boolean timeOut; // 0x12
	public String upItemId; // 0x18
	private PlayerAct24SideActivity m_actData; // 0x20
	private Int64 m_endTime; // 0x28
	private ListDict`2 m_actMealData; // 0x30
	private Boolean m_isInited; // 0x38
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__InitData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x329ec94 VA: 0x75958b6c94
	public Void LoadData(String actId) { }
	// RVA: 0x329f9b4 VA: 0x75958b79b4
	private Void _InitData(String actId) { }
	// RVA: 0x329e778 VA: 0x75958b6778
	public Void .ctor() { }
}
```