# SandboxV2EnemyRushTrackerViewModel

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
public class SandboxV2EnemyRushTrackerViewModel : IHotfixable
{
	private String m_topicId; // 0x10
	private Int32 m_enterSeq; // 0x18
	private ListDict`2 m_enemyRushViewModels; // 0x20
	public String selectedId; // 0x28
	public String confirmedNodeId; // 0x30
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_get_enemyRushViewModels; // 0x8
	private static DelegateBridge __Hotfix0_get_enterSeq; // 0x10
	private static DelegateBridge __Hotfix0_LoadData; // 0x18
	private static DelegateBridge __Hotfix0_GetSelectedNodeId; // 0x20
	private static DelegateBridge __Hotfix0_NotifyEnterSeq; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public String topicId { get; }
	public ListDict`2 enemyRushViewModels { get; }
	public Int32 enterSeq { get; }

	// RVA: 0x2556634 VA: 0x7594b6e634
	public String get_topicId() { }
	// RVA: 0x2552434 VA: 0x7594b6a434
	public ListDict`2 get_enemyRushViewModels() { }
	// RVA: 0x2556180 VA: 0x7594b6e180
	public Int32 get_enterSeq() { }
	// RVA: 0x2551e7c VA: 0x7594b69e7c
	public Void LoadData(String topicId, List`1 erFloatList) { }
	// RVA: 0x2552600 VA: 0x7594b6a600
	public String GetSelectedNodeId() { }
	// RVA: 0x255212c VA: 0x7594b6a12c
	public Void NotifyEnterSeq() { }
	// RVA: 0x25596c8 VA: 0x7594b716c8
	public Void .ctor() { }
}
```