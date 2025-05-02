# UpdateMeshOffset

**Namespace:** `Torappu.Battle`


## Fields

- `Single _maxOpenSpeed`

- `Single _maxCloseSpeed`

- `Boolean _onlyTickWhenAlive`

- `AnimationCurve _offsetCurve`

- `Single _axisValue`

- `Single _lastValue`

- `Single m_maxOpenSpeed`

- `Single m_maxCloseSpeed`

- `MeshAnimator m_meshAnimator`


## Methods

- `Void <>xLuaBaseProxy_Init(UnitAnimator)`

- `Void <>xLuaBaseProxy_OnTick(FP)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle
public class UpdateMeshOffset : Behaviour
{
	private List`1 _meshList; // 0x20
	private List`1 _maxOffset; // 0x28
	private Single _maxOpenSpeed; // 0x30
	private Single _maxCloseSpeed; // 0x34
	private Boolean _onlyTickWhenAlive; // 0x38
	private AnimationCurve _offsetCurve; // 0x40
	private Single _axisValue; // 0x48
	private Single _lastValue; // 0x4c
	private readonly Dictionary`2 _originalLocalPosition; // 0x50
	private Single m_maxOpenSpeed; // 0x58
	private Single m_maxCloseSpeed; // 0x5c
	private MeshAnimator m_meshAnimator; // 0x60
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnTick; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x3f2a78c VA: 0x759654278c
	public override Void Init(UnitAnimator unitAnimator) { }
	// RVA: 0x3f2ab18 VA: 0x7596542b18
	public override Void OnTick(FP deltaTime) { }
	// RVA: 0x3f2af88 VA: 0x7596542f88
	public Void .ctor() { }
	// RVA: 0x3f2b10c VA: 0x759654310c
	private Void <>xLuaBaseProxy_Init(UnitAnimator P0) { }
	// RVA: 0x3f2b114 VA: 0x7596543114
	private Void <>xLuaBaseProxy_OnTick(FP P0) { }
}
```