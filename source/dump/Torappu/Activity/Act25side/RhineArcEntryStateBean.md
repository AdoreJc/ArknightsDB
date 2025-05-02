# RhineArcEntryStateBean

**Namespace:** `Torappu.Activity.Act25side`


## Fields

- `RhineArcProperty property`


## Methods

- `Void LoadData(String, EnterType, String)`

- `Void UpdateAllNewMark(String)`

- `Void UpdateKeyItemNewMark(String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act25side
public class RhineArcEntryStateBean : MonoBehaviour, IStateBean, IHotfixable, IDataBindWrapper
{
	public RhineArcProperty property; // 0x18
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0_UpdateAllNewMark; // 0x8
	private static DelegateBridge __Hotfix0_UpdateKeyItemNewMark; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3274bf8 VA: 0x759588cbf8
	public Void LoadData(String actId, EnterType enterType, String selectAreaId) { }
	// RVA: 0x3275608 VA: 0x759588d608
	public Void UpdateAllNewMark(String actId) { }
	// RVA: 0x3275828 VA: 0x759588d828
	public Void UpdateKeyItemNewMark(String itemId, String actId) { }
	// RVA: 0x3275a50 VA: 0x759588da50
	public Void .ctor() { }
}
```