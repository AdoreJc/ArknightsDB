# SandboxV2QuestTrackerViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String m_topicId`

- `Int32 m_enterSeq`

- `String selectedId`

- `String confirmedNodeId`


## Properties

- `String topicId`

- `Int32 enterSeq`


## Methods

- `String get_topicId()`

- `Int32 get_enterSeq()`

- `Void LoadData(String, List`1)`

- `Void NotifyEnterSeq()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2QuestTrackerViewModel : IHotfixable
{
	private String m_topicId; // 0x10
	private Int32 m_enterSeq; // 0x18
	private ListDict`2 m_questViewModels; // 0x20
	public String selectedId; // 0x28
	public String confirmedNodeId; // 0x30
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_get_questViewModels; // 0x8
	private static DelegateBridge __Hotfix0_get_enterSeq; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0_NotifyEnterSeq; // 0x20
	private static DelegateBridge __Hotfix0__FilterTrackerFloat; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public String topicId { get; }
	public ListDict`2 questViewModels { get; }
	public Int32 enterSeq { get; }

	// RVA: 0x2558c10 VA: 0x7594b70c10
	public String get_topicId() { }
	// RVA: 0x2554b30 VA: 0x7594b6cb30
	public ListDict`2 get_questViewModels() { }
	// RVA: 0x25586a8 VA: 0x7594b706a8
	public Int32 get_enterSeq() { }
	// RVA: 0x2553d30 VA: 0x7594b6bd30
	public Void LoadData(String topicId, List`1 nodeList) { }
	// RVA: 0x25544d4 VA: 0x7594b6c4d4
	public Void NotifyEnterSeq() { }
	// RVA: 0x2559b40 VA: 0x7594b71b40
	private List`1 _FilterTrackerFloat(SandboxV2QuestRouteType routeType, List`1 floatViewModels, String routeParam) { }
	// RVA: 0x2559fd0 VA: 0x7594b71fd0
	public Void .ctor() { }
}
```