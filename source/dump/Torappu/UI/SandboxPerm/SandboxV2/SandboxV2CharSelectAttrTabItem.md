# SandboxV2CharSelectAttrTabItem

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2CharSelectTabEnum _tabType`

- `CharAttrTabTypeMessage _onSortTypeChanged`

- `TwoStateToggle _twoStateToggle`

- `UIStateFinder m_stateFinder`


## Properties

- `SandboxV2CharSelectTabEnum attrTabType`


## Methods

- `Void Render(SandboxV2CharSelectTabEnum)`

- `Void _OnToggle(State)`

- `SandboxV2CharSelectTabEnum get_attrTabType()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2CharSelectAttrTabItem : MonoBehaviour, IHotfixable
{
	private SandboxV2CharSelectTabEnum _tabType; // 0x18
	private CharAttrTabTypeMessage _onSortTypeChanged; // 0x20
	private TwoStateToggle _twoStateToggle; // 0x28
	private UIStateFinder m_stateFinder; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__OnToggle; // 0x8
	private static DelegateBridge __Hotfix0_get_attrTabType; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public SandboxV2CharSelectTabEnum attrTabType { get; }

	// RVA: 0x24861b0 VA: 0x7594a9e1b0
	public Void Render(SandboxV2CharSelectTabEnum attryTabType) { }
	// RVA: 0x2487694 VA: 0x7594a9f694
	private Void _OnToggle(State state) { }
	// RVA: 0x24877cc VA: 0x7594a9f7cc
	public SandboxV2CharSelectTabEnum get_attrTabType() { }
	// RVA: 0x2487834 VA: 0x7594a9f834
	public Void .ctor() { }
}
```