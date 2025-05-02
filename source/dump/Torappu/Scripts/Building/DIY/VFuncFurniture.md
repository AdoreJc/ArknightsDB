# VFuncFurniture

**Namespace:** `Torappu.Scripts.Building.DIY`


## Fields

- `Transform _btnPos`

- `FurnitureSubType m_subType`

- `ILODHolder m_lodHolder`


## Properties

- `Transform btnPos`

- `FurnitureSubType subType`

- `ILODHolder lodHolder`

- `Boolean lodVisible`


## Methods

- `Transform get_btnPos()`

- `FurnitureSubType get_subType()`

- `Void set_subType(FurnitureSubType)`

- `Void OpenFunctionPage()`

- `Void _TryOpenMessageLeavePage()`

- `Void _TryOpenMusicPlayerPage()`

- `ILODHolder get_lodHolder()`

- `Boolean get_lodVisible()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Scripts.Building.DIY
public class VFuncFurniture : MonoBehaviour, IHotfixable
{
	private Transform _btnPos; // 0x18
	private FurnitureSubType m_subType; // 0x20
	private ILODHolder m_lodHolder; // 0x28
	private static DelegateBridge __Hotfix0_get_btnPos; // 0x0
	private static DelegateBridge __Hotfix0_get_subType; // 0x8
	private static DelegateBridge __Hotfix0_set_subType; // 0x10
	private static DelegateBridge __Hotfix0_OpenFunctionPage; // 0x18
	private static DelegateBridge __Hotfix0__TryOpenMessageLeavePage; // 0x20
	private static DelegateBridge __Hotfix0__TryOpenMusicPlayerPage; // 0x28
	private static DelegateBridge __Hotfix0_get_lodHolder; // 0x30
	private static DelegateBridge __Hotfix0_get_lodVisible; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	public Transform btnPos { get; }
	public FurnitureSubType subType { get; set; }
	private ILODHolder lodHolder { get; }
	protected Boolean lodVisible { get; }

	// RVA: 0x37766f0 VA: 0x7595d8e6f0
	public Transform get_btnPos() { }
	// RVA: 0x3776758 VA: 0x7595d8e758
	public FurnitureSubType get_subType() { }
	// RVA: 0x37767c0 VA: 0x7595d8e7c0
	public Void set_subType(FurnitureSubType value) { }
	// RVA: 0x377683c VA: 0x7595d8e83c
	public Void OpenFunctionPage() { }
	// RVA: 0x3776a78 VA: 0x7595d8ea78
	private Void _TryOpenMessageLeavePage() { }
	// RVA: 0x3776b64 VA: 0x7595d8eb64
	private Void _TryOpenMusicPlayerPage() { }
	// RVA: 0x3776d54 VA: 0x7595d8ed54
	private ILODHolder get_lodHolder() { }
	// RVA: 0x3776980 VA: 0x7595d8e980
	protected Boolean get_lodVisible() { }
	// RVA: 0x3776df0 VA: 0x7595d8edf0
	public Void .ctor() { }
}
```