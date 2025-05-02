# SandboxV2CharRepoListAdapter

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2CharRepoCharItemView _itemPrefab`


## Methods

- `Void set_onSlotClick(Action`1)`

- `Void set_onDineClick(Action`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2CharRepoListAdapter : LoopScrollAdapter`2, IHotfixable
{
	private SandboxV2CharRepoCharItemView _itemPrefab; // 0x58
	private Action`1 <onSlotClick>k__BackingField; // 0x60
	private Action`1 <onDineClick>k__BackingField; // 0x68
	private static DelegateBridge __Hotfix0_get_onSlotClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onSlotClick; // 0x8
	private static DelegateBridge __Hotfix0_get_onDineClick; // 0x10
	private static DelegateBridge __Hotfix0_set_onDineClick; // 0x18
	private static DelegateBridge __Hotfix0_CreateView; // 0x20
	private static DelegateBridge __Hotfix0_UpdateView; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Action`1 onSlotClick { get; set; }
	private Action`1 onDineClick { get; set; }

	// RVA: 0x260bfc8 VA: 0x7594c23fc8
	private Action`1 get_onSlotClick() { }
	// RVA: 0x260c030 VA: 0x7594c24030
	public Void set_onSlotClick(Action`1 value) { }
	// RVA: 0x260c0b4 VA: 0x7594c240b4
	private Action`1 get_onDineClick() { }
	// RVA: 0x260c11c VA: 0x7594c2411c
	public Void set_onDineClick(Action`1 value) { }
	// RVA: 0x260c1a0 VA: 0x7594c241a0
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x260c270 VA: 0x7594c24270
	public override Void UpdateView(Int32 position, GameObject viewObj, SandboxV2CharRepoListViewHolder holder, SandboxV2CharViewModel data) { }
	// RVA: 0x260c3f4 VA: 0x7594c243f4
	public Void .ctor() { }
}
```