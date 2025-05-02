# Act24sideEntryBattleTrapViewModel

**Namespace:** `Torappu.Activity.Act24side`


## Fields

- `Boolean isHaveNew`

- `Boolean timeOut`

- `Boolean m_isInited`

- `Int64 m_endTime`


## Methods

- `Void LoadData(String)`

- `Void _InitData(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act24side
public class Act24sideEntryBattleTrapViewModel : IHotfixable
{
	public Boolean isHaveNew; // 0x10
	public Boolean timeOut; // 0x11
	private ListDict`2 m_actToolData; // 0x18
	private Boolean m_isInited; // 0x20
	private Int64 m_endTime; // 0x28
	private List`1 m_idList; // 0x30
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__InitData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x329ebb4 VA: 0x75958b6bb4
	public Void LoadData(String actId) { }
	// RVA: 0x329f714 VA: 0x75958b7714
	private Void _InitData(String actId) { }
	// RVA: 0x329e7e8 VA: 0x75958b67e8
	public Void .ctor() { }
}
```