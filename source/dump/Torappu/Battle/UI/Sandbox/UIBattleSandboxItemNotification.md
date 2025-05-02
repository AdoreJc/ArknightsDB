# UIBattleSandboxItemNotification

**Namespace:** `Torappu.Battle.UI.Sandbox`


## Fields

- `Transform _contentList`

- `Vector2 _spacing`

- `GameObject _viewPrefab`

- `Single _speed`


## Methods

- `Void Update()`

- `Void _Roll()`

- `Void InsertItemView(String, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.Sandbox
public class UIBattleSandboxItemNotification : MonoBehaviour, IHotfixable
{
	private Transform _contentList; // 0x18
	private Vector2 _spacing; // 0x20
	private GameObject _viewPrefab; // 0x28
	private Single _speed; // 0x30
	private List`1 m_itemViews; // 0x38
	private static DelegateBridge __Hotfix0_get_itemViews; // 0x0
	private static DelegateBridge __Hotfix0_Update; // 0x8
	private static DelegateBridge __Hotfix0__Roll; // 0x10
	private static DelegateBridge __Hotfix0_InsertItemView; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public List`1 itemViews { get; }

	// RVA: 0x209a85c VA: 0x75946b285c
	public List`1 get_itemViews() { }
	// RVA: 0x209a8c4 VA: 0x75946b28c4
	private Void Update() { }
	// RVA: 0x209a92c VA: 0x75946b292c
	private Void _Roll() { }
	// RVA: 0x209abc0 VA: 0x75946b2bc0
	public Void InsertItemView(String itemId, Int32 count) { }
	// RVA: 0x209ae6c VA: 0x75946b2e6c
	public Void .ctor() { }
}
```