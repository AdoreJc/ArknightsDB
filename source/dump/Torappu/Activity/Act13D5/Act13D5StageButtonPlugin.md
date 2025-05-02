# Act13D5StageButtonPlugin

**Namespace:** `Torappu.Activity.Act13D5`


## Fields

- `Single _lineDuration`

- `UIAnimationLocation _showAnim`

- `Single _allDelay`

- `GameObject _pluginObj`

- `GameObject _panelEmpty`

- `Boolean _enableShowEffect`

- `Boolean m_isFirstShow`

- `Boolean m_isEnabled`

- `StageViewModel m_model`

- `CoroutineOnEnable m_displayCoroutine`


## Methods

- `Void _StatusBegin()`

- `Void _StatusEnd()`

- `Boolean _CheckIfTriggerShowEffect()`

- `IEnumerator _DisplayCoroutine()`

- `Void OnEnable()`

- `Void OnDisable()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13D5
public class Act13D5StageButtonPlugin : StageButtonHolderPlugin
{
	private List`1 _lines; // 0x28
	private Single _lineDuration; // 0x30
	private UIAnimationLocation _showAnim; // 0x38
	private Single _allDelay; // 0x48
	private GameObject _pluginObj; // 0x50
	private GameObject _panelEmpty; // 0x58
	private Boolean _enableShowEffect; // 0x60
	private Boolean m_isFirstShow; // 0x61
	private Boolean m_isEnabled; // 0x62
	private StageViewModel m_model; // 0x68
	private CoroutineOnEnable m_displayCoroutine; // 0x70
	private static DelegateBridge __Hotfix0_OnInit; // 0x0
	private static DelegateBridge __Hotfix0_OnRenderStage; // 0x8
	private static DelegateBridge __Hotfix0__StatusBegin; // 0x10
	private static DelegateBridge __Hotfix0__StatusEnd; // 0x18
	private static DelegateBridge __Hotfix0__CheckIfTriggerShowEffect; // 0x20
	private static DelegateBridge __Hotfix0__DisplayCoroutine; // 0x28
	private static DelegateBridge __Hotfix0_OnEnable; // 0x30
	private static DelegateBridge __Hotfix0_OnDisable; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x34486e8 VA: 0x7595a606e8
	protected override Void OnInit() { }
	// RVA: 0x3448760 VA: 0x7595a60760
	protected override Void OnRenderStage(StageViewModel model) { }
	// RVA: 0x3448af0 VA: 0x7595a60af0
	private Void _StatusBegin() { }
	// RVA: 0x34489ec VA: 0x7595a609ec
	private Void _StatusEnd() { }
	// RVA: 0x34488b0 VA: 0x7595a608b0
	private Boolean _CheckIfTriggerShowEffect() { }
	// RVA: 0x3448940 VA: 0x7595a60940
	private IEnumerator _DisplayCoroutine() { }
	// RVA: 0x3448c0c VA: 0x7595a60c0c
	private Void OnEnable() { }
	// RVA: 0x3448d10 VA: 0x7595a60d10
	private Void OnDisable() { }
	// RVA: 0x3448d80 VA: 0x7595a60d80
	public Void .ctor() { }
}
```