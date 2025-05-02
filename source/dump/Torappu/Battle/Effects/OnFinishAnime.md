# OnFinishAnime

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `String _triggerName`

- `Boolean _triggerValue`

- `Animator m_animator`

- `Int32 m_property`


## Methods

- `Void <>xLuaBaseProxy_Init(Effect)`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class OnFinishAnime : Behaviour
{
	private String _triggerName; // 0x20
	private Boolean _triggerValue; // 0x28
	private Animator m_animator; // 0x30
	private Int32 m_property; // 0x38
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnFinish; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2001b84 VA: 0x7594619b84
	public override Void Init(Effect effect) { }
	// RVA: 0x2001c8c VA: 0x7594619c8c
	public override Void OnFinish() { }
	// RVA: 0x2001d10 VA: 0x7594619d10
	public Void .ctor() { }
	// RVA: 0x2001db4 VA: 0x7594619db4
	private Void <>xLuaBaseProxy_Init(Effect P0) { }
	// RVA: 0x2001db8 VA: 0x7594619db8
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```