# FinishEffectViaOwnerBuff

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `String _buffId`

- `Boolean _pauseInsteadOfFinish`

- `Boolean _enableIfBuffExistsAgain`

- `Boolean _useBehaviourPause`

- `Boolean _invertPause`


## Properties

- `Boolean pauseInsteadOfFinish`


## Methods

- `Boolean get_pauseInsteadOfFinish()`

- `Void Update()`

- `Void SetPause(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class FinishEffectViaOwnerBuff : Behaviour, IHotfixable
{
	private String _buffId; // 0x20
	private Boolean _pauseInsteadOfFinish; // 0x28
	private Boolean _enableIfBuffExistsAgain; // 0x29
	private Boolean _useBehaviourPause; // 0x2a
	private Boolean _invertPause; // 0x2b
	private static DelegateBridge __Hotfix0_get_pauseInsteadOfFinish; // 0x0
	private static DelegateBridge __Hotfix0_Update; // 0x8
	private static DelegateBridge __Hotfix0_SetPause; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	private Boolean pauseInsteadOfFinish { get; }

	// RVA: 0x1ffafb0 VA: 0x7594612fb0
	private Boolean get_pauseInsteadOfFinish() { }
	// RVA: 0x1ffb018 VA: 0x7594613018
	private Void Update() { }
	// RVA: 0x1ffb27c VA: 0x759461327c
	private Void SetPause(Boolean pause) { }
	// RVA: 0x1ffb32c VA: 0x759461332c
	public Void .ctor() { }
}
```