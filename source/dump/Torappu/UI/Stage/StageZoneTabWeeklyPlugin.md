# StageZoneTabWeeklyPlugin

**Namespace:** `Torappu.UI.Stage`


## Fields

- `Sprite _activeForceOpenIcon`

- `Sprite _unactiveForceOpenIcon`

- `Image _iconImg`

- `Image _commonIconImg`

- `Tweener m_cacheTweenerIcon`

- `Tweener m_cacheTweenerCommon`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Stage
public class StageZoneTabWeeklyPlugin : IPlugin
{
	private Sprite _activeForceOpenIcon; // 0x18
	private Sprite _unactiveForceOpenIcon; // 0x20
	private Image _iconImg; // 0x28
	private Image _commonIconImg; // 0x30
	private const Single FIX_DURATION; // 0x0
	private Tweener m_cacheTweenerIcon; // 0x38
	private Tweener m_cacheTweenerCommon; // 0x40
	private const String BLACK_UNSELECT; // 0x0
	private const String BLACK_SELECT; // 0x0
	private const String WHITE_UNSELECT; // 0x0


	// RVA: 0x2fbf390 VA: 0x75955d7390
	public override Void RefreshTargetImg(StageZoneTabViewModel viewModel, Boolean isBlack, ref Image pic, out Boolean needFadeColor) { }
	// RVA: 0x2fbf5a4 VA: 0x75955d75a4
	public Void .ctor() { }
}
```