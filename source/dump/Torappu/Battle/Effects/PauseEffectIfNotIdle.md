# PauseEffectIfNotIdle

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `Boolean _needCheckFaceSwitch`

- `Boolean _pauseWhenBack`

- `Boolean _pauseWhenFront`


## Properties

- `Boolean needCheckFaceSwitch`


## Methods

- `Boolean get_needCheckFaceSwitch()`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class PauseEffectIfNotIdle : Behaviour, IHotfixable
{
	private Boolean _needCheckFaceSwitch; // 0x20
	private Boolean _pauseWhenBack; // 0x21
	private Boolean _pauseWhenFront; // 0x22
	private static DelegateBridge __Hotfix0_get_needCheckFaceSwitch; // 0x0
	private static DelegateBridge __Hotfix0_Update; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Boolean needCheckFaceSwitch { get; }

	// RVA: 0x2005370 VA: 0x759461d370
	public Boolean get_needCheckFaceSwitch() { }
	// RVA: 0x20053d8 VA: 0x759461d3d8
	private Void Update() { }
	// RVA: 0x2005584 VA: 0x759461d584
	public Void .ctor() { }
}
```