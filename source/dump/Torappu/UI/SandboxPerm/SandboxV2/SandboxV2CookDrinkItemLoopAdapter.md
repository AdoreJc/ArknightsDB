# SandboxV2CookDrinkItemLoopAdapter

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2CookDrinkItemView _itemViewPrefab`

- `Boolean m_tutorialIsFirstItemRegistered`


## Methods

- `Void set_itemSelectEvent(Func`3)`

- `Void _TutorialOnly_TryRegisterAVGFirstItem(SandboxV2CookDrinkItemView)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2CookDrinkItemLoopAdapter : LoopScrollAdapter`2
{
	private SandboxV2CookDrinkItemView _itemViewPrefab; // 0x58
	private Func`3 <itemSelectEvent>k__BackingField; // 0x60
	private Boolean m_tutorialIsFirstItemRegistered; // 0x68
	private static DelegateBridge __Hotfix0_get_itemSelectEvent; // 0x0
	private static DelegateBridge __Hotfix0_set_itemSelectEvent; // 0x8
	private static DelegateBridge __Hotfix0_CreateView; // 0x10
	private static DelegateBridge __Hotfix0_UpdateView; // 0x18
	private static DelegateBridge __Hotfix0__TutorialOnly_TryRegisterAVGFirstItem; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	private Func`3 itemSelectEvent { get; set; }

	// RVA: 0x24c3ffc VA: 0x7594adbffc
	private Func`3 get_itemSelectEvent() { }
	// RVA: 0x24c4064 VA: 0x7594adc064
	public Void set_itemSelectEvent(Func`3 value) { }
	// RVA: 0x24c40e8 VA: 0x7594adc0e8
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x24c41e4 VA: 0x7594adc1e4
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, SandboxV2CookDrinkItemModel data) { }
	// RVA: 0x24c44bc VA: 0x7594adc4bc
	private Void _TutorialOnly_TryRegisterAVGFirstItem(SandboxV2CookDrinkItemView view) { }
	// RVA: 0x24c4678 VA: 0x7594adc678
	public Void .ctor() { }
}
```