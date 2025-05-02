# SandboxV2DineItemLoopAdapter

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2DineItemView _itemPrefab`

- `Boolean <initRender>k__BackingField`

- `Int32 <tutorialOnlyFirstFoodIndex>k__BackingField`

- `Boolean m_tutorialGoRegistered`


## Properties

- `Boolean initRender`

- `Int32 tutorialOnlyFirstFoodIndex`


## Methods

- `Void set_itemSelectEvent(Action`1)`

- `Boolean get_initRender()`

- `Void set_initRender(Boolean)`

- `Int32 get_tutorialOnlyFirstFoodIndex()`

- `Void set_tutorialOnlyFirstFoodIndex(Int32)`

- `Void _TutorialOnly_TryRegisterTutorialGo(SandboxV2DineItemView)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2DineItemLoopAdapter : LoopScrollAdapter`2
{
	private SandboxV2DineItemView _itemPrefab; // 0x58
	private Action`1 <itemSelectEvent>k__BackingField; // 0x60
	private Boolean <initRender>k__BackingField; // 0x68
	private Int32 <tutorialOnlyFirstFoodIndex>k__BackingField; // 0x6c
	private Boolean m_tutorialGoRegistered; // 0x70
	private static DelegateBridge __Hotfix0_get_itemSelectEvent; // 0x0
	private static DelegateBridge __Hotfix0_set_itemSelectEvent; // 0x8
	private static DelegateBridge __Hotfix0_get_initRender; // 0x10
	private static DelegateBridge __Hotfix0_set_initRender; // 0x18
	private static DelegateBridge __Hotfix0_get_tutorialOnlyFirstFoodIndex; // 0x20
	private static DelegateBridge __Hotfix0_set_tutorialOnlyFirstFoodIndex; // 0x28
	private static DelegateBridge __Hotfix0_CreateView; // 0x30
	private static DelegateBridge __Hotfix0_UpdateView; // 0x38
	private static DelegateBridge __Hotfix0__TutorialOnly_TryRegisterTutorialGo; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48

	private Action`1 itemSelectEvent { get; set; }
	private Boolean initRender { get; set; }
	private Int32 tutorialOnlyFirstFoodIndex { get; set; }

	// RVA: 0x2504f3c VA: 0x7594b1cf3c
	private Action`1 get_itemSelectEvent() { }
	// RVA: 0x2504fa4 VA: 0x7594b1cfa4
	public Void set_itemSelectEvent(Action`1 value) { }
	// RVA: 0x2505028 VA: 0x7594b1d028
	private Boolean get_initRender() { }
	// RVA: 0x2505090 VA: 0x7594b1d090
	public Void set_initRender(Boolean value) { }
	// RVA: 0x2505110 VA: 0x7594b1d110
	private Int32 get_tutorialOnlyFirstFoodIndex() { }
	// RVA: 0x2505178 VA: 0x7594b1d178
	public Void set_tutorialOnlyFirstFoodIndex(Int32 value) { }
	// RVA: 0x25051f4 VA: 0x7594b1d1f4
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x25052c4 VA: 0x7594b1d2c4
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, SandboxV2DineItemModel data) { }
	// RVA: 0x2505738 VA: 0x7594b1d738
	private Void _TutorialOnly_TryRegisterTutorialGo(SandboxV2DineItemView view) { }
	// RVA: 0x250587c VA: 0x7594b1d87c
	public Void .ctor() { }
}
```