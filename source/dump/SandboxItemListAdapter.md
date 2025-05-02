# SandboxItemListAdapter

**Namespace:** ` `


## Fields

- `UIBattleSandboxBagPanel m_panel`


## Methods

- `Int32 Compare(String, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class SandboxItemListAdapter : SimpleLayoutAdapter, IComparer`1
{
	private UIBattleSandboxBagPanel m_panel; // 0x20
	public readonly List`1 bagResAdditionList; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_get_count; // 0x8
	private static DelegateBridge __Hotfix0_RenderView; // 0x10
	private static DelegateBridge __Hotfix0_Compare; // 0x18

	public override Int32 count { get; }

	// RVA: 0x2091734 VA: 0x75946a9734
	public Void .ctor(UIBattleSandboxBagPanel panel) { }
	// RVA: 0x2091dc0 VA: 0x75946a9dc0
	public override Int32 get_count() { }
	// RVA: 0x2091e40 VA: 0x75946a9e40
	public override GameObject RenderView(Int32 position, GameObject prefab, Transform parent) { }
	// RVA: 0x209207c VA: 0x75946aa07c
	public Int32 Compare(String lhs, String rhs) { }
}
```