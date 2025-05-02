# CrisisV2MapNodePreviewNodeItem

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `CrisisV2MapNodeViewBase _nodeViewPrefab`

- `RectTransform _holderContainer`

- `UIStateFinder m_stateFinder`

- `CrisisV2MapNodeViewBase m_node`


## Methods

- `Void Render(CrisisV2MapNodeModel, CrisisV2MapNodeStatus, Boolean)`

- `Void _OnNodeClick(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2MapNodePreviewNodeItem : MonoBehaviour, IHotfixable
{
	private CrisisV2MapNodeViewBase _nodeViewPrefab; // 0x18
	private RectTransform _holderContainer; // 0x20
	private UIStateFinder m_stateFinder; // 0x28
	private CrisisV2MapNodeViewBase m_node; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__OnNodeClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2c053d0 VA: 0x759521d3d0
	public Void Render(CrisisV2MapNodeModel nodeModel, CrisisV2MapNodeStatus nodeStatus, Boolean isExclusion) { }
	// RVA: 0x2c056f8 VA: 0x759521d6f8
	private Void _OnNodeClick(String nodeId) { }
	// RVA: 0x2c05814 VA: 0x759521d814
	public Void .ctor() { }
}
```