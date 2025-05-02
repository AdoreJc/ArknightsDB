# Act20sideLoopItemContainerView

**Namespace:** `Torappu.Activity.Act20side`


## Fields

- `RectTransform _content`

- `RectTransform _viewport`

- `ScrollRect _scrollView`

- `Act20sideLoopItemGridView _item`


## Methods

- `Void Init(Act20sideMilestoneStateBean)`

- `Act20sideLoopItemGridView AddItem(RectTransform, Int32)`

- `Int32 _GetElementNumPerRow()`

- `Sprite _GetItemSprite(Int32)`

- `Void RefreshItem()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act20side
public class Act20sideLoopItemContainerView : MonoBehaviour, IHotfixable
{
	private const Single LOOP_SPEED; // 0x0
	private RectTransform _content; // 0x18
	private RectTransform _viewport; // 0x20
	private ScrollRect _scrollView; // 0x28
	private Act20sideLoopItemGridView _item; // 0x30
	private Dictionary`2 m_itemIdTable; // 0x38
	private List`1 m_itemIdList; // 0x40
	private const Int32 ROW_NUM; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_AddItem; // 0x8
	private static DelegateBridge __Hotfix0__GetElementNumPerRow; // 0x10
	private static DelegateBridge __Hotfix0__GetItemSprite; // 0x18
	private static DelegateBridge __Hotfix0_RefreshItem; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x32e911c VA: 0x759590111c
	public Void Init(Act20sideMilestoneStateBean stateBean) { }
	// RVA: 0x32e9254 VA: 0x7595901254
	private Act20sideLoopItemGridView AddItem(RectTransform rect, Int32 index) { }
	// RVA: 0x32e94b8 VA: 0x75959014b8
	private Int32 _GetElementNumPerRow() { }
	// RVA: 0x32e9354 VA: 0x7595901354
	private Sprite _GetItemSprite(Int32 index) { }
	// RVA: 0x32e962c VA: 0x759590162c
	public Void RefreshItem() { }
	// RVA: 0x32e9690 VA: 0x7595901690
	public Void .ctor() { }
}
```