# CarvingMainBoardModel

**Namespace:** `Torappu.UI.Carving`


## Fields

- `CarvingInputMaterialModel <inputMaterialModel>k__BackingField`

- `CarvingMainBoardOutputMaterialModel <outputMaterialModel>k__BackingField`

- `CarvingTopInfoViewModel <topInfoModel>k__BackingField`

- `String m_actId`

- `Act35SideData m_actData`


## Properties

- `CarvingInputMaterialModel inputMaterialModel`

- `CarvingMainBoardOutputMaterialModel outputMaterialModel`

- `CarvingTopInfoViewModel topInfoModel`


## Methods

- `CarvingInputMaterialModel get_inputMaterialModel()`

- `Void set_inputMaterialModel(CarvingInputMaterialModel)`

- `CarvingMainBoardOutputMaterialModel get_outputMaterialModel()`

- `Void set_outputMaterialModel(CarvingMainBoardOutputMaterialModel)`

- `CarvingTopInfoViewModel get_topInfoModel()`

- `Void set_topInfoModel(CarvingTopInfoViewModel)`

- `Void LoadData(String, Act35SideData)`

- `Void UpdateData()`

- `Void UpdateOutputMaterialData(ListDict`2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingMainBoardModel : IHotfixable
{
	private CarvingInputMaterialModel <inputMaterialModel>k__BackingField; // 0x10
	private CarvingMainBoardOutputMaterialModel <outputMaterialModel>k__BackingField; // 0x18
	private CarvingTopInfoViewModel <topInfoModel>k__BackingField; // 0x20
	private String m_actId; // 0x28
	private Act35SideData m_actData; // 0x30
	private static DelegateBridge __Hotfix0_get_inputMaterialModel; // 0x0
	private static DelegateBridge __Hotfix0_set_inputMaterialModel; // 0x8
	private static DelegateBridge __Hotfix0_get_outputMaterialModel; // 0x10
	private static DelegateBridge __Hotfix0_set_outputMaterialModel; // 0x18
	private static DelegateBridge __Hotfix0_get_topInfoModel; // 0x20
	private static DelegateBridge __Hotfix0_set_topInfoModel; // 0x28
	private static DelegateBridge __Hotfix0_LoadData; // 0x30
	private static DelegateBridge __Hotfix0_UpdateData; // 0x38
	private static DelegateBridge __Hotfix0_UpdateOutputMaterialData; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	public CarvingInputMaterialModel inputMaterialModel { get; set; }
	public CarvingMainBoardOutputMaterialModel outputMaterialModel { get; set; }
	public CarvingTopInfoViewModel topInfoModel { get; set; }

	// RVA: 0x2d976b8 VA: 0x75953af6b8
	public CarvingInputMaterialModel get_inputMaterialModel() { }
	// RVA: 0x2d97720 VA: 0x75953af720
	private Void set_inputMaterialModel(CarvingInputMaterialModel value) { }
	// RVA: 0x2d977a4 VA: 0x75953af7a4
	public CarvingMainBoardOutputMaterialModel get_outputMaterialModel() { }
	// RVA: 0x2d9780c VA: 0x75953af80c
	private Void set_outputMaterialModel(CarvingMainBoardOutputMaterialModel value) { }
	// RVA: 0x2d97890 VA: 0x75953af890
	public CarvingTopInfoViewModel get_topInfoModel() { }
	// RVA: 0x2d978f8 VA: 0x75953af8f8
	private Void set_topInfoModel(CarvingTopInfoViewModel value) { }
	// RVA: 0x2d9797c VA: 0x75953af97c
	public Void LoadData(String actId, Act35SideData actData) { }
	// RVA: 0x2d97a18 VA: 0x75953afa18
	public Void UpdateData() { }
	// RVA: 0x2d97df8 VA: 0x75953afdf8
	public Void UpdateOutputMaterialData(ListDict`2 slotCardList) { }
	// RVA: 0x2d982cc VA: 0x75953b02cc
	public Void .ctor() { }
}
```