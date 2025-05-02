# ActMultiV3AlbumRewardItemView

**Namespace:** `Torappu.Activity.ActMultiV3`


## Fields

- `Single _itemCardScale`

- `Color _itemCardNormalColor`

- `Color _itemCardRecievedColor`

- `RectTransform _itemCardRoot`

- `GameObject _recievedMaskGo`

- `UIItemCard m_itemCard`

- `Boolean m_inited`


## Methods

- `Void Render(ItemBundle, Int32, Boolean)`

- `Void _InitIfNot()`

- `Void _EventOnItemClicked(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.ActMultiV3
public class ActMultiV3AlbumRewardItemView : MonoBehaviour, IHotfixable
{
	private Single _itemCardScale; // 0x18
	private Color _itemCardNormalColor; // 0x1c
	private Color _itemCardRecievedColor; // 0x2c
	private RectTransform _itemCardRoot; // 0x40
	private GameObject _recievedMaskGo; // 0x48
	private UIItemCard m_itemCard; // 0x50
	private Boolean m_inited; // 0x58
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__EventOnItemClicked; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x3118934 VA: 0x7595730934
	public Void Render(ItemBundle item, Int32 position, Boolean hasRecieved) { }
	// RVA: 0x3118a90 VA: 0x7595730a90
	private Void _InitIfNot() { }
	// RVA: 0x3118cb4 VA: 0x7595730cb4
	private Void _EventOnItemClicked(Int32 index) { }
	// RVA: 0x3118db8 VA: 0x7595730db8
	public Void .ctor() { }
}
```