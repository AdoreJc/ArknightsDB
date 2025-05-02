# UIBackPressListener

**Namespace:** `Torappu.UI.BackPress`


## Fields

- `RectTransform m_rectTrans`

- `Canvas m_rootCanvas`

- `BackPressOptions m_options`


## Methods

- `Void Start()`

- `Void OnEnable()`

- `Void OnDestroy()`

- `Void ManagerOnlySetOptions(BackPressOptions)`

- `Boolean ManagerOnlyConsumeBackPress()`

- `Boolean _CheckIfToConsume()`

- `Boolean _BreakWhenOtherListener(Transform)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BackPress
public class UIBackPressListener : MonoBehaviour, IHotfixable
{
	private RectTransform m_rectTrans; // 0x18
	private Canvas m_rootCanvas; // 0x20
	private BackPressOptions m_options; // 0x28
	private List`1 m_raycastResults; // 0x48
	private static DelegateBridge __Hotfix0_Start; // 0x0
	private static DelegateBridge __Hotfix0_OnEnable; // 0x8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x10
	private static DelegateBridge __Hotfix0_ManagerOnlySetOptions; // 0x18
	private static DelegateBridge __Hotfix0_ManagerOnlyConsumeBackPress; // 0x20
	private static DelegateBridge __Hotfix0__CheckIfToConsume; // 0x28
	private static DelegateBridge __Hotfix0__BreakWhenOtherListener; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x2c5f490 VA: 0x7595277490
	private Void Start() { }
	// RVA: 0x2c5f60c VA: 0x759527760c
	private Void OnEnable() { }
	// RVA: 0x2c5f6b0 VA: 0x75952776b0
	private Void OnDestroy() { }
	// RVA: 0x2c5f740 VA: 0x7595277740
	public Void ManagerOnlySetOptions(BackPressOptions options) { }
	// RVA: 0x2c5f7e4 VA: 0x75952777e4
	public Boolean ManagerOnlyConsumeBackPress() { }
	// RVA: 0x2c5f878 VA: 0x7595277878
	private Boolean _CheckIfToConsume() { }
	// RVA: 0x2c5f9f0 VA: 0x75952779f0
	private Boolean _BreakWhenOtherListener(Transform target) { }
	// RVA: 0x2c5fb10 VA: 0x7595277b10
	public Void .ctor() { }
}
```