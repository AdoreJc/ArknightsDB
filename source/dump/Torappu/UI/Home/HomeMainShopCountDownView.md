# HomeMainShopCountDownView

**Namespace:** `Torappu.UI.Home`


## Fields

- `Transform _onTimeContainer`

- `UIItemTimeCountDown _countDown`

- `Single _itemScaler`

- `GameObject _monthlySubWarning`

- `UIItemTimeCountDown m_countDown`

- `Boolean m_initFlag`


## Methods

- `Void _InitIfNot()`

- `Void RefreshState()`

- `Void _OnTimeExceed()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class HomeMainShopCountDownView : MonoBehaviour, IHotfixable
{
	private Transform _onTimeContainer; // 0x18
	private UIItemTimeCountDown _countDown; // 0x20
	private Single _itemScaler; // 0x28
	private GameObject _monthlySubWarning; // 0x30
	private UIItemTimeCountDown m_countDown; // 0x38
	private Boolean m_initFlag; // 0x40
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_RefreshState; // 0x8
	private static DelegateBridge __Hotfix0__OnTimeExceed; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x283c094 VA: 0x7594e54094
	public Void _InitIfNot() { }
	// RVA: 0x283c198 VA: 0x7594e54198
	public Void RefreshState() { }
	// RVA: 0x283c504 VA: 0x7594e54504
	private Void _OnTimeExceed() { }
	// RVA: 0x283c5a4 VA: 0x7594e545a4
	public Void .ctor() { }
}
```