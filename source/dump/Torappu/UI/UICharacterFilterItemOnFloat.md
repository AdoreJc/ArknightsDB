# UICharacterFilterItemOnFloat

**Namespace:** `Torappu.UI`


## Fields

- `CharacterFilterElement _filter`

- `TwoStateToggle m_toggle`

- `Boolean m_isInited`


## Methods

- `Boolean NotifyFilterTypeChanged(List`1)`

- `Void _OnToggleClick(State)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharacterFilterItemOnFloat : MonoBehaviour, IHotfixable
{
	private CharacterFilterElement _filter; // 0x18
	private TwoStateToggle m_toggle; // 0x20
	private Boolean m_isInited; // 0x28
	public Action`2 onFilterChanged; // 0x30
	private static DelegateBridge __Hotfix0_NotifyFilterTypeChanged; // 0x0
	private static DelegateBridge __Hotfix0__OnToggleClick; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x212f474 VA: 0x7594747474
	public Boolean NotifyFilterTypeChanged(List`1 selectedFilters) { }
	// RVA: 0x212fb4c VA: 0x7594747b4c
	private Void _OnToggleClick(State state) { }
	// RVA: 0x212fa38 VA: 0x7594747a38
	private Void _InitIfNot() { }
	// RVA: 0x212fbf4 VA: 0x7594747bf4
	public Void .ctor() { }
}
```