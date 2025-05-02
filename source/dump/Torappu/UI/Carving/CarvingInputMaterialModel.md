# CarvingInputMaterialModel

**Namespace:** `Torappu.UI.Carving`


## Methods

- `Void set_inputMaterials(List`1)`

- `Void LoadData(PlayerAct35SideCarving, Act35SideData)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingInputMaterialModel : IHotfixable
{
	private List`1 <inputMaterials>k__BackingField; // 0x10
	private static DelegateBridge __Hotfix0_get_inputMaterials; // 0x0
	private static DelegateBridge __Hotfix0_set_inputMaterials; // 0x8
	private static DelegateBridge __Hotfix0_LoadData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public List`1 inputMaterials { get; set; }

	// RVA: 0x2dbb08c VA: 0x75953d308c
	public List`1 get_inputMaterials() { }
	// RVA: 0x2dbf718 VA: 0x75953d7718
	private Void set_inputMaterials(List`1 value) { }
	// RVA: 0x2dbca10 VA: 0x75953d4a10
	public Void LoadData(PlayerAct35SideCarving carving, Act35SideData actData) { }
	// RVA: 0x2dbc9a0 VA: 0x75953d49a0
	public Void .ctor() { }
}
```