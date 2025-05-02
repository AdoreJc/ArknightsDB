# SandboxV2AdminCharSelectRecycleAdapter

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `LoopScrollRect _scrollRect`

- `SandboxV2AdminCharSelectAbstractRightItemView _itemView`


## Properties

- `LoopScrollRect scrollRect`


## Methods

- `LoopScrollRect get_scrollRect()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminCharSelectRecycleAdapter : LoopScrollAdapter`2
{
	private LoopScrollRect _scrollRect; // 0x58
	private SandboxV2AdminCharSelectAbstractRightItemView _itemView; // 0x60
	private static DelegateBridge __Hotfix0_get_scrollRect; // 0x0
	private static DelegateBridge __Hotfix0_UpdateView; // 0x8
	private static DelegateBridge __Hotfix0_CreateView; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public LoopScrollRect scrollRect { get; }

	// RVA: 0x24ae464 VA: 0x7594ac6464
	public LoopScrollRect get_scrollRect() { }
	// RVA: 0x24ae4cc VA: 0x7594ac64cc
	public override Void UpdateView(Int32 position, GameObject view, SandboxV2AdminCharSelectViewHolder holder, SandboxV2CharViewModel data) { }
	// RVA: 0x24ae674 VA: 0x7594ac6674
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x24ae74c VA: 0x7594ac674c
	public Void .ctor() { }
}
```