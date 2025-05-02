# Act1VAutoChessCharSelectFilterItem

**Namespace:** `Torappu.Activity.Act1VAutoChess.CharSelect`


## Fields

- `ProfessionCategory _filter`

- `TwoStateToggle m_toggle`

- `ProfessionCategory m_filter`


## Methods

- `Void add_onItemClick(Action`1)`

- `Void remove_onItemClick(Action`1)`

- `Void Render(ProfessionCategory)`

- `Void _InitIfNot()`

- `Void EventOnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess.CharSelect
public class Act1VAutoChessCharSelectFilterItem : MonoBehaviour, IHotfixable
{
	private ProfessionCategory _filter; // 0x18
	private TwoStateToggle m_toggle; // 0x20
	private ProfessionCategory m_filter; // 0x28
	private Action`1 onItemClick; // 0x30
	private static DelegateBridge __Hotfix0_add_onItemClick; // 0x0
	private static DelegateBridge __Hotfix0_remove_onItemClick; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge __Hotfix0_EventOnClick; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x338b504 VA: 0x75959a3504
	public Void add_onItemClick(Action`1 value) { }
	// RVA: 0x338b5f8 VA: 0x75959a35f8
	public Void remove_onItemClick(Action`1 value) { }
	// RVA: 0x338b6ec VA: 0x75959a36ec
	public Void Render(ProfessionCategory filter) { }
	// RVA: 0x338b788 VA: 0x75959a3788
	private Void _InitIfNot() { }
	// RVA: 0x338b86c VA: 0x75959a386c
	public Void EventOnClick() { }
	// RVA: 0x338b8f0 VA: 0x75959a38f0
	public Void .ctor() { }
}
```