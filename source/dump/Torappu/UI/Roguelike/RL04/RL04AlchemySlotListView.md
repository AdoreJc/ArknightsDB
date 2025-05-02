# RL04AlchemySlotListView

**Namespace:** `Torappu.UI.Roguelike.RL04`


## Fields

- `SimpleLayoutContent _slotList`

- `Boolean m_hasInited`

- `SlotListAdapter m_slotListAdapter`


## Methods

- `Void Render(RL04AlchemySlotListViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.RL04
public class RL04AlchemySlotListView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _slotList; // 0x18
	private Boolean m_hasInited; // 0x20
	private SlotListAdapter m_slotListAdapter; // 0x28
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2b0a604 VA: 0x7595122604
	public Void Render(RL04AlchemySlotListViewModel slotListViewModel) { }
	// RVA: 0x2b0d3e4 VA: 0x75951253e4
	private Void _InitIfNot() { }
	// RVA: 0x2b0d5cc VA: 0x75951255cc
	public Void .ctor() { }
}
```