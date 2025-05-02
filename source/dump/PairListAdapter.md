# PairListAdapter

**Namespace:** ` `


## Fields

- `BattleSandboxConstructItemListModel model`

- `ShowType showType`

- `UIBattleSandboxConstructMenuItemList m_holder`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class PairListAdapter : SimpleLayoutAdapter
{
	public BattleSandboxConstructItemListModel model; // 0x20
	public ShowType showType; // 0x28
	private UIBattleSandboxConstructMenuItemList m_holder; // 0x30
	private static DelegateBridge __Hotfix0_get_count; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10

	public override Int32 count { get; }

	// RVA: 0x20c08d8 VA: 0x75946d88d8
	public override Int32 get_count() { }
	// RVA: 0x20c0164 VA: 0x75946d8164
	public Void .ctor(UIBattleSandboxConstructMenuItemList holder) { }
	// RVA: 0x20c0970 VA: 0x75946d8970
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
}
```