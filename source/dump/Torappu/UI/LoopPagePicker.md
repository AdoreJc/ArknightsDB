# LoopPagePicker

**Namespace:** `Torappu.UI`


## Fields

- `Single _baseLine`

- `Single _pageWidth`

- `Single _unselectScale`

- `Single _unselectOffset`

- `Single _tweenDur`

- `Boolean _loop`

- `PickerSelectEvent m_onSelectBegin`

- `PickerSelectEvent m_onSelectChanged`

- `PickerTweenEvent m_onSelectTweening`

- `IDataSource m_data`

- `Int32 m_select`

- `Single m_tweenCost`

- `Single m_pageWidth`

- `EasingFunction m_easeFunc`

- `Int32 <tweenFrom>k__BackingField`


## Properties

- `Int32 select`

- `PickerSelectEvent onSelectBegin`

- `PickerSelectEvent onSelectChanged`

- `PickerTweenEvent onSelectTweening`

- `Boolean tweening`

- `Int32 tweenFrom`


## Methods

- `Void Reset(IDataSource, Int32)`

- `Int32 get_select()`

- `Void set_select(Int32)`

- `PickerSelectEvent get_onSelectBegin()`

- `Void set_onSelectBegin(PickerSelectEvent)`

- `PickerSelectEvent get_onSelectChanged()`

- `Void set_onSelectChanged(PickerSelectEvent)`

- `PickerTweenEvent get_onSelectTweening()`

- `Void set_onSelectTweening(PickerTweenEvent)`

- `Boolean get_tweening()`

- `Int32 get_tweenFrom()`

- `Void set_tweenFrom(Int32)`

- `Void MoveToPrePage()`

- `Void MoveToNextPage()`

- `Void _MovePage(Int32)`

- `Void UpdateTime(Single)`

- `Void _SetSelect(Int32)`

- `Void ReflushAll()`

- `Int32 _CalcRealDataIndex(Int32)`

- `Void _UpdateSort()`

- `Vector2 _CalcVector2(Vector2, Vector2, Single)`

- `Vector3 _CalcVector3(Vector3, Vector3, Single)`

- `Void <>xLuaBaseProxy_Start()`

- `Void <>xLuaBaseProxy_OnEnable()`

- `Void <>xLuaBaseProxy_OnDisable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class LoopPagePicker : UIBehaviour, ITimeWatcher, IHotfixable
{
	private Single _baseLine; // 0x18
	private Single _pageWidth; // 0x1c
	private Single _unselectScale; // 0x20
	private Single _unselectOffset; // 0x24
	private Single _tweenDur; // 0x28
	private Boolean _loop; // 0x2c
	public const Int32 BEGIN_PAGE; // 0x0
	public const Int32 END_PAGE; // 0x0
	private const Int32 VIEW_COUNT; // 0x0
	private const Int32 SEAT_FRONT; // 0x0
	private const Int32 SEAT_RIGHT; // 0x0
	private const Int32 SEAT_BEHIND; // 0x0
	private const Int32 SEAT_LEFT; // 0x0
	private static readonly Int32[] FORWARD_MATCH; // 0x0
	private static readonly Int32[] BACKWARD_MATCH; // 0x8
	private const Single TWEEN_OFF; // 0x0
	private PickerSelectEvent m_onSelectBegin; // 0x30
	private PickerSelectEvent m_onSelectChanged; // 0x38
	private PickerTweenEvent m_onSelectTweening; // 0x40
	private IDataSource m_data; // 0x48
	private Int32 m_select; // 0x50
	private SeatProperty[] m_seats; // 0x58
	private List`1 m_sorting; // 0x60
	private Single m_tweenCost; // 0x68
	private Single m_pageWidth; // 0x6c
	private EasingFunction m_easeFunc; // 0x70
	private Int32 <tweenFrom>k__BackingField; // 0x78
	private static DelegateBridge __Hotfix0_Start; // 0x10
	private static DelegateBridge __Hotfix0_Reset; // 0x18
	private static DelegateBridge __Hotfix0_get_select; // 0x20
	private static DelegateBridge __Hotfix0_set_select; // 0x28
	private static DelegateBridge __Hotfix0_get_onSelectBegin; // 0x30
	private static DelegateBridge __Hotfix0_set_onSelectBegin; // 0x38
	private static DelegateBridge __Hotfix0_get_onSelectChanged; // 0x40
	private static DelegateBridge __Hotfix0_set_onSelectChanged; // 0x48
	private static DelegateBridge __Hotfix0_get_onSelectTweening; // 0x50
	private static DelegateBridge __Hotfix0_set_onSelectTweening; // 0x58
	private static DelegateBridge __Hotfix0_get_tweening; // 0x60
	private static DelegateBridge __Hotfix0_get_tweenFrom; // 0x68
	private static DelegateBridge __Hotfix0_set_tweenFrom; // 0x70
	private static DelegateBridge __Hotfix0_MoveToPrePage; // 0x78
	private static DelegateBridge __Hotfix0_MoveToNextPage; // 0x80
	private static DelegateBridge __Hotfix0__MovePage; // 0x88
	private static DelegateBridge __Hotfix0_UpdateTime; // 0x90
	private static DelegateBridge __Hotfix0_OnEnable; // 0x98
	private static DelegateBridge __Hotfix0_OnDisable; // 0xa0
	private static DelegateBridge __Hotfix0__SetSelect; // 0xa8
	private static DelegateBridge __Hotfix0_ReflushAll; // 0xb0
	private static DelegateBridge __Hotfix0__CalcRealDataIndex; // 0xb8
	private static DelegateBridge __Hotfix0__UpdateSort; // 0xc0
	private static DelegateBridge __Hotfix0__CalcVector2; // 0xc8
	private static DelegateBridge __Hotfix0__CalcVector3; // 0xd0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xd8

	public Int32 select { get; set; }
	public PickerSelectEvent onSelectBegin { get; set; }
	public PickerSelectEvent onSelectChanged { get; set; }
	public PickerTweenEvent onSelectTweening { get; set; }
	public Boolean tweening { get; }
	public Int32 tweenFrom { get; set; }

	// RVA: 0x22230c8 VA: 0x759483b0c8
	protected override Void Start() { }
	// RVA: 0x2223154 VA: 0x759483b154
	public Void Reset(IDataSource source, Int32 select) { }
	// RVA: 0x2223ba4 VA: 0x759483bba4
	public Int32 get_select() { }
	// RVA: 0x2223c1c VA: 0x759483bc1c
	public Void set_select(Int32 value) { }
	// RVA: 0x2223d88 VA: 0x759483bd88
	public PickerSelectEvent get_onSelectBegin() { }
	// RVA: 0x2223e00 VA: 0x759483be00
	public Void set_onSelectBegin(PickerSelectEvent value) { }
	// RVA: 0x2223e94 VA: 0x759483be94
	public PickerSelectEvent get_onSelectChanged() { }
	// RVA: 0x2223f0c VA: 0x759483bf0c
	public Void set_onSelectChanged(PickerSelectEvent value) { }
	// RVA: 0x2223fa0 VA: 0x759483bfa0
	public PickerTweenEvent get_onSelectTweening() { }
	// RVA: 0x2224018 VA: 0x759483c018
	public Void set_onSelectTweening(PickerTweenEvent value) { }
	// RVA: 0x22240ac VA: 0x759483c0ac
	public Boolean get_tweening() { }
	// RVA: 0x2224130 VA: 0x759483c130
	public Int32 get_tweenFrom() { }
	// RVA: 0x22241a8 VA: 0x759483c1a8
	private Void set_tweenFrom(Int32 value) { }
	// RVA: 0x2224234 VA: 0x759483c234
	public Void MoveToPrePage() { }
	// RVA: 0x2224814 VA: 0x759483c814
	public Void MoveToNextPage() { }
	// RVA: 0x22242b0 VA: 0x759483c2b0
	private Void _MovePage(Int32 move) { }
	// RVA: 0x2224a8c VA: 0x759483ca8c
	public Void UpdateTime(Single deltaTime) { }
	// RVA: 0x222520c VA: 0x759483d20c
	protected override Void OnEnable() { }
	// RVA: 0x222528c VA: 0x759483d28c
	protected override Void OnDisable() { }
	// RVA: 0x22238bc VA: 0x759483b8bc
	private Void _SetSelect(Int32 select) { }
	// RVA: 0x222530c VA: 0x759483d30c
	public Void ReflushAll() { }
	// RVA: 0x2224890 VA: 0x759483c890
	private Int32 _CalcRealDataIndex(Int32 offset) { }
	// RVA: 0x2225054 VA: 0x759483d054
	private Void _UpdateSort() { }
	// RVA: 0x2224df4 VA: 0x759483cdf4
	private Vector2 _CalcVector2(Vector2 start, Vector2 end, Single v) { }
	// RVA: 0x2224f00 VA: 0x759483cf00
	private Vector3 _CalcVector3(Vector3 start, Vector3 end, Single v) { }
	// RVA: 0x22254a0 VA: 0x759483d4a0
	public Void .ctor() { }
	// RVA: 0x2225674 VA: 0x759483d674
	private static Void .cctor() { }
	// RVA: 0x2225758 VA: 0x759483d758
	private Void <>xLuaBaseProxy_Start() { }
	// RVA: 0x2225760 VA: 0x759483d760
	private Void <>xLuaBaseProxy_OnEnable() { }
	// RVA: 0x2225768 VA: 0x759483d768
	private Void <>xLuaBaseProxy_OnDisable() { }
}
```