# UICharacterStarMarkTopSortItem

**Namespace:** `Torappu.UI`


## Fields

- `UIAnimationLocation _starMarkEditBtnAnim`

- `Boolean m_isInited`

- `TwoStateToggle m_twoStateToggle`

- `Action m_eventStarMarkTopSortClick`

- `Action m_eventEnterEditModeClick`

- `Boolean m_cachedStarMarkTop`

- `AnimationSwitchTween m_editBtnSwitchTween`


## Properties

- `Action eventOnStarMarkTopClick`

- `Action eventOnEnterEditMode`


## Methods

- `Void Render(Boolean)`

- `Void set_eventOnStarMarkTopClick(Action)`

- `Void set_eventOnEnterEditMode(Action)`

- `Void EventOnEnterEditMode()`

- `Void _InitIfNot()`

- `Void _OnToggle(State)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharacterStarMarkTopSortItem : MonoBehaviour, IHotfixable
{
	private UIAnimationLocation _starMarkEditBtnAnim; // 0x18
	private Boolean m_isInited; // 0x28
	private TwoStateToggle m_twoStateToggle; // 0x30
	private Action m_eventStarMarkTopSortClick; // 0x38
	private Action m_eventEnterEditModeClick; // 0x40
	private Boolean m_cachedStarMarkTop; // 0x48
	private AnimationSwitchTween m_editBtnSwitchTween; // 0x50
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_set_eventOnStarMarkTopClick; // 0x8
	private static DelegateBridge __Hotfix0_set_eventOnEnterEditMode; // 0x10
	private static DelegateBridge __Hotfix0_EventOnEnterEditMode; // 0x18
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x20
	private static DelegateBridge __Hotfix0__OnToggle; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public Action eventOnStarMarkTopClick { set; }
	public Action eventOnEnterEditMode { set; }

	// RVA: 0x2136ddc VA: 0x759474eddc
	public Void Render(Boolean isStarMarkTop) { }
	// RVA: 0x2136bac VA: 0x759474ebac
	public Void set_eventOnStarMarkTopClick(Action value) { }
	// RVA: 0x2136c30 VA: 0x759474ec30
	public Void set_eventOnEnterEditMode(Action value) { }
	// RVA: 0x21370fc VA: 0x759474f0fc
	public Void EventOnEnterEditMode() { }
	// RVA: 0x2136f4c VA: 0x759474ef4c
	private Void _InitIfNot() { }
	// RVA: 0x2137188 VA: 0x759474f188
	private Void _OnToggle(State state) { }
	// RVA: 0x2137224 VA: 0x759474f224
	public Void .ctor() { }
}
```