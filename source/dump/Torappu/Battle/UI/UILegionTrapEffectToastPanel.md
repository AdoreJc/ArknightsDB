# UILegionTrapEffectToastPanel

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Image _trapIcon`

- `Text _trapDesc`

- `Single m_lastTime`


## Methods

- `String _ParseSkillDescription(String, Blackboard)`

- `Void OnDestroy()`

- `Void <>xLuaBaseProxy_OnUpdate()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UILegionTrapEffectToastPanel : UIToastSubPanel
{
	private Image _trapIcon; // 0x28
	private Text _trapDesc; // 0x30
	private Single m_lastTime; // 0x38
	private static DelegateBridge __Hotfix0_OnShow; // 0x0
	private static DelegateBridge __Hotfix0__ParseSkillDescription; // 0x8
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x10
	private static DelegateBridge __Hotfix0_OnUpdate; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2043eb4 VA: 0x759465beb4
	public override Void OnShow(Options options) { }
	// RVA: 0x204408c VA: 0x759465c08c
	private String _ParseSkillDescription(String description, Blackboard blackboard) { }
	// RVA: 0x2044144 VA: 0x759465c144
	private Void OnDestroy() { }
	// RVA: 0x20441bc VA: 0x759465c1bc
	public override Void OnUpdate() { }
	// RVA: 0x2044258 VA: 0x759465c258
	public Void .ctor() { }
	// RVA: 0x20442c4 VA: 0x759465c2c4
	private Void <>xLuaBaseProxy_OnUpdate() { }
}
```