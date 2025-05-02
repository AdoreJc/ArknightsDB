# BuffListAdapter

**Namespace:** ` `


## Fields

- `RL04DifficultyRulesView m_view`


## Methods

- `Void set_buffList(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class BuffListAdapter : SimpleLayoutAdapter
{
	private RL04DifficultyRulesView m_view; // 0x20
	private List`1 <buffList>k__BackingField; // 0x28
	private static DelegateBridge __Hotfix0_get_buffList; // 0x0
	private static DelegateBridge __Hotfix0_set_buffList; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10
	private static DelegateBridge __Hotfix0_get_count; // 0x18
	private static DelegateBridge __Hotfix0_RenderView; // 0x20

	public List`1 buffList { get; set; }
	public override Int32 count { get; }

	// RVA: 0x26eb280 VA: 0x7594d03280
	public List`1 get_buffList() { }
	// RVA: 0x26eab0c VA: 0x7594d02b0c
	public Void set_buffList(List`1 value) { }
	// RVA: 0x26ea814 VA: 0x7594d02814
	public Void .ctor(RL04DifficultyRulesView view) { }
	// RVA: 0x26eb2e8 VA: 0x7594d032e8
	public override Int32 get_count() { }
	// RVA: 0x26eb378 VA: 0x7594d03378
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
}
```