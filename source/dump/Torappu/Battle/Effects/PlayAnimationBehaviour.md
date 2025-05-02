# PlayAnimationBehaviour

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `String _onPlayAnim`

- `String _onFinishAnim`

- `Boolean _disableFinishAnimWhenOwnerAlive`

- `Boolean _finishWhenOwnerFinish`

- `String _finishWhenNotContaionsBuff`

- `Animation m_animation`

- `Boolean m_started`


## Methods

- `Void Update()`

- `Void Awake()`

- `Void <>xLuaBaseProxy_Init(Effect)`

- `Void <>xLuaBaseProxy_OnPlay()`

- `Void <>xLuaBaseProxy_OnFinish()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class PlayAnimationBehaviour : Behaviour
{
	private String _onPlayAnim; // 0x20
	private String _onFinishAnim; // 0x28
	private Boolean _disableFinishAnimWhenOwnerAlive; // 0x30
	private Boolean _finishWhenOwnerFinish; // 0x31
	private String _finishWhenNotContaionsBuff; // 0x38
	private Animation m_animation; // 0x40
	private Boolean m_started; // 0x48
	private static DelegateBridge __Hotfix0_Update; // 0x0
	private static DelegateBridge __Hotfix0_Awake; // 0x8
	private static DelegateBridge __Hotfix0_Init; // 0x10
	private static DelegateBridge __Hotfix0_OnPlay; // 0x18
	private static DelegateBridge __Hotfix0_OnFinish; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x20067cc VA: 0x759461e7cc
	private Void Update() { }
	// RVA: 0x2006974 VA: 0x759461e974
	private Void Awake() { }
	// RVA: 0x2006a14 VA: 0x759461ea14
	public override Void Init(Effect effect) { }
	// RVA: 0x2006b0c VA: 0x759461eb0c
	public override Void OnPlay() { }
	// RVA: 0x2006bec VA: 0x759461ebec
	public override Void OnFinish() { }
	// RVA: 0x2006cf4 VA: 0x759461ecf4
	public Void .ctor() { }
	// RVA: 0x2006da0 VA: 0x759461eda0
	private Void <>xLuaBaseProxy_Init(Effect P0) { }
	// RVA: 0x2006da4 VA: 0x759461eda4
	private Void <>xLuaBaseProxy_OnPlay() { }
	// RVA: 0x2006da8 VA: 0x759461eda8
	private Void <>xLuaBaseProxy_OnFinish() { }
}
```