# UIAutoChangeScaleImage

**Namespace:** `Torappu.UI`


## Fields

- `Image _autoChangeScale`

- `Single _minValue`

- `Single _maxValue`

- `Boolean _isHorizon`

- `Single _initValue`


## Methods

- `Void ToInitScale()`

- `Void OnValueChanged(Vector2)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIAutoChangeScaleImage : MonoBehaviour, IHotfixable
{
	private Image _autoChangeScale; // 0x18
	private Single _minValue; // 0x20
	private Single _maxValue; // 0x24
	private Boolean _isHorizon; // 0x28
	private Single _initValue; // 0x2c
	private static DelegateBridge __Hotfix0_ToInitScale; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2241354 VA: 0x7594859354
	public Void ToInitScale() { }
	// RVA: 0x22413f0 VA: 0x75948593f0
	public Void OnValueChanged(Vector2 value) { }
	// RVA: 0x22414bc VA: 0x75948594bc
	public Void .ctor() { }
}
```