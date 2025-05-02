# HandBookButtonTab

**Namespace:** `Torappu.UI.HandBook`


## Fields

- `HandBookInfoView _parentView`

- `Int32 _initPos`

- `Animator _tabState`

- `TwoStateToggle _availToggle`

- `Single m_currentPos`

- `UIStateFinder m_finder`

- `Boolean m_isFast`

- `Tween m_posTween`


## Properties

- `Int32 m_state`

- `Boolean isFast`

- `Int32 m_posID`


## Methods

- `Void set_m_state(Int32)`

- `Boolean get_isFast()`

- `Void set_isFast(Boolean)`

- `Void set_m_posID(Int32)`

- `Void OnEnable()`

- `Void onState(Int32)`

- `Void onClick()`

- `Single <set_m_posID>b__15_0()`

- `Void <set_m_posID>b__15_1(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.HandBook
public class HandBookButtonTab : MonoBehaviour, IHotfixable
{
	private HandBookInfoView _parentView; // 0x18
	private Int32 _initPos; // 0x20
	private Animator _tabState; // 0x28
	private TwoStateToggle _availToggle; // 0x30
	private Single m_currentPos; // 0x38
	private const String ISFAST_PARAM; // 0x0
	private UIStateFinder m_finder; // 0x40
	private Boolean m_isFast; // 0x50
	private Tween m_posTween; // 0x58
	private static DelegateBridge __Hotfix0_set_m_state; // 0x0
	private static DelegateBridge __Hotfix0_get_isFast; // 0x8
	private static DelegateBridge __Hotfix0_set_isFast; // 0x10
	private static DelegateBridge __Hotfix0_set_m_posID; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge __Hotfix0_OnEnable; // 0x28
	private static DelegateBridge __Hotfix0_onState; // 0x30
	private static DelegateBridge __Hotfix0_onClick; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40

	private Int32 m_state { set; }
	public Boolean isFast { get; set; }
	private Int32 m_posID { set; }

	// RVA: 0x2ea9b44 VA: 0x75954c1b44
	private Void set_m_state(Int32 value) { }
	// RVA: 0x2ea9be8 VA: 0x75954c1be8
	public Boolean get_isFast() { }
	// RVA: 0x2ea9c50 VA: 0x75954c1c50
	public Void set_isFast(Boolean value) { }
	// RVA: 0x2ea9cfc VA: 0x75954c1cfc
	private Void set_m_posID(Int32 value) { }
	// RVA: 0x2ea8eb0 VA: 0x75954c0eb0
	public virtual Void Render(HandBookInfoViewModel viewModel) { }
	// RVA: 0x2ea9ec0 VA: 0x75954c1ec0
	private Void OnEnable() { }
	// RVA: 0x2ea9f58 VA: 0x75954c1f58
	public Void onState(Int32 selectedID) { }
	// RVA: 0x2eaa02c VA: 0x75954c202c
	public Void onClick() { }
	// RVA: 0x2ea8f94 VA: 0x75954c0f94
	public Void .ctor() { }
	// RVA: 0x2eaa10c VA: 0x75954c210c
	private Single <set_m_posID>b__15_0() { }
	// RVA: 0x2eaa114 VA: 0x75954c2114
	private Void <set_m_posID>b__15_1(Single val) { }
}
```