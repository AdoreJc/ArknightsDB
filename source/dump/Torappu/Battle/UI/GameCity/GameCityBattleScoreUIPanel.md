# GameCityBattleScoreUIPanel

**Namespace:** `Torappu.Battle.UI.GameCity`


## Fields

- `AnimationWrapper _animationWrapper`

- `Text _normalScore`

- `Text _shadowScore`

- `Text _rainbowScore`

- `RectTransform _normalFX`

- `RectTransform _rainbowFX`


## Methods

- `Void OnPanelShownScore(Int32, Boolean)`

- `Void PlayForOnce()`

- `Void PlayOutAnim()`

- `Void PlayDoubleAnim()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI.GameCity
public class GameCityBattleScoreUIPanel : MonoBehaviour, IHotfixable
{
	private const String SHOW_ANIM_IN_KEY; // 0x0
	private const String SHOW_ANIM_DOUBLE_KEY; // 0x0
	private const String SHOW_ANIM_OUT_KEY; // 0x0
	private AnimationWrapper _animationWrapper; // 0x18
	private Text _normalScore; // 0x20
	private Text _shadowScore; // 0x28
	private Text _rainbowScore; // 0x30
	private RectTransform _normalFX; // 0x38
	private RectTransform _rainbowFX; // 0x40
	private static DelegateBridge __Hotfix0_OnPanelShownScore; // 0x0
	private static DelegateBridge __Hotfix0_PlayForOnce; // 0x8
	private static DelegateBridge __Hotfix0_PlayOutAnim; // 0x10
	private static DelegateBridge __Hotfix0_PlayDoubleAnim; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x20f7394 VA: 0x759470f394
	public Void OnPanelShownScore(Int32 score, Boolean isRainbow) { }
	// RVA: 0x20f750c VA: 0x759470f50c
	public Void PlayForOnce() { }
	// RVA: 0x20f7648 VA: 0x759470f648
	private Void PlayOutAnim() { }
	// RVA: 0x20f7718 VA: 0x759470f718
	public Void PlayDoubleAnim() { }
	// RVA: 0x20f77fc VA: 0x759470f7fc
	public Void .ctor() { }
}
```