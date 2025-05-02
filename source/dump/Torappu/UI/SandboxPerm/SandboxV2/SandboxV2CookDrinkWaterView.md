# SandboxV2CookDrinkWaterView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Single _animDuration`

- `Ease _ease`

- `Vector2 _sizeBegin`

- `Vector2 _sizeEnd`

- `RectTransform _rectWater`

- `Image _reflectionFill`

- `Slider _floatingTagSlider`

- `Text _floatingTagText`

- `Single m_value`

- `Tween m_tween`


## Methods

- `Void Render(SandboxV2CookDrinkModel)`

- `Void _SetTargetValue(Single)`

- `Single <Render>b__12_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2CookDrinkWaterView : MonoBehaviour, IHotfixable
{
	private const String STATUS_TEXT_FORMAT; // 0x0
	private const Single POT_WATER_LIMIT; // 0x0
	private Single _animDuration; // 0x18
	private Ease _ease; // 0x1c
	private Vector2 _sizeBegin; // 0x20
	private Vector2 _sizeEnd; // 0x28
	private RectTransform _rectWater; // 0x30
	private Image _reflectionFill; // 0x38
	private Slider _floatingTagSlider; // 0x40
	private Text _floatingTagText; // 0x48
	private Single m_value; // 0x50
	private Tween m_tween; // 0x58
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__SetTargetValue; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x24c5ae0 VA: 0x7594addae0
	public Void Render(SandboxV2CookDrinkModel model) { }
	// RVA: 0x24c7690 VA: 0x7594adf690
	private Void _SetTargetValue(Single target) { }
	// RVA: 0x24c77dc VA: 0x7594adf7dc
	public Void .ctor() { }
	// RVA: 0x24c7868 VA: 0x7594adf868
	private Single <Render>b__12_0() { }
}
```