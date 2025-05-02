# UIFlashAlert

**Namespace:** `Torappu.UI`


## Fields

- `GameObject _canvas`

- `Text _resText`

- `Single _hideTime`

- `Single _lengthPerSec`

- `Single _widthBar`

- `Int32 m_loopTimes`

- `CanvasGroup _canvasGroup`

- `Sequence m_animSequence`

- `TextGenerator m_textGenerator`


## Methods

- `Boolean _CheckAbleToAlert()`

- `Void HandleFlashAlert(InputParam)`

- `Tweener _InstTweener(Single, Single)`

- `UISwitchTween GetSwitchTween()`

- `Void <_InstTweener>b__12_0(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIFlashAlert : NotifyView, IFloatNotifyView
{
	private GameObject _canvas; // 0x28
	private Text _resText; // 0x30
	private Single _hideTime; // 0x38
	private Single _lengthPerSec; // 0x3c
	private Single _widthBar; // 0x40
	private Int32 m_loopTimes; // 0x44
	private CanvasGroup _canvasGroup; // 0x48
	private Sequence m_animSequence; // 0x50
	private TextGenerator m_textGenerator; // 0x58
	private static DelegateBridge __Hotfix0__CheckAbleToAlert; // 0x0
	private static DelegateBridge __Hotfix0_HandleFlashAlert; // 0x8
	private static DelegateBridge __Hotfix0__InstTweener; // 0x10
	private static DelegateBridge __Hotfix0_TriggerRender; // 0x18
	private static DelegateBridge __Hotfix0_GetSwitchTween; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x2247fdc VA: 0x759485ffdc
	private Boolean _CheckAbleToAlert() { }
	// RVA: 0x2248070 VA: 0x7594860070
	public Void HandleFlashAlert(InputParam option) { }
	// RVA: 0x2248368 VA: 0x7594860368
	private Tweener _InstTweener(Single preferedWeight, Single duration) { }
	// RVA: 0x22484a4 VA: 0x75948604a4
	public override Void TriggerRender(NotifyViewParam rawParam) { }
	// RVA: 0x224857c VA: 0x759486057c
	public UISwitchTween GetSwitchTween() { }
	// RVA: 0x2248634 VA: 0x7594860634
	public Void .ctor() { }
	// RVA: 0x22486bc VA: 0x75948606bc
	private Void <_InstTweener>b__12_0(Single val) { }
}
```