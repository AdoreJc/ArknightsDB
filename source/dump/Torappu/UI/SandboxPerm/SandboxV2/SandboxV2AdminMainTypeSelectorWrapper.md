# SandboxV2AdminMainTypeSelectorWrapper

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2AdminMainTypeSelector m_selector`


## Methods

- `Void add_eTypeSelectChanged(Action`1)`

- `Void remove_eTypeSelectChanged(Action`1)`

- `Void Init(SandboxV2AdminMainTypeSelector, Color, IList`1, Transform)`

- `Void _EventSelectChanged(Int32)`

- `Void SetSelectType(TypeEnum)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2AdminMainTypeSelectorWrapper`1 : MonoBehaviour, IHotfixable
{
	private SandboxV2AdminMainTypeSelector m_selector; // 0x0
	private IList`1 m_typeList; // 0x0
	private Action`1 eTypeSelectChanged; // 0x0
	private static DelegateBridge __Hotfix0_add_eTypeSelectChanged; // 0x0
	private static DelegateBridge __Hotfix0_remove_eTypeSelectChanged; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0__EventSelectChanged; // 0x0
	private static DelegateBridge __Hotfix0_SetSelectType; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0


	// RVA: 0x VA: 0x0
	public Void add_eTypeSelectChanged(Action`1 value) { }
	// RVA: 0x VA: 0x0
	public Void remove_eTypeSelectChanged(Action`1 value) { }
	// RVA: 0x VA: 0x0
	public Void Init(SandboxV2AdminMainTypeSelector selectorPrefab, Color selectedColor, IList`1 typeList, Transform root) { }
	// RVA: 0x VA: 0x0
	private Void _EventSelectChanged(Int32 idx) { }
	// RVA: 0x VA: 0x0
	public Void SetSelectType(TypeEnum t) { }
	// RVA: 0x VA: 0x0
	public Void .ctor() { }
}
```