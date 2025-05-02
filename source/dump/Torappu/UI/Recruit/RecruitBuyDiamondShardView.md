# RecruitBuyDiamondShardView

**Namespace:** `Torappu.UI.Recruit`


## Fields

- `Text _soldText`

- `UIBlurFloatPanel _backImage`

- `UIItemCard _itemPrefab`

- `Transform _itemContainer1`

- `Transform _itemContainer2`

- `Single _itemScale`

- `String inputPoolId`

- `Int32 m_cacheDiamond`

- `UIItemCard m_costItem`

- `UIItemCard m_targetItem`

- `UIItemViewModel m_costModel`

- `UIItemViewModel m_targetModel`

- `Boolean m_initFlag`


## Methods

- `Void _Init()`

- `Void SendDiamondExchangeService()`

- `Void _OnExchangeResponseSuccess(ExchangeDiamondShardResponse)`

- `Void Dismiss()`

- `Void ApplyData(Int32)`

- `Void <_Init>b__14_0(Int32)`

- `Void <_Init>b__14_1(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Recruit
public class RecruitBuyDiamondShardView : PageSingleComponent
{
	private Text _soldText; // 0x20
	private UIBlurFloatPanel _backImage; // 0x28
	private UIItemCard _itemPrefab; // 0x30
	private Transform _itemContainer1; // 0x38
	private Transform _itemContainer2; // 0x40
	private Single _itemScale; // 0x48
	public Action`1 action; // 0x50
	public String inputPoolId; // 0x58
	private Int32 m_cacheDiamond; // 0x60
	private UIItemCard m_costItem; // 0x68
	private UIItemCard m_targetItem; // 0x70
	private UIItemViewModel m_costModel; // 0x78
	private UIItemViewModel m_targetModel; // 0x80
	private Boolean m_initFlag; // 0x88
	private static DelegateBridge __Hotfix0__Init; // 0x0
	private static DelegateBridge __Hotfix0_ApplyDataStatic; // 0x8
	private static DelegateBridge __Hotfix0_SendDiamondExchangeService; // 0x10
	private static DelegateBridge __Hotfix0__OnExchangeResponseSuccess; // 0x18
	private static DelegateBridge __Hotfix0_Dismiss; // 0x20
	private static DelegateBridge __Hotfix0_ApplyData; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x2707e14 VA: 0x7594d1fe14
	private Void _Init() { }
	// RVA: 0x27081ec VA: 0x7594d201ec
	public static Void ApplyDataStatic(Int32 needDS, Action`1 gachaEvent, String inputPoolId) { }
	// RVA: 0x27086a0 VA: 0x7594d206a0
	public Void SendDiamondExchangeService() { }
	// RVA: 0x2708974 VA: 0x7594d20974
	private Void _OnExchangeResponseSuccess(ExchangeDiamondShardResponse response) { }
	// RVA: 0x27088e0 VA: 0x7594d208e0
	public Void Dismiss() { }
	// RVA: 0x2708308 VA: 0x7594d20308
	public Void ApplyData(Int32 needDS) { }
	// RVA: 0x2708a20 VA: 0x7594d20a20
	public Void .ctor() { }
	// RVA: 0x2708af8 VA: 0x7594d20af8
	private Void <_Init>b__14_0(Int32 _) { }
	// RVA: 0x2708b30 VA: 0x7594d20b30
	private Void <_Init>b__14_1(Int32 _) { }
}
```