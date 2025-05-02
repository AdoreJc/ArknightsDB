# SandboxV2OtherTrackerViewModel

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

- `String GetSelectedNodeId()`

- `Void NotifyEnterSeq()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2OtherTrackerViewModel : IHotfixable
{
	private String m_topicId; // 0x10
	private Int32 m_enterSeq; // 0x18
	private ListDict`2 m_itemViewModels; // 0x20
	public String selectedId; // 0x28
	public String confirmedNodeId; // 0x30
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_get_enterSeq; // 0x8
	private static DelegateBridge __Hotfix0_get_itemViewModels; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0_GetSelectedNodeId; // 0x20
	private static DelegateBridge __Hotfix0_NotifyEnterSeq; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public String topicId { get; }
	public Int32 enterSeq { get; }
	public ListDict`2 itemViewModels { get; }

	// RVA: 0x25574c0 VA: 0x7594b6f4c0
	public String get_topicId() { }
	// RVA: 0x2557528 VA: 0x7594b6f528
	public Int32 get_enterSeq() { }
	// RVA: 0x2553714 VA: 0x7594b6b714
	public ListDict`2 get_itemViewModels() { }
	// RVA: 0x2552fc4 VA: 0x7594b6afc4
	public Void LoadData(String topicId, List`1 nodeList) { }
	// RVA: 0x255377c VA: 0x7594b6b77c
	public String GetSelectedNodeId() { }
	// RVA: 0x2553410 VA: 0x7594b6b410
	public Void NotifyEnterSeq() { }
	// RVA: 0x2559794 VA: 0x7594b71794
	public Void .ctor() { }
}
```