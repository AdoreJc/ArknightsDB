# ShopSocialView

**Namespace:** `Torappu.UI.Shop`


## Fields

- `ShopSocialItemObject _itemObj`

- `SimpleLayoutContent _itemContainer`

- `Text _backTime`

- `CountDownTask m_countDownTask`

- `DateTime m_timeLimit`

- `SpriteHub m_priceTypeHub`

- `Adapter m_adapter`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void RenderView(List`1, SpriteHub)`

- `Void _RenderCountDownValue()`

- `Void Update()`

- `Void <RenderView>b__11_0(TickValue)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class ShopSocialView : MonoBehaviour
{
	private ShopSocialItemObject _itemObj; // 0x18
	private SimpleLayoutContent _itemContainer; // 0x20
	private Text _backTime; // 0x28
	private CountDownTask m_countDownTask; // 0x30
	private DateTime m_timeLimit; // 0x38
	private List`1 m_itemObjList; // 0x40
	private SpriteHub m_priceTypeHub; // 0x48
	private Adapter m_adapter; // 0x50
	private Boolean m_isInited; // 0x58


	// RVA: 0x246ea6c VA: 0x7594a86a6c
	private Void _InitIfNot() { }
	// RVA: 0x246e358 VA: 0x7594a86358
	public Void RenderView(List`1 itemObjList, SpriteHub priceTypeHub) { }
	// RVA: 0x246eb98 VA: 0x7594a86b98
	private Void _RenderCountDownValue() { }
	// RVA: 0x246ed7c VA: 0x7594a86d7c
	private Void Update() { }
	// RVA: 0x246ed90 VA: 0x7594a86d90
	public Void .ctor() { }
	// RVA: 0x246ed98 VA: 0x7594a86d98
	private Void <RenderView>b__11_0(TickValue _) { }
}
```