# NodeGroupAdapter

**Namespace:** ` `


## Fields

- `SandboxV2AdminMainScienceNodeGroupView m_closure`

- `SandboxV2AdminMainScienceType m_cachedType`


## Methods

- `Void RefreshView(ListDict`2, SandboxV2AdminMainScienceType, String, String)`

- `SandboxV2AdminMainScienceNodeItem _GetView(Int32)`

- `Void _UpdateViewInstance(Int32, SandboxV2AdminMainScienceNodeItem)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class NodeGroupAdapter : IHotfixable
{
	private SandboxV2AdminMainScienceNodeGroupView m_closure; // 0x10
	private List`1 m_nodeViews; // 0x18
	private SandboxV2AdminMainScienceType m_cachedType; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_RefreshView; // 0x8
	private static DelegateBridge __Hotfix0__GetView; // 0x10
	private static DelegateBridge __Hotfix0__UpdateViewInstance; // 0x18


	// RVA: 0x24e08b8 VA: 0x7594af88b8
	public Void .ctor(SandboxV2AdminMainScienceNodeGroupView closure) { }
	// RVA: 0x24e0a70 VA: 0x7594af8a70
	public Void RefreshView(ListDict`2 viewModelList, SandboxV2AdminMainScienceType curType, String selectingNodeId, String topicId) { }
	// RVA: 0x24e0e10 VA: 0x7594af8e10
	private SandboxV2AdminMainScienceNodeItem _GetView(Int32 position) { }
	// RVA: 0x24e10b0 VA: 0x7594af90b0
	private Void _UpdateViewInstance(Int32 position, SandboxV2AdminMainScienceNodeItem view) { }
}
```