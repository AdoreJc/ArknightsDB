# CarvingMainBoardOutputMaterialModel

**Namespace:** `Torappu.UI.Carving`


## Fields

- `Int32 point`

- `BirdSpineState spineState`


## Methods

- `Void LoadOutputModel(Act35SideData, List`1, ListDict`2, String)`

- `Void _CalcCurSpineState(String, Act35SideData)`

- `Boolean _DiffSlotCardList(ListDict`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingMainBoardOutputMaterialModel : IHotfixable
{
	public List`1 outputMaterialItemList; // 0x10
	public Int32 point; // 0x18
	public BirdSpineState spineState; // 0x1c
	private ListDict`2 m_cachedSlotCardList; // 0x20
	private static DelegateBridge __Hotfix0_LoadOutputModel; // 0x0
	private static DelegateBridge __Hotfix0__CalcCurSpineState; // 0x8
	private static DelegateBridge __Hotfix0__DiffSlotCardList; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2d98004 VA: 0x75953b0004
	public Void LoadOutputModel(Act35SideData actData, List`1 inputList, ListDict`2 slotCardList, String actId) { }
	// RVA: 0x2d9853c VA: 0x75953b053c
	private Void _CalcCurSpineState(String actId, Act35SideData actData) { }
	// RVA: 0x2d9833c VA: 0x75953b033c
	private Boolean _DiffSlotCardList(ListDict`2 newSlotCardList) { }
	// RVA: 0x2d97ef0 VA: 0x75953afef0
	public Void .ctor() { }
}
```