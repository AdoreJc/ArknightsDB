# Act24sideEntryMissionViewModel

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `Boolean isHaveOver`

- `Boolean m_isInited`


## Methods

- `Void LoadData(String)`

- `Void _InitData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideEntryMissionViewModel : IHotfixable
{
	public Boolean isHaveOver; // 0x10
	private ListDict`2 m_actMissionData; // 0x18
	private Boolean m_isInited; // 0x20
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__InitData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x329e91c VA: 0x75958b691c
	public Void LoadData(String actId) { }
	// RVA: 0x329fb04 VA: 0x75958b7b04
	private Void _InitData(String actId) { }
	// RVA: 0x329e858 VA: 0x75958b6858
	public Void .ctor() { }
}
```