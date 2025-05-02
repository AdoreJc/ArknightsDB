# ZoneHomeToDoGroupModel

**Namespace:** `Torappu.UI.Stage`


## Methods

- `Void LoadData(CrisisV2ServerDataWrapper)`

- `Void _UpdateViewIndex()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class ZoneHomeToDoGroupModel : IHotfixable
{
	public List`1 todoList; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x0
	private static DelegateBridge __Hotfix0__UpdateViewIndex; // 0x8
	private static DelegateBridge __Hotfix0__CompareToDo; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2f0ad4c VA: 0x7595522d4c
	public Void LoadData(CrisisV2ServerDataWrapper crisisData) { }
	// RVA: 0x2f0bafc VA: 0x7595523afc
	private Void _UpdateViewIndex() { }
	// RVA: 0x2f0bbd0 VA: 0x7595523bd0
	private static Int32 _CompareToDo(ZoneHomeToDoItemModel lhs, ZoneHomeToDoItemModel rhs) { }
	// RVA: 0x2f0be0c VA: 0x7595523e0c
	public Void .ctor() { }
}
```