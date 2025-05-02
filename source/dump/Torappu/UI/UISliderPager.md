# UISliderPager

**Namespace:** `Torappu.UI`


## Fields

- `UIWrappedSlider _slider`

- `Single _alignDuration`

- `State m_state`

- `Single m_pageUpdatingCacheValue`

- `InitOptions m_options`

- `Int32 m_currentPage`

- `SmoothStep m_alignTween`

- `InvokeWhenUnlock m_startUpdateWhenInited`

- `ScrollEffectTrigger m_effectTrigger`

- `Int32 <pageCount>k__BackingField`


## Properties

- `State currentState`

- `Int32 pageCount`

- `Int32 currentPage`


## Methods

- `Void OnEnable()`

- `Void OnDisable()`

- `Void UpdateTime(Single)`

- `State get_currentState()`

- `Boolean IsAutoPaging()`

- `Int32 get_pageCount()`

- `Void set_pageCount(Int32)`

- `Int32 get_currentPage()`

- `Void set_currentPage(Int32)`

- `Single GetDisplayPageIndex()`

- `Void MoveToPage(Int32)`

- `Void Init(InitOptions)`

- `Void SetScrollEffect(ScrollEffectConfig)`

- `Void ChangePageCount(Int32)`

- `Single _Value2PageIndex(Single)`

- `Single _PageIndex2Value(Single)`

- `Int32 _ValueAlignToPage(Single)`

- `Void _SwitchToPage(Int32, Boolean)`

- `Void _AutoAlign()`

- `Void _OnStateChanged(State, State)`

- `Void <OnEnable>b__12_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UISliderPager : MonoBehaviour, IHotfixable, ITimeWatcher
{
	private UIWrappedSlider _slider; // 0x18
	private Single _alignDuration; // 0x20
	private State m_state; // 0x24
	private Single m_pageUpdatingCacheValue; // 0x28
	private InitOptions m_options; // 0x30
	private Int32 m_currentPage; // 0x50
	private SmoothStep m_alignTween; // 0x58
	private InvokeWhenUnlock m_startUpdateWhenInited; // 0x90
	private ScrollEffectTrigger m_effectTrigger; // 0x98
	private Int32 <pageCount>k__BackingField; // 0xa0
	private static DelegateBridge __Hotfix0_OnEnable; // 0x0
	private static DelegateBridge __Hotfix0_OnDisable; // 0x8
	private static DelegateBridge __Hotfix0_UpdateTime; // 0x10
	private static DelegateBridge __Hotfix0_get_currentState; // 0x18
	private static DelegateBridge __Hotfix0_IsAutoPaging; // 0x20
	private static DelegateBridge __Hotfix0_get_pageCount; // 0x28
	private static DelegateBridge __Hotfix0_set_pageCount; // 0x30
	private static DelegateBridge __Hotfix0_get_currentPage; // 0x38
	private static DelegateBridge __Hotfix0_set_currentPage; // 0x40
	private static DelegateBridge __Hotfix0_GetDisplayPageIndex; // 0x48
	private static DelegateBridge __Hotfix0_MoveToPage; // 0x50
	private static DelegateBridge __Hotfix0_Init; // 0x58
	private static DelegateBridge __Hotfix0_SetScrollEffect; // 0x60
	private static DelegateBridge __Hotfix0_ChangePageCount; // 0x68
	private static DelegateBridge __Hotfix0_IsScrollStableState; // 0x70
	private static DelegateBridge __Hotfix0__Value2PageIndex; // 0x78
	private static DelegateBridge __Hotfix0__PageIndex2Value; // 0x80
	private static DelegateBridge __Hotfix0__ValueAlignToPage; // 0x88
	private static DelegateBridge __Hotfix0__SwitchToPage; // 0x90
	private static DelegateBridge __Hotfix0__AutoAlign; // 0x98
	private static DelegateBridge __Hotfix0__OnStateChanged; // 0xa0
	private static DelegateBridge _c__Hotfix0_ctor; // 0xa8

	public State currentState { get; }
	public Int32 pageCount { get; set; }
	public Int32 currentPage { get; set; }

	// RVA: 0x221abf8 VA: 0x7594832bf8
	private Void OnEnable() { }
	// RVA: 0x221ad70 VA: 0x7594832d70
	private Void OnDisable() { }
	// RVA: 0x221ade0 VA: 0x7594832de0
	public Void UpdateTime(Single deltaTime) { }
	// RVA: 0x221b2d4 VA: 0x75948332d4
	public State get_currentState() { }
	// RVA: 0x221b33c VA: 0x759483333c
	public Boolean IsAutoPaging() { }
	// RVA: 0x221b3ac VA: 0x75948333ac
	public Int32 get_pageCount() { }
	// RVA: 0x221b414 VA: 0x7594833414
	private Void set_pageCount(Int32 value) { }
	// RVA: 0x221b490 VA: 0x7594833490
	public Int32 get_currentPage() { }
	// RVA: 0x221b4f8 VA: 0x75948334f8
	public Void set_currentPage(Int32 value) { }
	// RVA: 0x221b810 VA: 0x7594833810
	public Single GetDisplayPageIndex() { }
	// RVA: 0x221b894 VA: 0x7594833894
	public Void MoveToPage(Int32 pageIndex) { }
	// RVA: 0x221b944 VA: 0x7594833944
	public Void Init(InitOptions callbacks) { }
	// RVA: 0x221ba4c VA: 0x7594833a4c
	public Void SetScrollEffect(ScrollEffectConfig config) { }
	// RVA: 0x221bb64 VA: 0x7594833b64
	public Void ChangePageCount(Int32 pageCount) { }
	// RVA: 0x221bc1c VA: 0x7594833c1c
	public static Boolean IsScrollStableState(State state) { }
	// RVA: 0x221b0ac VA: 0x75948330ac
	private Single _Value2PageIndex(Single value) { }
	// RVA: 0x221b14c VA: 0x759483314c
	private Single _PageIndex2Value(Single index) { }
	// RVA: 0x221bc88 VA: 0x7594833c88
	private Int32 _ValueAlignToPage(Single value) { }
	// RVA: 0x221b5a8 VA: 0x75948335a8
	private Void _SwitchToPage(Int32 target, Boolean useTween) { }
	// RVA: 0x221acdc VA: 0x7594832cdc
	private Void _AutoAlign() { }
	// RVA: 0x221b1ec VA: 0x75948331ec
	private Void _OnStateChanged(State from, State to) { }
	// RVA: 0x221bd4c VA: 0x7594833d4c
	public Void .ctor() { }
	// RVA: 0x221beb8 VA: 0x7594833eb8
	private Void <OnEnable>b__12_0() { }
}
```