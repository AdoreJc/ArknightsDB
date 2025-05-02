# StretchProgressBar

**Namespace:** `Torappu.UI`


## Fields

- `RectTransform _emptyBar`

- `RectTransform _stretchBar`

- `RectTransform _fullBar`

- `Single m_progress`


## Properties

- `Single progress`


## Methods

- `Void Start()`

- `Single get_progress()`

- `Void set_progress(Single)`

- `Void _UpdateProgress()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class StretchProgressBar : MonoBehaviour, IHotfixable
{
	private const Single FULL_THRESHOLD; // 0x0
	private const Single EMPTY_THRESHOLD; // 0x0
	private RectTransform _emptyBar; // 0x18
	private RectTransform _stretchBar; // 0x20
	private RectTransform _fullBar; // 0x28
	private Single m_progress; // 0x30
	private static DelegateBridge __Hotfix0_Start; // 0x0
	private static DelegateBridge __Hotfix0_get_progress; // 0x8
	private static DelegateBridge __Hotfix0_set_progress; // 0x10
	private static DelegateBridge __Hotfix0__UpdateProgress; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Single progress { get; set; }

	// RVA: 0x223fcd0 VA: 0x7594857cd0
	private Void Start() { }
	// RVA: 0x223fee8 VA: 0x7594857ee8
	public Single get_progress() { }
	// RVA: 0x223ff50 VA: 0x7594857f50
	public Void set_progress(Single value) { }
	// RVA: 0x223fd38 VA: 0x7594857d38
	private Void _UpdateProgress() { }
	// RVA: 0x223ffe4 VA: 0x7594857fe4
	public Void .ctor() { }
}
```