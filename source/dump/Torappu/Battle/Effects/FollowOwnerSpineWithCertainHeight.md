# FollowOwnerSpineWithCertainHeight

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `Boolean _useOffset`

- `Single _offset`

- `Boolean _useYOffsetWithSpineTiltRate`

- `Single m_initUnitTransformZ`


## Properties

- `Boolean useOffset`


## Methods

- `Boolean get_useOffset()`

- `Void Start()`

- `Void Update()`

- `Void _FollowUnitSpine()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class FollowOwnerSpineWithCertainHeight : Behaviour
{
	private Boolean _useOffset; // 0x20
	private Single _offset; // 0x24
	private Boolean _useYOffsetWithSpineTiltRate; // 0x28
	private const Single SQRT_3; // 0x0
	private Single m_initUnitTransformZ; // 0x2c
	private static DelegateBridge __Hotfix0_get_useOffset; // 0x0
	private static DelegateBridge __Hotfix0_Start; // 0x8
	private static DelegateBridge __Hotfix0_Update; // 0x10
	private static DelegateBridge __Hotfix0__FollowUnitSpine; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean useOffset { get; }

	// RVA: 0x1ffd258 VA: 0x7594615258
	public Boolean get_useOffset() { }
	// RVA: 0x1ffd2c0 VA: 0x75946152c0
	private Void Start() { }
	// RVA: 0x1ffd3bc VA: 0x75946153bc
	private Void Update() { }
	// RVA: 0x1ffd464 VA: 0x7594615464
	private Void _FollowUnitSpine() { }
	// RVA: 0x1ffd644 VA: 0x7594615644
	public Void .ctor() { }
}
```