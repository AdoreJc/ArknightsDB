# Act5D1RuneStageStateBean

**Namespace:** `Torappu.Activity.Act5D1`


## Fields

- `String cacheStageId`

- `String cacheRuneReId`


## Methods

- `Void Refresh()`

- `Void InitRuneInfo(String, String)`

- `Int32 GetRuneWarningLine()`

- `Int32 GetPointCount()`

- `Boolean GetNewHandFlag()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
public class Act5D1RuneStageStateBean : MonoBehaviour, IStateBean, IHotfixable
{
	public List`1 runeList; // 0x18
	public String cacheStageId; // 0x20
	public String cacheRuneReId; // 0x28
	private static DelegateBridge __Hotfix0_Refresh; // 0x0
	private static DelegateBridge __Hotfix0_InitRuneInfo; // 0x8
	private static DelegateBridge __Hotfix0_GetRuneWarningLine; // 0x10
	private static DelegateBridge __Hotfix0_GetPointCount; // 0x18
	private static DelegateBridge __Hotfix0_GetNewHandFlag; // 0x20
	private static DelegateBridge __Hotfix0_GetBanList; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x31d90d8 VA: 0x75957f10d8
	public Void Refresh() { }
	// RVA: 0x31d92cc VA: 0x75957f12cc
	public Void InitRuneInfo(String runeReId, String stageId) { }
	// RVA: 0x31d9988 VA: 0x75957f1988
	public Int32 GetRuneWarningLine() { }
	// RVA: 0x31d9a38 VA: 0x75957f1a38
	public Int32 GetPointCount() { }
	// RVA: 0x31d9b54 VA: 0x75957f1b54
	public Boolean GetNewHandFlag() { }
	// RVA: 0x31d9c44 VA: 0x75957f1c44
	public List`1 GetBanList() { }
	// RVA: 0x31d9e08 VA: 0x75957f1e08
	public Void .ctor() { }
}
```