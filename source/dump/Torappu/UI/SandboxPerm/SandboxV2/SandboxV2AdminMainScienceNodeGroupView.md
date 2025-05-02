# SandboxV2AdminMainScienceNodeGroupView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `RectTransform _container`

- `SandboxV2AdminMainScienceNodeItem _nodePrefab`

- `NodeGroupAdapter m_adapter`


## Methods

- `Void set_eventOnNodeClick(Action`1)`

- `Void _InitIfNot()`

- `Void Render(ListDict`2, SandboxV2AdminMainScienceType, String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainScienceNodeGroupView : MonoBehaviour, IHotfixable
{
	private RectTransform _container; // 0x18
	private SandboxV2AdminMainScienceNodeItem _nodePrefab; // 0x20
	private NodeGroupAdapter m_adapter; // 0x28
	private Action`1 <eventOnNodeClick>k__BackingField; // 0x30
	private static DelegateBridge __Hotfix0_get_eventOnNodeClick; // 0x0
	private static DelegateBridge __Hotfix0_set_eventOnNodeClick; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private Action`1 eventOnNodeClick { get; set; }

	// RVA: 0x24e0714 VA: 0x7594af8714
	private Action`1 get_eventOnNodeClick() { }
	// RVA: 0x24e077c VA: 0x7594af877c
	public Void set_eventOnNodeClick(Action`1 value) { }
	// RVA: 0x24e0800 VA: 0x7594af8800
	private Void _InitIfNot() { }
	// RVA: 0x24e09a0 VA: 0x7594af89a0
	public Void Render(ListDict`2 viewModelList, SandboxV2AdminMainScienceType scienceType, String selectingNodeId, String topicId) { }
	// RVA: 0x24e0da0 VA: 0x7594af8da0
	public Void .ctor() { }
}
```