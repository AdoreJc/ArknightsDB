# HomeSecretarySkinFilterItemView

**Namespace:** `Torappu.UI.Home`


## Fields

- `FilterType _type`

- `TwoStateToggle _toggle`

- `UIStateFinder m_stateFinder`


## Properties

- `FilterType type`

- `Boolean selected`


## Methods

- `FilterType get_type()`

- `Void set_selected(Boolean)`

- `Void OnFilterClicked(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeSecretarySkinFilterItemView : MonoBehaviour, IHotfixable
{
	private FilterType _type; // 0x18
	private TwoStateToggle _toggle; // 0x20
	private UIStateFinder m_stateFinder; // 0x28
	private static DelegateBridge __Hotfix0_get_type; // 0x0
	private static DelegateBridge __Hotfix0_set_selected; // 0x8
	private static DelegateBridge __Hotfix0_OnFilterClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public FilterType type { get; }
	public Boolean selected { set; }

	// RVA: 0x283f34c VA: 0x7594e5734c
	public FilterType get_type() { }
	// RVA: 0x283f3b4 VA: 0x7594e573b4
	public Void set_selected(Boolean value) { }
	// RVA: 0x283f87c VA: 0x7594e5787c
	public Void OnFilterClicked(Boolean selected) { }
	// RVA: 0x283f994 VA: 0x7594e57994
	public Void .ctor() { }
}
```