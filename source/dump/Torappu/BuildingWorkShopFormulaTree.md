# BuildingWorkShopFormulaTree

**Namespace:** `Torappu`


## Fields

- `Node currentNode`

- `Boolean m_isTreeAvail`


## Properties

- `Boolean isTreeAvail`


## Methods

- `Boolean get_isTreeAvail()`

- `Void _RefreshItemCount()`

- `Void RefreshTree()`

- `Int32 _GetFormulaWorkMaxCount(Node, Int32)`

- `Node TryGetNodeByItemId(String)`

- `Void _SetWorkFormulaTree(String, Int32, Boolean)`

- `Void _RegisterNode(Node)`

- `Void OutPutTree()`

- `Node _GenNodeWithOutChild(String, Int32, Boolean)`

- `Node _GenNodeWithOutChild(String, String, Int32, Int32, Boolean)`

- `Node _InternalGenNodeWithoutChild(Node, String, Int32, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu
public class BuildingWorkShopFormulaTree : IHotfixable
{
	public Node currentNode; // 0x10
	public Dictionary`2 nodeDict; // 0x18
	public List`1 nodeList; // 0x20
	public List`1 itemList; // 0x28
	private Boolean m_isTreeAvail; // 0x30
	public static readonly Int32 MAX_NODE_COUNT; // 0x0
	private static DelegateBridge __Hotfix0_get_isTreeAvail; // 0x8
	private static DelegateBridge __Hotfix0__RefreshItemCount; // 0x10
	private static DelegateBridge __Hotfix0_RefreshTree; // 0x18
	private static DelegateBridge __Hotfix0__GetFormulaWorkMaxCount; // 0x20
	private static DelegateBridge __Hotfix0_TryGetNodeByItemId; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30
	private static DelegateBridge _c__Hotfix1_ctor; // 0x38
	private static DelegateBridge __Hotfix0__SetWorkFormulaTree; // 0x40
	private static DelegateBridge __Hotfix0__RegisterNode; // 0x48
	private static DelegateBridge __Hotfix0_OutPutTree; // 0x50
	private static DelegateBridge __Hotfix0__GenNodeWithOutChild; // 0x58
	private static DelegateBridge __Hotfix1__GenNodeWithOutChild; // 0x60
	private static DelegateBridge __Hotfix0__InternalGenNodeWithoutChild; // 0x68

	public Boolean isTreeAvail { get; }

	// RVA: 0x2d0b5bc VA: 0x75953235bc
	public Boolean get_isTreeAvail() { }
	// RVA: 0x2d0b630 VA: 0x7595323630
	private Void _RefreshItemCount() { }
	// RVA: 0x2d0b884 VA: 0x7595323884
	public Void RefreshTree() { }
	// RVA: 0x2d0ba8c VA: 0x7595323a8c
	private Int32 _GetFormulaWorkMaxCount(Node node, Int32 defaultWorkMaxCount) { }
	// RVA: 0x2d0bc70 VA: 0x7595323c70
	public Node TryGetNodeByItemId(String itemId) { }
	// RVA: 0x2d0bd30 VA: 0x7595323d30
	public Void .ctor(String requireItemId) { }
	// RVA: 0x2d0c3c4 VA: 0x75953243c4
	public Void .ctor(String requireItemId, Int32 requireCount) { }
	// RVA: 0x2d0be2c VA: 0x7595323e2c
	private Void _SetWorkFormulaTree(String requireItem, Int32 requireCount, Boolean isNeedCalculateExtraRequire) { }
	// RVA: 0x2d0c5b4 VA: 0x75953245b4
	private Void _RegisterNode(Node node) { }
	// RVA: 0x2d0c99c VA: 0x759532499c
	public Void OutPutTree() { }
	// RVA: 0x2d0c4d0 VA: 0x75953244d0
	private Node _GenNodeWithOutChild(String itemId, Int32 requireCount, Boolean isNeedCalculateExtraRequire) { }
	// RVA: 0x2d0c7e4 VA: 0x75953247e4
	private Node _GenNodeWithOutChild(String parentNodeItemId, String itemId, Int32 requireCount, Int32 perCount, Boolean isNeedCalculateExtraRequire) { }
	// RVA: 0x2d0cf78 VA: 0x7595324f78
	private Node _InternalGenNodeWithoutChild(Node node, String itemId, Int32 requireCount, Boolean isNeedCalculateExtraRequire) { }
	// RVA: 0x2d0d274 VA: 0x7595325274
	private static Void .cctor() { }
}
```