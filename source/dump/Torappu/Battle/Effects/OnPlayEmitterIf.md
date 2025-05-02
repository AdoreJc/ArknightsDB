# OnPlayEmitterIf

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `CheckType _checkType`

- `MotionMode _motionMode`

- `String _buffKey`


## Properties

- `Boolean _showMotionMode`

- `Boolean _showBuffKey`


## Methods

- `Boolean get__showMotionMode()`

- `Boolean get__showBuffKey()`

- `Void <>xLuaBaseProxy_OnPlay()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class OnPlayEmitterIf : OnPlayEmitter
{
	private CheckType _checkType; // 0x40
	private MotionMode _motionMode; // 0x44
	private String _buffKey; // 0x48
	private static DelegateBridge __Hotfix0_get__showMotionMode; // 0x0
	private static DelegateBridge __Hotfix0_get__showBuffKey; // 0x8
	private static DelegateBridge __Hotfix0_OnPlay; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	private Boolean _showMotionMode { get; }
	private Boolean _showBuffKey { get; }

	// RVA: 0x20030b0 VA: 0x759461b0b0
	private Boolean get__showMotionMode() { }
	// RVA: 0x200311c VA: 0x759461b11c
	private Boolean get__showBuffKey() { }
	// RVA: 0x2003188 VA: 0x759461b188
	public override Void OnPlay() { }
	// RVA: 0x2003314 VA: 0x759461b314
	public Void .ctor() { }
	// RVA: 0x20033c0 VA: 0x759461b3c0
	private Void <>xLuaBaseProxy_OnPlay() { }
}
```