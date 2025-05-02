# TuningHomeMajorInvestDetailViewModel

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `Int32 currProgress`

- `Int32 majorMaxCount`

- `String detailDesc1`

- `String detailDesc2`

- `String detailDesc3`

- `String detailDesc4`

- `String m_detailDescFormat1`

- `String m_detailDescFormat2`

- `String m_detailDescFormat3`

- `String m_detailDescFormat4`

- `String m_tokenName`

- `String m_actId`


## Methods

- `Void LoadData(String)`

- `Void RefreshPlayerData()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningHomeMajorInvestDetailViewModel : IHotfixable
{
	public List`1 majorItemList; // 0x10
	public Int32 currProgress; // 0x18
	public Int32 majorMaxCount; // 0x1c
	public String detailDesc1; // 0x20
	public String detailDesc2; // 0x28
	public String detailDesc3; // 0x30
	public String detailDesc4; // 0x38
	private String m_detailDescFormat1; // 0x40
	private String m_detailDescFormat2; // 0x48
	private String m_detailDescFormat3; // 0x50
	private String m_detailDescFormat4; // 0x58
	private String m_tokenName; // 0x60
	private String m_actId; // 0x68
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_RefreshPlayerData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x232ca94 VA: 0x7594944a94
	public Void LoadData(String actId) { }
	// RVA: 0x232d014 VA: 0x7594945014
	public Void RefreshPlayerData() { }
	// RVA: 0x232de10 VA: 0x7594945e10
	public Void .ctor() { }
}
```