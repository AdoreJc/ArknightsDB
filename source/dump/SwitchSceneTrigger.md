# SwitchSceneTrigger

**Namespace:** ` `


## Fields

- `Boolean m_isTweenFinished`

- `Boolean m_isLicenseGranted`

- `Action m_switchToScene`


## Methods

- `Void NotifyLicenseGranted()`

- `Void NotifyTweenFinshed()`

- `Void _TryTriggerSwitchScene()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class SwitchSceneTrigger
{
	private Boolean m_isTweenFinished; // 0x10
	private Boolean m_isLicenseGranted; // 0x11
	private Action m_switchToScene; // 0x18


	// RVA: 0x3107128 VA: 0x759571f128
	public Void .ctor(Action switchToScene) { }
	// RVA: 0x310721c VA: 0x759571f21c
	public Void NotifyLicenseGranted() { }
	// RVA: 0x3107240 VA: 0x759571f240
	public Void NotifyTweenFinshed() { }
	// RVA: 0x310777c VA: 0x759571f77c
	private Void _TryTriggerSwitchScene() { }
}
```