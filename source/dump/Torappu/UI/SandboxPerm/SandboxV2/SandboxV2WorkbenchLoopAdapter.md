# SandboxV2WorkbenchLoopAdapter

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2WorkbenchItemView _itemViewPrefab`

- `Boolean m_tutorialIsFirstItemRegistered`


## Methods

- `Void set_itemSelectEvent(Action`1)`

- `Void _TutorialOnly_TryRegisterAVGFirstItem(SandboxV2WorkbenchItemView)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2WorkbenchLoopAdapter : LoopScrollAdapter`2
{
	private SandboxV2WorkbenchItemView _itemViewPrefab; // 0x58
	private Action`1 <itemSelectEvent>k__BackingField; // 0x60
	private Boolean m_tutorialIsFirstItemRegistered; // 0x68
	private static DelegateBridge __Hotfix0_get_itemSelectEvent; // 0x0
	private static DelegateBridge __Hotfix0_set_itemSelectEvent; // 0x8
	private static DelegateBridge __Hotfix0_CreateView; // 0x10
	private static DelegateBridge __Hotfix0_UpdateView; // 0x18
	private static DelegateBridge __Hotfix0__TutorialOnly_TryRegisterAVGFirstItem; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Action`1 itemSelectEvent { get; set; }

	// RVA: 0x24f01e0 VA: 0x7594b081e0
	private Action`1 get_itemSelectEvent() { }
	// RVA: 0x24f0248 VA: 0x7594b08248
	public Void set_itemSelectEvent(Action`1 value) { }
	// RVA: 0x24f02cc VA: 0x7594b082cc
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x24f039c VA: 0x7594b0839c
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, SandboxV2WorkbenchItemModel data) { }
	// RVA: 0x24f053c VA: 0x7594b0853c
	private Void _TutorialOnly_TryRegisterAVGFirstItem(SandboxV2WorkbenchItemView view) { }
	// RVA: 0x24f0680 VA: 0x7594b08680
	public Void .ctor() { }
}
```