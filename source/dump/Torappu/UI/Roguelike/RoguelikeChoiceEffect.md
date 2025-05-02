# RoguelikeChoiceEffect

**Namespace:** `Torappu.UI.Roguelike`


## Fields

- `Image _choiceStaticBg`

- `Image _choiceBlackBg`

- `Single _choiceBlackBgAlpha`

- `GameObject _choiceParticleGo`

- `GameObject _choiceEffectGo`

- `Boolean m_isActive`


## Methods

- `IEnumerator _SceneHideTween()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike
public class RoguelikeChoiceEffect : RoguelikeChoiceEffectBase, IHotfixable
{
	private const Int32 FADEIN_FRAME; // 0x0
	private Image _choiceStaticBg; // 0x28
	private Image _choiceBlackBg; // 0x30
	private Single _choiceBlackBgAlpha; // 0x38
	private GameObject _choiceParticleGo; // 0x40
	private GameObject _choiceEffectGo; // 0x48
	private Boolean m_isActive; // 0x50
	private static DelegateBridge __Hotfix0__SceneHideTween; // 0x0
	private static DelegateBridge __Hotfix0_SetChoiceBgEffectVisible; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x29ea66c VA: 0x759500266c
	private IEnumerator _SceneHideTween() { }
	// RVA: 0x29ea740 VA: 0x7595002740
	public override Void SetChoiceBgEffectVisible(Boolean isActive, String assetName) { }
	// RVA: 0x29ea96c VA: 0x759500296c
	public Void .ctor() { }
}
```