# ItemRepoSelectCharRowComp

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `Single _baseHeight`

- `Single _ownTagHeight`

- `Single _potentialTagHeight`

- `SimpleLayoutContent _charContent`

- `GameObject _ownedPanel`

- `GameObject _notOwnedPanel`

- `GameObject _standardPanel`

- `GameObject _classicPanel`

- `Boolean m_hasInited`

- `ItemRepoChooseCharAdapter m_adapter`


## Methods

- `Void _Render(ViewModel)`

- `Void _InitIfNot(ViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoSelectCharRowComp : MonoBehaviour, IHotfixable
{
	private Single _baseHeight; // 0x18
	private Single _ownTagHeight; // 0x1c
	private Single _potentialTagHeight; // 0x20
	private SimpleLayoutContent _charContent; // 0x28
	private GameObject _ownedPanel; // 0x30
	private GameObject _notOwnedPanel; // 0x38
	private GameObject _standardPanel; // 0x40
	private GameObject _classicPanel; // 0x48
	private Boolean m_hasInited; // 0x50
	private ItemRepoChooseCharAdapter m_adapter; // 0x58
	private static DelegateBridge __Hotfix0__Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2d3944c VA: 0x759535144c
	private Void _Render(ViewModel model) { }
	// RVA: 0x2d3958c VA: 0x759535158c
	private Void _InitIfNot(ViewModel model) { }
	// RVA: 0x2d39670 VA: 0x7595351670
	public Void .ctor() { }
}
```