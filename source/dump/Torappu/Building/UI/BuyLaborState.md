# BuyLaborState

**Namespace:** `Torappu.Building.UI`


## Fields

- `BuyLaborStateBean _stateBean`

- `Text _currentCount`

- `Text _downAP`

- `Text _detailText`

- `BuildingUIResItem _laborPriceItem`

- `Boolean m_initFlag`

- `DateTime m_currentTime`


## Methods

- `Void SendCurrentBuy()`

- `Void Render()`

- `Void Add()`

- `Void Minus()`

- `Void MinusToMin()`

- `Void AddToMax()`

- `Void Update()`

- `Void <SendCurrentBuy>b__8_0(BuildingBuyLaborResponse)`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI
public class BuyLaborState : State
{
	private BuyLaborStateBean _stateBean; // 0x50
	private Text _currentCount; // 0x58
	private Text _downAP; // 0x60
	private Text _detailText; // 0x68
	private BuildingUIResItem _laborPriceItem; // 0x70
	private Boolean m_initFlag; // 0x78
	private DateTime m_currentTime; // 0x80
	private static DelegateBridge __Hotfix0_OnEnter; // 0x0
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x8
	private static DelegateBridge __Hotfix0_SendCurrentBuy; // 0x10
	private static DelegateBridge __Hotfix0_Render; // 0x18
	private static DelegateBridge __Hotfix0_Add; // 0x20
	private static DelegateBridge __Hotfix0_Minus; // 0x28
	private static DelegateBridge __Hotfix0_MinusToMin; // 0x30
	private static DelegateBridge __Hotfix0_AddToMax; // 0x38
	private static DelegateBridge __Hotfix0_Update; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x3d2eaf0 VA: 0x7596346af0
	protected override Void OnEnter() { }
	// RVA: 0x3d2eff4 VA: 0x7596346ff4
	public override IStateBean GetCacheBean() { }
	// RVA: 0x3d2f05c VA: 0x759634705c
	public Void SendCurrentBuy() { }
	// RVA: 0x3d2ed8c VA: 0x7596346d8c
	public Void Render() { }
	// RVA: 0x3d2f3f0 VA: 0x75963473f0
	public Void Add() { }
	// RVA: 0x3d2f51c VA: 0x759634751c
	public Void Minus() { }
	// RVA: 0x3d2f5a4 VA: 0x75963475a4
	public Void MinusToMin() { }
	// RVA: 0x3d2f6a0 VA: 0x75963476a0
	public Void AddToMax() { }
	// RVA: 0x3d2f878 VA: 0x7596347878
	private Void Update() { }
	// RVA: 0x3d2f9c8 VA: 0x75963479c8
	public Void .ctor() { }
	// RVA: 0x3d2fa38 VA: 0x7596347a38
	private Void <SendCurrentBuy>b__8_0(BuildingBuyLaborResponse response) { }
	// RVA: 0x3d2fab4 VA: 0x7596347ab4
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```