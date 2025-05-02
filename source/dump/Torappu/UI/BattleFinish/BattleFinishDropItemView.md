# BattleFinishDropItemView

**Namespace:** `Torappu.UI.BattleFinish`


## Fields

- `GameObject _firstDropTag`

- `Single _cardScaleFactor`

- `Transform _itemContainer`

- `UIItemCard m_itemCard`

- `Animator m_animator`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `IEnumerator _RenderAfterTime(Single)`

- `Void Render(Int32, Boolean, UIItemViewModel, Single)`

- `Void _PlayItemDropSE()`

- `Void <Render>b__8_0(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BattleFinish
public class BattleFinishDropItemView : MonoBehaviour
{
	private GameObject _firstDropTag; // 0x18
	private Single _cardScaleFactor; // 0x20
	private Transform _itemContainer; // 0x28
	private UIItemCard m_itemCard; // 0x30
	private Animator m_animator; // 0x38
	private Boolean m_isInited; // 0x40


	// RVA: 0x2e8de5c VA: 0x75954a5e5c
	private Void _InitIfNot() { }
	// RVA: 0x2e8e01c VA: 0x75954a601c
	private IEnumerator _RenderAfterTime(Single passTime) { }
	// RVA: 0x2e8d36c VA: 0x75954a536c
	public Void Render(Int32 index, Boolean isFirstDrop, UIItemViewModel itemModel, Single passTime) { }
	// RVA: 0x2e8e0c8 VA: 0x75954a60c8
	private Void _PlayItemDropSE() { }
	// RVA: 0x2e8e134 VA: 0x75954a6134
	public Void .ctor() { }
	// RVA: 0x2e8e13c VA: 0x75954a613c
	private Void <Render>b__8_0(Int32 _) { }
}
```