# SandboxV2ArchiveAchievementTypeFilterView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SimpleLayoutContent _content`

- `Adapter m_adapter`

- `Boolean m_Inited`


## Methods

- `Void set_onSelectionChange(Action`2)`

- `Void Render(ArchiveAchievementModel)`

- `Void _InitIfNot()`

- `Void _OnChangeType(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2ArchiveAchievementTypeFilterView : MonoBehaviour, IArchiveAchievementListFilterView, IHotfixable
{
	private SimpleLayoutContent _content; // 0x18
	private Action`2 m_onChangeType; // 0x20
	private List`1 m_btnViewParams; // 0x28
	private Adapter m_adapter; // 0x30
	private Boolean m_Inited; // 0x38
	private Action`2 <onSelectionChange>k__BackingField; // 0x40
	private static DelegateBridge __Hotfix0_get_onSelectionChange; // 0x0
	private static DelegateBridge __Hotfix0_set_onSelectionChange; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0__OnChangeType; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Action`2 onSelectionChange { get; set; }

	// RVA: 0x24f9fe8 VA: 0x7594b11fe8
	public Action`2 get_onSelectionChange() { }
	// RVA: 0x24fa050 VA: 0x7594b12050
	public Void set_onSelectionChange(Action`2 value) { }
	// RVA: 0x24fa0d4 VA: 0x7594b120d4
	public Void Render(ArchiveAchievementModel viewModel) { }
	// RVA: 0x24fa464 VA: 0x7594b12464
	private Void _InitIfNot() { }
	// RVA: 0x24fa5c8 VA: 0x7594b125c8
	private Void _OnChangeType(String type) { }
	// RVA: 0x24fa66c VA: 0x7594b1266c
	public Void .ctor() { }
}
```