# ActivityFirstShopView

**Namespace:** `Torappu.Activity.Act1`


## Fields

- `ActivityFirstShopObject _shopObj`

- `Transform _shopContainer`

- `UIActShopEvent _stringEvent`

- `Boolean m_isInited`


## Methods

- `Void _InitData(List`1)`

- `Void RenderData(List`1)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1
public class ActivityFirstShopView : MonoBehaviour, IHotfixable
{
	private ActivityFirstShopObject _shopObj; // 0x18
	private Transform _shopContainer; // 0x20
	private UIActShopEvent _stringEvent; // 0x28
	private List`1 m_shopObjList; // 0x30
	private Boolean m_isInited; // 0x38
	private static DelegateBridge __Hotfix0__InitData; // 0x0
	private static DelegateBridge __Hotfix0_RenderData; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x348cd38 VA: 0x7595aa4d38
	private Void _InitData(List`1 shopDataList) { }
	// RVA: 0x348cf80 VA: 0x7595aa4f80
	public Void RenderData(List`1 shopDataList) { }
	// RVA: 0x348d104 VA: 0x7595aa5104
	public Void .ctor() { }
}
```