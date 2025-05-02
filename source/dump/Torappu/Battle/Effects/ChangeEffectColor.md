# ChangeEffectColor

**Namespace:** `Torappu.Battle.Effects`


## Fields

- `Color _colorStart`

- `Color _colorEnd`

- `Boolean _restoreIfNotInSpecificModes`


## Methods

- `Void Update()`

- `Boolean _IsWorkMode()`

- `Void _UpdateColorBasedOnHpRatio()`

- `Void _SetColor(Color)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.Effects
public class ChangeEffectColor : Behaviour
{
	private Color _colorStart; // 0x20
	private Color _colorEnd; // 0x30
	private Boolean _restoreIfNotInSpecificModes; // 0x40
	private Int32[] modeIndex; // 0x48
	private static DelegateBridge __Hotfix0_Update; // 0x0
	private static DelegateBridge __Hotfix0__IsWorkMode; // 0x8
	private static DelegateBridge __Hotfix0__UpdateColorBasedOnHpRatio; // 0x10
	private static DelegateBridge __Hotfix0__SetColor; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x1ff91f0 VA: 0x75946111f0
	private Void Update() { }
	// RVA: 0x1ff9308 VA: 0x7594611308
	private Boolean _IsWorkMode() { }
	// RVA: 0x1ff9504 VA: 0x7594611504
	private Void _UpdateColorBasedOnHpRatio() { }
	// RVA: 0x1ff963c VA: 0x759461163c
	private Void _SetColor(Color color) { }
	// RVA: 0x1ff97d4 VA: 0x75946117d4
	public Void .ctor() { }
}
```