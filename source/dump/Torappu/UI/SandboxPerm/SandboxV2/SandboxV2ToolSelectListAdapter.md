# SandboxV2ToolSelectListAdapter

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2ToolSelectItemView _itemPrefab`

- `SandboxV2ToolSelectModel <toolSelectModel>k__BackingField`


## Properties

- `SandboxV2ToolSelectModel toolSelectModel`


## Methods

- `Void set_onItemClick(Action`1)`

- `SandboxV2ToolSelectModel get_toolSelectModel()`

- `Void set_toolSelectModel(SandboxV2ToolSelectModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2ToolSelectListAdapter : LoopScrollAdapter`2, IHotfixable
{
	private SandboxV2ToolSelectItemView _itemPrefab; // 0x58
	private Action`1 <onItemClick>k__BackingField; // 0x60
	private SandboxV2ToolSelectModel <toolSelectModel>k__BackingField; // 0x68
	private static DelegateBridge __Hotfix0_get_onItemClick; // 0x0
	private static DelegateBridge __Hotfix0_set_onItemClick; // 0x8
	private static DelegateBridge __Hotfix0_get_toolSelectModel; // 0x10
	private static DelegateBridge __Hotfix0_set_toolSelectModel; // 0x18
	private static DelegateBridge __Hotfix0_CreateView; // 0x20
	private static DelegateBridge __Hotfix0_UpdateView; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	private Action`1 onItemClick { get; set; }
	public SandboxV2ToolSelectModel toolSelectModel { get; set; }

	// RVA: 0x262260c VA: 0x7594c3a60c
	private Action`1 get_onItemClick() { }
	// RVA: 0x2622674 VA: 0x7594c3a674
	public Void set_onItemClick(Action`1 value) { }
	// RVA: 0x26226f8 VA: 0x7594c3a6f8
	public SandboxV2ToolSelectModel get_toolSelectModel() { }
	// RVA: 0x2622760 VA: 0x7594c3a760
	public Void set_toolSelectModel(SandboxV2ToolSelectModel value) { }
	// RVA: 0x26227e4 VA: 0x7594c3a7e4
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x26228b4 VA: 0x7594c3a8b4
	public override Void UpdateView(Int32 position, GameObject viewObj, SandboxV2ToolSelectListViewHolder holder, SandboxV2SquadToolModel data) { }
	// RVA: 0x2622bf0 VA: 0x7594c3abf0
	public Void .ctor() { }
}
```