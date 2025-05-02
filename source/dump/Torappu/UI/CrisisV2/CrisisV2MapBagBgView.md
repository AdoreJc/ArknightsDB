# CrisisV2MapBagBgView

**Namespace:** `Torappu.UI.CrisisV2`


## Fields

- `UIAtlasImage _imgDimension`

- `UIAtlasObject _dimensionAtlas`

- `UIAnimationLocation _animSwitch`

- `GameObject _panelFocus`

- `UIStateFinder m_stateFinder`

- `AnimationSwitchTween m_switchTween`


## Methods

- `Void _SetPos(Vector2, Vector2)`

- `Void Init(Vector2, Vector2)`

- `Void Render(CrisisV2MapBagModel, Boolean, String)`

- `Void _RegisterTutorialGoIfNeed(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CrisisV2
public class CrisisV2MapBagBgView : MonoBehaviour, IHotfixable
{
	private UIAtlasImage _imgDimension; // 0x18
	private UIAtlasObject _dimensionAtlas; // 0x20
	private UIAnimationLocation _animSwitch; // 0x28
	private GameObject _panelFocus; // 0x38
	private UIStateFinder m_stateFinder; // 0x40
	private AnimationSwitchTween m_switchTween; // 0x50
	private static DelegateBridge __Hotfix0__SetPos; // 0x0
	private static DelegateBridge __Hotfix0_Init; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0__RegisterTutorialGoIfNeed; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2c01d28 VA: 0x7595219d28
	private Void _SetPos(Vector2 pos, Vector2 size) { }
	// RVA: 0x2c01dfc VA: 0x7595219dfc
	public Void Init(Vector2 bagPos, Vector2 bagSize) { }
	// RVA: 0x2c01f24 VA: 0x7595219f24
	public Void Render(CrisisV2MapBagModel bagModel, Boolean isVisible, String tutorialKey) { }
	// RVA: 0x2c02060 VA: 0x759521a060
	private Void _RegisterTutorialGoIfNeed(String key) { }
	// RVA: 0x2c0219c VA: 0x759521a19c
	public Void .ctor() { }
}
```