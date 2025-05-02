# TemplateMissionCommonEntryFadeTween

**Namespace:** `Torappu.UI.TemplateMission`


## Fields

- `Single _fadeInDur`

- `Ease _easeType`

- `Single _delay`

- `CanvasGroup _canvasGroup`


## Properties

- `Single entryDelay`

- `Tween entryTween`


## Methods

- `Single get_entryDelay()`

- `Tween get_entryTween()`

- `Void ResetTween()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateMission
public class TemplateMissionCommonEntryFadeTween : MonoBehaviour, ITemplateMissionEntryTween, IHotfixable
{
	private Single _fadeInDur; // 0x18
	private Ease _easeType; // 0x1c
	private Single _delay; // 0x20
	private CanvasGroup _canvasGroup; // 0x28
	private static DelegateBridge __Hotfix0_get_entryDelay; // 0x0
	private static DelegateBridge __Hotfix0_get_entryTween; // 0x8
	private static DelegateBridge __Hotfix0_ResetTween; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Single entryDelay { get; }
	public Tween entryTween { get; }

	// RVA: 0x236b480 VA: 0x7594983480
	public Single get_entryDelay() { }
	// RVA: 0x236b4e8 VA: 0x75949834e8
	public Tween get_entryTween() { }
	// RVA: 0x236b57c VA: 0x759498357c
	public Void ResetTween() { }
	// RVA: 0x236b5f4 VA: 0x75949835f4
	public Void .ctor() { }
}
```