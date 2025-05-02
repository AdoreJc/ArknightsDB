# QCShopLowView

**Namespace:** `Torappu.UI.Shop`


## Fields

- `QCShopLowViewModel _viewModel`

- `Text _backDownTime`

- `CountDownTask m_countDownTask`

- `DateTime m_timeLimit`


## Methods

- `Void OnEnter(ShopPage)`

- `Void _RenderCountDownValue()`

- `Void ApplyData(GetLowGoodListResponse)`

- `Void ApplyCurrentGroup(Int32)`

- `Void _ApplyGroupWithIndex(Int32)`

- `Void Update()`

- `Void <OnEnter>b__6_0(GetLowGoodListResponse, Boolean)`

- `Void <OnEnter>b__6_1(TickValue)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Shop
public class QCShopLowView : MonoBehaviour, IHotfixable
{
	private QCShopLowViewModel _viewModel; // 0x18
	private List`1 _groupList; // 0x20
	private List`1 _buttonList; // 0x28
	private Text _backDownTime; // 0x30
	private CountDownTask m_countDownTask; // 0x38
	private List`1 _objList; // 0x40
	private DateTime m_timeLimit; // 0x48
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0__RenderCountDownValue; // 0x8
	private static DelegateBridge __Hotfix0_ApplyData; // 0x10
	private static DelegateBridge __Hotfix0_ApplyCurrentGroup; // 0x18
	private static DelegateBridge __Hotfix0__ApplyGroupWithIndex; // 0x20
	private static DelegateBridge __Hotfix0_Update; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x24511a4 VA: 0x7594a691a4
	public Void OnEnter(ShopPage page) { }
	// RVA: 0x24571e0 VA: 0x7594a6f1e0
	public Void _RenderCountDownValue() { }
	// RVA: 0x2457648 VA: 0x7594a6f648
	public Void ApplyData(GetLowGoodListResponse response) { }
	// RVA: 0x24581ec VA: 0x7594a701ec
	public Void ApplyCurrentGroup(Int32 index) { }
	// RVA: 0x245826c VA: 0x7594a7026c
	private Void _ApplyGroupWithIndex(Int32 index) { }
	// RVA: 0x24583b0 VA: 0x7594a703b0
	private Void Update() { }
	// RVA: 0x245842c VA: 0x7594a7042c
	public Void .ctor() { }
	// RVA: 0x245849c VA: 0x7594a7049c
	private Void <OnEnter>b__6_0(GetLowGoodListResponse response, Boolean isDataUpdated) { }
	// RVA: 0x2458674 VA: 0x7594a70674
	private Void <OnEnter>b__6_1(TickValue _) { }
}
```