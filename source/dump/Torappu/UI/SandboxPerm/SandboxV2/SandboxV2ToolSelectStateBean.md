# SandboxV2ToolSelectStateBean

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Input m_input`

- `Boolean m_isConfirm`

- `SandboxV2ToolSelectProp m_prop`


## Properties

- `Input input`

- `SandboxV2ToolSelectProp prop`


## Methods

- `Input get_input()`

- `SandboxV2ToolSelectProp get_prop()`

- `Void SetInput(Input)`

- `Void ConfirmSelect()`

- `Output GenOutput()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2ToolSelectStateBean : IStateBean, IHotfixable
{
	private Input m_input; // 0x10
	private Boolean m_isConfirm; // 0x40
	private SandboxV2ToolSelectProp m_prop; // 0x48
	private static DelegateBridge __Hotfix0_get_input; // 0x0
	private static DelegateBridge __Hotfix0_get_prop; // 0x8
	private static DelegateBridge __Hotfix0_SetInput; // 0x10
	private static DelegateBridge __Hotfix0_ConfirmSelect; // 0x18
	private static DelegateBridge __Hotfix0_GenOutput; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Input input { get; }
	public SandboxV2ToolSelectProp prop { get; }

	// RVA: 0x2622ff4 VA: 0x7594c3aff4
	public Input get_input() { }
	// RVA: 0x2622f8c VA: 0x7594c3af8c
	public SandboxV2ToolSelectProp get_prop() { }
	// RVA: 0x2624134 VA: 0x7594c3c134
	public Void SetInput(Input input) { }
	// RVA: 0x2623be0 VA: 0x7594c3bbe0
	public Void ConfirmSelect() { }
	// RVA: 0x26241e8 VA: 0x7594c3c1e8
	public Output GenOutput() { }
	// RVA: 0x2624078 VA: 0x7594c3c078
	public Void .ctor() { }
}
```