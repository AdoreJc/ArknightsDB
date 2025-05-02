# SandboxV2NodePreviewNpcLoopAdapter

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2NodePreviewNpcItemView _itemPrefab`

- `UIPageFinder m_finder`

- `String <topicId>k__BackingField`


## Properties

- `String topicId`


## Methods

- `String get_topicId()`

- `Void set_topicId(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2NodePreviewNpcLoopAdapter : LoopScrollAdapter`2
{
	private SandboxV2NodePreviewNpcItemView _itemPrefab; // 0x58
	private UIPageFinder m_finder; // 0x60
	private String <topicId>k__BackingField; // 0x70
	private static DelegateBridge __Hotfix0_get_topicId; // 0x0
	private static DelegateBridge __Hotfix0_set_topicId; // 0x8
	private static DelegateBridge __Hotfix0_CreateView; // 0x10
	private static DelegateBridge __Hotfix0_UpdateView; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	private String topicId { get; set; }

	// RVA: 0x256df44 VA: 0x7594b85f44
	private String get_topicId() { }
	// RVA: 0x256ce4c VA: 0x7594b84e4c
	public Void set_topicId(String value) { }
	// RVA: 0x256dfac VA: 0x7594b85fac
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x256e0a8 VA: 0x7594b860a8
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, SandboxV2DungeonNpcViewModel data) { }
	// RVA: 0x256e240 VA: 0x7594b86240
	public Void .ctor() { }
}
```