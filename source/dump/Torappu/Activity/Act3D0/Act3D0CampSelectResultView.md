# Act3D0CampSelectResultView

**Namespace:** `Torappu.Activity.Act3D0`


## Fields

- `UIColorGraphic _colorTheme`

- `Image _imgCampLeft`

- `Image _imgBox`

- `Image _imgBoxShadow`

- `Text _textCampName`

- `UIAnimationLocation _effectAnim`

- `Boolean m_isEffectStart`

- `Boolean m_isEffectFinish`

- `Action onResultConfirmed`


## Methods

- `Void Start()`

- `IEnumerator StartEffectCoroutine()`

- `Void _RenderContent(String)`

- `Void _LoadCampRes(String)`

- `Void EventOnConfirmClicked()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act3D0
public class Act3D0CampSelectResultView : MonoBehaviour, IHotfixable
{
	private UIColorGraphic _colorTheme; // 0x18
	private CampColor[] _campColors; // 0x20
	private CampGameObject[] _campNameImgs; // 0x28
	private Image _imgCampLeft; // 0x30
	private Image _imgBox; // 0x38
	private Image _imgBoxShadow; // 0x40
	private Text _textCampName; // 0x48
	private UIAnimationLocation _effectAnim; // 0x50
	private Boolean m_isEffectStart; // 0x60
	private Boolean m_isEffectFinish; // 0x61
	public Action onResultConfirmed; // 0x68
	private static DelegateBridge __Hotfix0_Start; // 0x0
	private static DelegateBridge __Hotfix0_StartEffectCoroutine; // 0x8
	private static DelegateBridge __Hotfix0__RenderContent; // 0x10
	private static DelegateBridge __Hotfix0__LoadCampRes; // 0x18
	private static DelegateBridge __Hotfix0_EventOnConfirmClicked; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x32372a8 VA: 0x759584f2a8
	private Void Start() { }
	// RVA: 0x323733c VA: 0x759584f33c
	public IEnumerator StartEffectCoroutine() { }
	// RVA: 0x3237410 VA: 0x759584f410
	private Void _RenderContent(String campId) { }
	// RVA: 0x3237624 VA: 0x759584f624
	private Void _LoadCampRes(String campId) { }
	// RVA: 0x32378e8 VA: 0x759584f8e8
	public Void EventOnConfirmClicked() { }
	// RVA: 0x3237974 VA: 0x759584f974
	public Void .ctor() { }
}
```