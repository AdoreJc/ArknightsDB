# AVGTimerView

**Namespace:** `Torappu.AVG`


## Fields

- `Text _message`

- `RectTransform _textTransform`

- `CanvasGroup _canvas`

- `CountDownTask m_countTimerTask`

- `Tweener m_timerTween`


## Methods

- `Void RenderTimer(Vector2, Vector2, Int32, Int64, Single, Single, Single)`

- `Void StopTimer(Single)`

- `Void Update()`

- `Void _StartCountTimer(Int64)`

- `Void _ShowTimer(Single, Single, Single)`

- `Void _TimerEnd()`

- `Void _TimerTick(TickValue)`

- `TickValue _OverrideTimerTaskTick(Context)`

- `Void <StopTimer>b__7_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.AVG
public class AVGTimerView : MonoBehaviour, IHotfixable
{
	private Text _message; // 0x18
	private RectTransform _textTransform; // 0x20
	private CanvasGroup _canvas; // 0x28
	private const Single DEFAULT_DURATION; // 0x0
	private CountDownTask m_countTimerTask; // 0x30
	private Tweener m_timerTween; // 0x38
	private static DelegateBridge __Hotfix0_RenderTimer; // 0x0
	private static DelegateBridge __Hotfix0_StopTimer; // 0x8
	private static DelegateBridge __Hotfix0_Update; // 0x10
	private static DelegateBridge __Hotfix0__StartCountTimer; // 0x18
	private static DelegateBridge __Hotfix0__ShowTimer; // 0x20
	private static DelegateBridge __Hotfix0__TimerEnd; // 0x28
	private static DelegateBridge __Hotfix0__TimerTick; // 0x30
	private static DelegateBridge __Hotfix0__OverrideTimerTaskTick; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x3eac2b0 VA: 0x75964c42b0
	public Void RenderTimer(Vector2 pos, Vector2 size, Int32 fontSize, Int64 totalTimeSec, Single aFrom, Single aTo, Single duration) { }
	// RVA: 0x3eac7d4 VA: 0x75964c47d4
	public Void StopTimer(Single duration) { }
	// RVA: 0x3eac8f0 VA: 0x75964c48f0
	private Void Update() { }
	// RVA: 0x3eac404 VA: 0x75964c4404
	private Void _StartCountTimer(Int64 totalTimeSec) { }
	// RVA: 0x3eac5f8 VA: 0x75964c45f8
	private Void _ShowTimer(Single aFrom, Single aTo, Single duration) { }
	// RVA: 0x3eacaec VA: 0x75964c4aec
	private Void _TimerEnd() { }
	// RVA: 0x3eac96c VA: 0x75964c496c
	private Void _TimerTick(TickValue tickValue) { }
	// RVA: 0x3eacb5c VA: 0x75964c4b5c
	private TickValue _OverrideTimerTaskTick(Context context) { }
	// RVA: 0x3eacc28 VA: 0x75964c4c28
	public Void .ctor() { }
	// RVA: 0x3eacc98 VA: 0x75964c4c98
	private Void <StopTimer>b__7_0() { }
}
```