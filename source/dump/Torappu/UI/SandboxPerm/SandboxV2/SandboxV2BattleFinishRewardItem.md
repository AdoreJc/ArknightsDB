# SandboxV2BattleFinishRewardItem

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `SandboxV2ItemCard _itemCard`

- `RectTransform _itemContainer`

- `Single _itemScale`

- `SandboxV2ItemCard m_itemCard`

- `UIItemViewModel m_itemViewModel`


## Methods

- `Void Render(Int32, UIItemViewModel)`

- `Void _EventOnItemClick(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2BattleFinishRewardItem : MonoBehaviour, IHotfixable
{
	private SandboxV2ItemCard _itemCard; // 0x18
	private RectTransform _itemContainer; // 0x20
	private Single _itemScale; // 0x28
	private SandboxV2ItemCard m_itemCard; // 0x30
	private UIItemViewModel m_itemViewModel; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__EventOnItemClick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x24fbea8 VA: 0x7594b13ea8
	public Void Render(Int32 index, UIItemViewModel itemViewModel) { }
	// RVA: 0x24fc0f0 VA: 0x7594b140f0
	private Void _EventOnItemClick(Int32 itemIndex) { }
	// RVA: 0x24fc1e4 VA: 0x7594b141e4
	public Void .ctor() { }
}
```