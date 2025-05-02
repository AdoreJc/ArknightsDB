# TuningProductSlotFormEffectView

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `CanvasGroup _effectGroup`

- `GameObject _effectPrefab`

- `Transform _content`

- `Single _effectShowAlpha`

- `Single _effectHideAlpha`

- `Single _effectTweenDuration`

- `FormEffectSwitchTween m_formEffectSwitchTween`

- `GameObject m_effectObj`

- `Boolean m_isInited`


## Methods

- `Void Render(Boolean)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningProductSlotFormEffectView : MonoBehaviour, IHotfixable
{
	private CanvasGroup _effectGroup; // 0x18
	private GameObject _effectPrefab; // 0x20
	private Transform _content; // 0x28
	private Single _effectShowAlpha; // 0x30
	private Single _effectHideAlpha; // 0x34
	private Single _effectTweenDuration; // 0x38
	private FormEffectSwitchTween m_formEffectSwitchTween; // 0x40
	private GameObject m_effectObj; // 0x48
	private Boolean m_isInited; // 0x50
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2332420 VA: 0x759494a420
	public Void Render(Boolean isShow) { }
	// RVA: 0x2337104 VA: 0x759494f104
	private Void _InitIfNot() { }
	// RVA: 0x2337268 VA: 0x759494f268
	public Void .ctor() { }
}
```