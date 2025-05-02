# QCShopLMTGSView

**Namespace:** `Torappu.UI.Shop`


## Fields

- `SimpleLayoutContent _content`

- `Text _endTime`

- `Adapter m_adapter`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void OnEnter(ShopPage)`

- `Void <OnEnter>b__6_0(GetLMTGSGoodListResponse, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class QCShopLMTGSView : MonoBehaviour, IHotfixable
{
	private SimpleLayoutContent _content; // 0x18
	private Text _endTime; // 0x20
	private Adapter m_adapter; // 0x28
	private Boolean m_isInited; // 0x30
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_OnEnter; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2456780 VA: 0x7594a6e780
	private Void _InitIfNot() { }
	// RVA: 0x2451828 VA: 0x7594a69828
	public Void OnEnter(ShopPage page) { }
	// RVA: 0x24568bc VA: 0x7594a6e8bc
	public Void .ctor() { }
	// RVA: 0x245692c VA: 0x7594a6e92c
	private Void <OnEnter>b__6_0(GetLMTGSGoodListResponse response, Boolean isDataUpdated) { }
}
```