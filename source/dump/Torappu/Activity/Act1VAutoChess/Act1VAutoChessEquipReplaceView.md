# Act1VAutoChessEquipReplaceView

**Namespace:** `Torappu.Activity.Act1VAutoChess`


## Fields

- `Text _mainDescText`


## Methods

- `Void set_selectEvent(Action`1)`

- `Void set_confirmEvent(Action`1)`

- `Void _OnSelectEvent(Int32)`

- `Void _OnConfirmEvent(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act1VAutoChess
public class Act1VAutoChessEquipReplaceView : DataBinder`1
{
	private Text _mainDescText; // 0x20
	private List`1 _equipItems; // 0x28
	private Action`1 <selectEvent>k__BackingField; // 0x30
	private Action`1 <confirmEvent>k__BackingField; // 0x38
	private static DelegateBridge __Hotfix0_get_selectEvent; // 0x0
	private static DelegateBridge __Hotfix0_set_selectEvent; // 0x8
	private static DelegateBridge __Hotfix0_get_confirmEvent; // 0x10
	private static DelegateBridge __Hotfix0_set_confirmEvent; // 0x18
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x20
	private static DelegateBridge __Hotfix0__OnSelectEvent; // 0x28
	private static DelegateBridge __Hotfix0__OnConfirmEvent; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	private Action`1 selectEvent { get; set; }
	private Action`1 confirmEvent { get; set; }

	// RVA: 0x336ee90 VA: 0x7595986e90
	private Action`1 get_selectEvent() { }
	// RVA: 0x336eef8 VA: 0x7595986ef8
	public Void set_selectEvent(Action`1 value) { }
	// RVA: 0x336ef7c VA: 0x7595986f7c
	private Action`1 get_confirmEvent() { }
	// RVA: 0x336efe4 VA: 0x7595986fe4
	public Void set_confirmEvent(Action`1 value) { }
	// RVA: 0x336f068 VA: 0x7595987068
	public override Void OnValueChanged(Act1VAutoChessEquipReplaceProperty property) { }
	// RVA: 0x336f494 VA: 0x7595987494
	private Void _OnSelectEvent(Int32 index) { }
	// RVA: 0x336f54c VA: 0x759598754c
	public Void _OnConfirmEvent(Int32 index) { }
	// RVA: 0x336f604 VA: 0x7595987604
	public Void .ctor() { }
}
```