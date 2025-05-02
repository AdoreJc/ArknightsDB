# Act13sideMissionStateBtn

**Namespace:** `Torappu.Activity.Act13Side`


## Fields

- `GameObject _btnActive`

- `CanvasGroup _canvasGroup`

- `Transform _moveTrans`

- `Int32 _direction`

- `GameObject _hideObj`

- `Single m_cacheVal`

- `Boolean m_isInited`

- `Tween m_tween`

- `Vector2 m_cachePos`


## Methods

- `Void HandleActive(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act13Side
public class Act13sideMissionStateBtn : MonoBehaviour, IHotfixable
{
	private GameObject _btnActive; // 0x18
	private CanvasGroup _canvasGroup; // 0x20
	private Transform _moveTrans; // 0x28
	private Int32 _direction; // 0x30
	private GameObject _hideObj; // 0x38
	private const Single TWEEN_DURATION; // 0x0
	private const Single DELTA_POS; // 0x0
	private Single m_cacheVal; // 0x40
	private Boolean m_isInited; // 0x44
	private Tween m_tween; // 0x48
	private Vector2 m_cachePos; // 0x50
	private static DelegateBridge __Hotfix0_HandleActive; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x3442ce8 VA: 0x7595a5ace8
	public Void HandleActive(Boolean active) { }
	// RVA: 0x3442fec VA: 0x7595a5afec
	public Void .ctor() { }
}
```