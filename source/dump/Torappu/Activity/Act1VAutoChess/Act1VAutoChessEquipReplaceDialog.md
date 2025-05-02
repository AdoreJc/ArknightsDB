# Act1VAutoChessEquipReplaceDialog

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Act1VAutoChessEquipReplaceView _view`

- `UIAnimationLocation _showAnimation`

- `AnimationWrapper m_showWrapper`

- `Tween m_showTween`


## Methods

- `Void OnBackEvent()`

- `Void _OnSelectEvent(Int32)`

- `Void _OnConfirmEvent(Int32)`

- `Void <>xLuaBaseProxy_OnInit()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessEquipReplaceDialog : UICompDialog`1
{
	private Act1VAutoChessEquipReplaceView _view; // 0x48
	private UIAnimationLocation _showAnimation; // 0x50
	private readonly Act1VAutoChessEquipReplaceProperty m_prop; // 0x60
	private AnimationWrapper m_showWrapper; // 0x68
	private Tween m_showTween; // 0x70
	private static DelegateBridge __Hotfix0_OnBackEvent; // 0x0
	private static DelegateBridge __Hotfix0_OnInit; // 0x8
	private static DelegateBridge __Hotfix0_OnRender; // 0x10
	private static DelegateBridge __Hotfix0__OnSelectEvent; // 0x18
	private static DelegateBridge __Hotfix0__OnConfirmEvent; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x336e040 VA: 0x7595986040
	public Void OnBackEvent() { }
	// RVA: 0x336e128 VA: 0x7595986128
	protected override Void OnInit() { }
	// RVA: 0x336e2b0 VA: 0x75959862b0
	protected override Void OnRender(Input input) { }
	// RVA: 0x336e4a4 VA: 0x75959864a4
	private Void _OnSelectEvent(Int32 index) { }
	// RVA: 0x336e590 VA: 0x7595986590
	private Void _OnConfirmEvent(Int32 index) { }
	// RVA: 0x336e700 VA: 0x7595986700
	public Void .ctor() { }
	// RVA: 0x336e7d0 VA: 0x75959867d0
	private Void <>xLuaBaseProxy_OnInit() { }
}
```