# UIBattleSandboxV2ResItem

**Namespace:** `Torappu.Battle.UI.Sandbox`


## Fields

- `SandboxV2ItemCard _itemCard`

- `Transform _itemCardRoot`

- `Single _scale`

- `Boolean m_inited`

- `SandboxV2ItemCard m_itemCard`


## Methods

- `Void Render(Int32, UIItemViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Sandbox
public class UIBattleSandboxV2ResItem : MonoBehaviour, IHotfixable
{
	private SandboxV2ItemCard _itemCard; // 0x18
	private Transform _itemCardRoot; // 0x20
	private Single _scale; // 0x28
	private Boolean m_inited; // 0x2c
	private SandboxV2ItemCard m_itemCard; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x20c4744 VA: 0x75946dc744
	public Void Render(Int32 idx, UIItemViewModel itemViewModel) { }
	// RVA: 0x20c47e4 VA: 0x75946dc7e4
	private Void _InitIfNot() { }
	// RVA: 0x20c4970 VA: 0x75946dc970
	public Void .ctor() { }
}
```