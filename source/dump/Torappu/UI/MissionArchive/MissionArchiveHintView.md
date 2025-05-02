# MissionArchiveHintView

**Namespace:** `Torappu.UI.MissionArchive`


## Fields

- `CanvasGroup _hintGroup`

- `Text _hintText`

- `Single _hintDuration`

- `Single _hintFadeDuration`

- `String m_cachedHint`

- `Tween m_hintTween`


## Methods

- `Void Reset()`

- `Void ShowHint(String)`

- `Void HideHint()`

- `Sequence _SequenceOfShowHint(String)`

- `Void <_SequenceOfShowHint>b__9_0()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.MissionArchive
public class MissionArchiveHintView : MonoBehaviour, IHotfixable
{
	private CanvasGroup _hintGroup; // 0x18
	private Text _hintText; // 0x20
	private Single _hintDuration; // 0x28
	private Single _hintFadeDuration; // 0x2c
	private String m_cachedHint; // 0x30
	private Tween m_hintTween; // 0x38
	private static DelegateBridge __Hotfix0_Reset; // 0x0
	private static DelegateBridge __Hotfix0_ShowHint; // 0x8
	private static DelegateBridge __Hotfix0_HideHint; // 0x10
	private static DelegateBridge __Hotfix0__SequenceOfShowHint; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2728bb0 VA: 0x7594d40bb0
	public Void Reset() { }
	// RVA: 0x272981c VA: 0x7594d4181c
	public Void ShowHint(String hint) { }
	// RVA: 0x27296c4 VA: 0x7594d416c4
	public Void HideHint() { }
	// RVA: 0x272b574 VA: 0x7594d43574
	private Sequence _SequenceOfShowHint(String hint) { }
	// RVA: 0x272b790 VA: 0x7594d43790
	public Void .ctor() { }
	// RVA: 0x272b800 VA: 0x7594d43800
	private Void <_SequenceOfShowHint>b__9_0() { }
}
```