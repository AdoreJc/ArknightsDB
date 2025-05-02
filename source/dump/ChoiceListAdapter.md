# ChoiceListAdapter

**Namespace:** ` `


## Fields

- `DeepSeaRPChoiceModel m_choiceModel`

- `Action <onBtnLeave>k__BackingField`


## Properties

- `Action onBtnLeave`


## Methods

- `Void SetData(DeepSeaRPChoiceModel)`

- `Void set_onItemSelect(Action`2)`

- `Action get_onBtnLeave()`

- `Void set_onBtnLeave(Action)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class ChoiceListAdapter : SimpleLayoutAdapter
{
	private DeepSeaRPChoiceModel m_choiceModel; // 0x20
	private Action`2 <onItemSelect>k__BackingField; // 0x28
	private Action <onBtnLeave>k__BackingField; // 0x30
	private static DelegateBridge __Hotfix0_SetData; // 0x0
	private static DelegateBridge __Hotfix0_get_count; // 0x8
	private static DelegateBridge __Hotfix0_get_onItemSelect; // 0x10
	private static DelegateBridge __Hotfix0_set_onItemSelect; // 0x18
	private static DelegateBridge __Hotfix0_get_onBtnLeave; // 0x20
	private static DelegateBridge __Hotfix0_set_onBtnLeave; // 0x28
	private static DelegateBridge __Hotfix0_RenderView; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public override Int32 count { get; }
	private Action`2 onItemSelect { get; set; }
	private Action onBtnLeave { get; set; }

	// RVA: 0x29de3e4 VA: 0x7594ff63e4
	public Void SetData(DeepSeaRPChoiceModel choiceModel) { }
	// RVA: 0x29de468 VA: 0x7594ff6468
	public override Int32 get_count() { }
	// RVA: 0x29de510 VA: 0x7594ff6510
	private Action`2 get_onItemSelect() { }
	// RVA: 0x29de578 VA: 0x7594ff6578
	public Void set_onItemSelect(Action`2 value) { }
	// RVA: 0x29de5fc VA: 0x7594ff65fc
	private Action get_onBtnLeave() { }
	// RVA: 0x29de664 VA: 0x7594ff6664
	public Void set_onBtnLeave(Action value) { }
	// RVA: 0x29de6e8 VA: 0x7594ff66e8
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x29de8a4 VA: 0x7594ff68a4
	public Void .ctor() { }
}
```