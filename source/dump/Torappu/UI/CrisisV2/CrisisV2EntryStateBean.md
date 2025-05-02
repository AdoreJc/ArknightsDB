# CrisisV2EntryStateBean

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `CrisisV2EntryProperty property`


## Methods

- `Void InitData()`

- `Void RefreshPlayerData()`

- `Void InitServerData(CrisisV2CacheServerData)`

- `String GetPermStageId()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2EntryStateBean : MonoBehaviour, IStateBean, IHotfixable
{
	public CrisisV2EntryProperty property; // 0x18
	private static DelegateBridge __Hotfix0_InitData; // 0x0
	private static DelegateBridge __Hotfix0_RefreshPlayerData; // 0x8
	private static DelegateBridge __Hotfix0_InitServerData; // 0x10
	private static DelegateBridge __Hotfix0_GetPermStageId; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2be5978 VA: 0x75951fd978
	public Void InitData() { }
	// RVA: 0x2be5a48 VA: 0x75951fda48
	public Void RefreshPlayerData() { }
	// RVA: 0x2be5c74 VA: 0x75951fdc74
	public Void InitServerData(CrisisV2CacheServerData data) { }
	// RVA: 0x2be6338 VA: 0x75951fe338
	public String GetPermStageId() { }
	// RVA: 0x2be63f8 VA: 0x75951fe3f8
	public Void .ctor() { }
}
```