# ItemRepoCardGroupAdapter

**Namespace:** `Torappu.UI.ItemRepo`


## Fields

- `Single _itemCardScaleFactor`

- `LoopHorizontalScrollRect _loopScroll`

- `ClassifyFilter classifyType`


## Methods

- `Void OnDestroy()`

- `Void _OnItemCardClicked(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ItemRepo
public class ItemRepoCardGroupAdapter : LoopScrollAdapter`2, IHotfixable
{
	private Single _itemCardScaleFactor; // 0x54
	private LoopHorizontalScrollRect _loopScroll; // 0x58
	private Dictionary`2 m_activeCards; // 0x60
	public Action`1 onItemCardClick; // 0x68
	public ClassifyFilter classifyType; // 0x70
	private static DelegateBridge __Hotfix0_UpdateView; // 0x0
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x8
	private static DelegateBridge __Hotfix0__OnItemCardClicked; // 0x10
	private static DelegateBridge __Hotfix0_CreateView; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2d2e7f4 VA: 0x75953467f4
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, UIItemViewModel data) { }
	// RVA: 0x2d2eab0 VA: 0x7595346ab0
	protected Void OnDestroy() { }
	// RVA: 0x2d2eb38 VA: 0x7595346b38
	private Void _OnItemCardClicked(Int32 position) { }
	// RVA: 0x2d2ebd8 VA: 0x7595346bd8
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x2d2ecd8 VA: 0x7595346cd8
	public Void .ctor() { }
}
```