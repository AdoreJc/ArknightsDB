# StageRetroCoinRuleState

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Text _ruleText`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void <>xLuaBaseProxy_OnEnter()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageRetroCoinRuleState : PopupFloatState
{
	private Text _ruleText; // 0x70
	private Boolean m_isInited; // 0x78
	private static DelegateBridge __Hotfix0_GetCacheBean; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_OnEnter; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2f6fadc VA: 0x7595587adc
	public override IStateBean GetCacheBean() { }
	// RVA: 0x2f6fb40 VA: 0x7595587b40
	private Void _InitIfNot() { }
	// RVA: 0x2f6fc40 VA: 0x7595587c40
	protected override Void OnEnter() { }
	// RVA: 0x2f6ff0c VA: 0x7595587f0c
	public Void .ctor() { }
	// RVA: 0x2f6ff7c VA: 0x7595587f7c
	private Void <>xLuaBaseProxy_OnEnter() { }
}
```