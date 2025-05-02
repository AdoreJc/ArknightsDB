# CharmExchangeBar

**Namespace:** `Torappu.Activity.Act12side.UI`


## Fields

- `Image _icon`

- `Sprite _iconNormal`

- `Sprite _iconGradient`

- `Image _prgPic`

- `Image _nextPrgPic`

- `Text _num`

- `GameObject _prgDetail`

- `Text _curNum`

- `Text _targetNum`

- `UIEffectHelper _effect`

- `AnimationWrapper _animWrapper`


## Methods

- `Void UpdateProgress(Int32, Int32)`

- `IEnumerator UpdateProgressToNext(Int32, Int32)`

- `Void UpdateNextPrg(Int32, Int32)`

- `Void SetShowPrgDetail(Boolean)`

- `Void StopBlink()`

- `Void FadeInDetail()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act12side.UI
public class CharmExchangeBar : MonoBehaviour, IHotfixable
{
	private Image _icon; // 0x18
	private Sprite _iconNormal; // 0x20
	private Sprite _iconGradient; // 0x28
	private Image _prgPic; // 0x30
	private Image _nextPrgPic; // 0x38
	private Text _num; // 0x40
	private GameObject _prgDetail; // 0x48
	private Text _curNum; // 0x50
	private Text _targetNum; // 0x58
	private UIEffectHelper _effect; // 0x60
	private AnimationWrapper _animWrapper; // 0x68
	private const String ANIM_BLINK_ANIM_NAME; // 0x0
	private const String ANIM_DETAIL_FADEIN; // 0x0
	private static DelegateBridge __Hotfix0_UpdateProgress; // 0x0
	private static DelegateBridge __Hotfix0_UpdateProgressToNext; // 0x8
	private static DelegateBridge __Hotfix0_UpdateNextPrg; // 0x10
	private static DelegateBridge __Hotfix0_SetShowPrgDetail; // 0x18
	private static DelegateBridge __Hotfix0_StopBlink; // 0x20
	private static DelegateBridge __Hotfix0_FadeInDetail; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x34517f4 VA: 0x7595a697f4
	public Void UpdateProgress(Int32 cur, Int32 target) { }
	// RVA: 0x3451900 VA: 0x7595a69900
	public IEnumerator UpdateProgressToNext(Int32 next, Int32 target) { }
	// RVA: 0x34519f4 VA: 0x7595a699f4
	public Void UpdateNextPrg(Int32 next, Int32 target) { }
	// RVA: 0x3451b60 VA: 0x7595a69b60
	public Void SetShowPrgDetail(Boolean v) { }
	// RVA: 0x3451c7c VA: 0x7595a69c7c
	public Void StopBlink() { }
	// RVA: 0x3451d0c VA: 0x7595a69d0c
	public Void FadeInDetail() { }
	// RVA: 0x3451d98 VA: 0x7595a69d98
	public Void .ctor() { }
}
```