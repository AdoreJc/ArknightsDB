# DisplayFeatureSwitch

**Namespace:** ` `


## Fields

- `OverallDisplayFeature feature`

- `CanvasGroup unselectedGroup`

- `CanvasGroup selectedGroup`

- `FadeSwitchTween m_unselectedTween`

- `FadeSwitchTween m_selectedTween`


## Methods

- `Void SetSelected(OverallDisplayFeature, Boolean)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
public class DisplayFeatureSwitch : IHotfixable
{
	public OverallDisplayFeature feature; // 0x10
	public CanvasGroup unselectedGroup; // 0x18
	public CanvasGroup selectedGroup; // 0x20
	private FadeSwitchTween m_unselectedTween; // 0x28
	private FadeSwitchTween m_selectedTween; // 0x30
	private static DelegateBridge __Hotfix0_SetSelected; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2ffcd74 VA: 0x7595614d74
	public Void SetSelected(OverallDisplayFeature current, Boolean fastMode) { }
	// RVA: 0x2ffe7d4 VA: 0x75956167d4
	private Void _InitIfNot() { }
	// RVA: 0x2ffe8ec VA: 0x75956168ec
	public Void .ctor() { }
}
```