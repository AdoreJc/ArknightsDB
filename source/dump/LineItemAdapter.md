# LineItemAdapter

**Namespace:** ` `


## Fields

- `SandboxV2AdminMainScienceLineGroupView m_closure`

- `SandboxV2AdminMainScienceType m_cachedType`


## Methods

- `Void RefreshView(List`1, SandboxV2AdminMainScienceType)`

- `SandboxV2AdminMainScienceLineItemView _GetView(Int32)`

- `Void _UpdateViewInstance(Int32, SandboxV2AdminMainScienceLineItemView)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class LineItemAdapter : IHotfixable
{
	private SandboxV2AdminMainScienceLineGroupView m_closure; // 0x10
	private List`1 m_views; // 0x18
	private SandboxV2AdminMainScienceType m_cachedType; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_RefreshView; // 0x8
	private static DelegateBridge __Hotfix0__GetView; // 0x10
	private static DelegateBridge __Hotfix0__UpdateViewInstance; // 0x18


	// RVA: 0x24df740 VA: 0x7594af7740
	public Void .ctor(SandboxV2AdminMainScienceLineGroupView closure) { }
	// RVA: 0x24df8d0 VA: 0x7594af78d0
	public Void RefreshView(List`1 viewModelList, SandboxV2AdminMainScienceType selectedType) { }
	// RVA: 0x24dfb94 VA: 0x7594af7b94
	private SandboxV2AdminMainScienceLineItemView _GetView(Int32 position) { }
	// RVA: 0x24dfeec VA: 0x7594af7eec
	private Void _UpdateViewInstance(Int32 position, SandboxV2AdminMainScienceLineItemView view) { }
}
```