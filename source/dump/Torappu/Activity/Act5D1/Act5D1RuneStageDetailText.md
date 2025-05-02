# Act5D1RuneStageDetailText

**Namespace:** `Torappu.Activity.Act5D1`


## Fields

- `Text _detailText`

- `CanvasGroup _alphaHandler`

- `Boolean m_isInited`

- `Status m_status`

- `Tween m_tween`

- `Boolean m_hasInterruptedTween`


## Methods

- `Void OnDestroy()`

- `Void RenderInfo(RuneInfo)`

- `Boolean _ResetTween()`

- `Void _TransitionFirst()`

- `Void _TransitionSecond(Single)`

- `Boolean _RenderStatus()`

- `Boolean _ValidateComps()`

- `Void <_TransitionFirst>b__11_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act5D1
public class Act5D1RuneStageDetailText : MonoBehaviour, IHotfixable
{
	private const Single FADE_DUR; // 0x0
	private Text _detailText; // 0x18
	private CanvasGroup _alphaHandler; // 0x20
	private Boolean m_isInited; // 0x28
	private Status m_status; // 0x30
	private Tween m_tween; // 0x40
	private Boolean m_hasInterruptedTween; // 0x48
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x0
	private static DelegateBridge __Hotfix0_RenderInfo; // 0x8
	private static DelegateBridge __Hotfix0__ResetTween; // 0x10
	private static DelegateBridge __Hotfix0__TransitionFirst; // 0x18
	private static DelegateBridge __Hotfix0__TransitionSecond; // 0x20
	private static DelegateBridge __Hotfix0__RenderStatus; // 0x28
	private static DelegateBridge __Hotfix0__ValidateComps; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38


	// RVA: 0x31cbc8c VA: 0x75957e3c8c
	private Void OnDestroy() { }
	// RVA: 0x31cbb48 VA: 0x75957e3b48
	public Void RenderInfo(RuneInfo runeInfo) { }
	// RVA: 0x31cbcf4 VA: 0x75957e3cf4
	private Boolean _ResetTween() { }
	// RVA: 0x31cbe3c VA: 0x75957e3e3c
	private Void _TransitionFirst() { }
	// RVA: 0x31cbf8c VA: 0x75957e3f8c
	private Void _TransitionSecond(Single delay) { }
	// RVA: 0x31cc1ac VA: 0x75957e41ac
	private Boolean _RenderStatus() { }
	// RVA: 0x31cc0dc VA: 0x75957e40dc
	private Boolean _ValidateComps() { }
	// RVA: 0x31cc3a4 VA: 0x75957e43a4
	public Void .ctor() { }
	// RVA: 0x31cc454 VA: 0x75957e4454
	private Void <_TransitionFirst>b__11_0() { }
}
```