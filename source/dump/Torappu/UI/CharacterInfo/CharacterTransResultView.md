# CharacterTransResultView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Transform _illustContainer`

- `Transform _illustColorContainer`

- `GameObject _hintPanel`

- `Image _yesImage`

- `Material _pureColorMat`

- `Graphic _hotspotImage`

- `GameObject _background0`

- `GameObject _background1`

- `Image _whiteCover`

- `GameObject _extraIconParticleSystem`

- `UICharacterIllust m_illustInst`

- `UICharacterIllust m_illustColorInst`

- `TransMark m_curTransMark`

- `Coroutine m_effectMotionCoroutine`

- `Action m_endCB`

- `CanvasGroup m_hintCanvasGroup`

- `Material m_illustNewMaterial`

- `Vector2 m_hintOriginPos`


## Methods

- `Void Awake()`

- `Void Setup(CharUISkinStruct, Int32, Action)`

- `Void _SetupIllustColorInst(UICharacterIllustLoader, CharUISkinStruct)`

- `Void StartMotion()`

- `Void OnBGPressed()`

- `Void OnDestroy()`

- `Void ShowExtraEffect(Boolean)`

- `IEnumerator _EffectMotion()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterTransResultView : MonoBehaviour, IHotfixable
{
	private Transform _illustContainer; // 0x18
	private Transform _illustColorContainer; // 0x20
	private TransMark[] _transMarks; // 0x28
	private GameObject _hintPanel; // 0x30
	private Image _yesImage; // 0x38
	private Material _pureColorMat; // 0x40
	private Graphic _hotspotImage; // 0x48
	private GameObject _background0; // 0x50
	private GameObject _background1; // 0x58
	private Image _whiteCover; // 0x60
	private GameObject _extraIconParticleSystem; // 0x68
	private UICharacterIllust m_illustInst; // 0x70
	private UICharacterIllust m_illustColorInst; // 0x78
	private TransMark m_curTransMark; // 0x80
	private Coroutine m_effectMotionCoroutine; // 0x88
	private Action m_endCB; // 0x90
	private CanvasGroup m_hintCanvasGroup; // 0x98
	private Material m_illustNewMaterial; // 0xa0
	private Vector2 m_hintOriginPos; // 0xa8
	private static DelegateBridge __Hotfix0_Awake; // 0x0
	private static DelegateBridge __Hotfix0_Setup; // 0x8
	private static DelegateBridge __Hotfix0__SetupIllustColorInst; // 0x10
	private static DelegateBridge __Hotfix0__IsAlphaSplitMaterial; // 0x18
	private static DelegateBridge __Hotfix0_StartMotion; // 0x20
	private static DelegateBridge __Hotfix0_OnBGPressed; // 0x28
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x30
	private static DelegateBridge __Hotfix0_ShowExtraEffect; // 0x38
	private static DelegateBridge __Hotfix0__EffectMotion; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x2d6aec0 VA: 0x7595382ec0
	private Void Awake() { }
	// RVA: 0x2d6af70 VA: 0x7595382f70
	public Void Setup(CharUISkinStruct illustSkin, Int32 transIndex, Action endCB) { }
	// RVA: 0x2d6b310 VA: 0x7595383310
	private Void _SetupIllustColorInst(UICharacterIllustLoader illustLoader, CharUISkinStruct illustSkin) { }
	// RVA: 0x2d6b660 VA: 0x7595383660
	private static Boolean _IsAlphaSplitMaterial(Material mat) { }
	// RVA: 0x2d6b748 VA: 0x7595383748
	public Void StartMotion() { }
	// RVA: 0x2d6b894 VA: 0x7595383894
	public Void OnBGPressed() { }
	// RVA: 0x2d6b920 VA: 0x7595383920
	private Void OnDestroy() { }
	// RVA: 0x2d6b9e8 VA: 0x75953839e8
	public Void ShowExtraEffect(Boolean show) { }
	// RVA: 0x2d6b7e8 VA: 0x75953837e8
	private IEnumerator _EffectMotion() { }
	// RVA: 0x2d6ba94 VA: 0x7595383a94
	public Void .ctor() { }
}
```