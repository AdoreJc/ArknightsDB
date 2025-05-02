# WorkshopMotionEffect

**Namespace:** `Torappu.Building.UI.Workshop`


## Fields

- `Single _barTime`

- `Single _circleTime`

- `Image _progressCircle`

- `Image _subBar1`

- `Image _subBar2`

- `Image _subBar3`

- `AnimationCurve _barAnimationCurve`

- `Int32 _maxCircleCount`

- `Single _recoverDuration`

- `Coroutine m_coroutine`

- `Boolean m_shouldBreak`


## Methods

- `IEnumerator _MakeEffectCoroutine(Boolean, Boolean, Boolean, Int32, Action`1, Action)`

- `IEnumerator _RecoverCoroutine(Single)`

- `Void ResetMakeEffect()`

- `Void PerformMakeEffect(Boolean, Boolean, Boolean, Int32, Action`1, Action)`

- `Void PerformRecoverEffect()`

- `Void StopMakeEffect()`

- `Void OnDestroy()`

- `Void _PlayStartIndustSe()`

- `Void _PlayIndustCircleSingleSe()`

- `Void _PlayIndustCircleMultiSe()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.UI.Workshop
public class WorkshopMotionEffect : MonoBehaviour
{
	private Single _barTime; // 0x18
	private Single _circleTime; // 0x1c
	private Image _progressCircle; // 0x20
	private Image _subBar1; // 0x28
	private Image _subBar2; // 0x30
	private Image _subBar3; // 0x38
	private AnimationCurve _barAnimationCurve; // 0x40
	private Int32 _maxCircleCount; // 0x48
	private Single _recoverDuration; // 0x4c
	private Coroutine m_coroutine; // 0x50
	private Boolean m_shouldBreak; // 0x58


	// RVA: 0x3d73b2c VA: 0x759638bb2c
	private IEnumerator _MakeEffectCoroutine(Boolean ingredient1Play, Boolean ingredient2Play, Boolean ingredient3Play, Int32 workCount, Action`1 circleHandler, Action endHandler) { }
	// RVA: 0x3d73c34 VA: 0x759638bc34
	private IEnumerator _RecoverCoroutine(Single duration) { }
	// RVA: 0x3d69f78 VA: 0x7596381f78
	public Void ResetMakeEffect() { }
	// RVA: 0x3d7271c VA: 0x759638a71c
	public Void PerformMakeEffect(Boolean ingredient1Play, Boolean ingredient2Play, Boolean ingredient3Play, Int32 workCount, Action`1 circleHandler, Action endHandler) { }
	// RVA: 0x3d73094 VA: 0x759638b094
	public Void PerformRecoverEffect() { }
	// RVA: 0x3d73cb8 VA: 0x759638bcb8
	public Void StopMakeEffect() { }
	// RVA: 0x3d73d04 VA: 0x759638bd04
	private Void OnDestroy() { }
	// RVA: 0x3d73d4c VA: 0x759638bd4c
	private Void _PlayStartIndustSe() { }
	// RVA: 0x3d73db8 VA: 0x759638bdb8
	private Void _PlayIndustCircleSingleSe() { }
	// RVA: 0x3d73e24 VA: 0x759638be24
	private Void _PlayIndustCircleMultiSe() { }
	// RVA: 0x3d73e90 VA: 0x759638be90
	public Void .ctor() { }
}
```