# CharacterInfoHomePotentialView

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `Image _imagePotential`

- `Image _imagePlus`

- `Image _imageMax`

- `Text _symbolUnapplicable`

- `Transform _potentialTextContainer`

- `GameObject _downArrow`

- `GameObject _upArrow`

- `UICommonTrackPoint _potentialTrackPoint`

- `TrackPointViewProperty potentialTrackProp`

- `Boolean m_isInited`


## Methods

- `Void _InitIfNot()`

- `Void SetArrowTarget(Boolean)`

- `Void Render(CharViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoHomePotentialView : MonoBehaviour, IHotfixable
{
	private Image _imagePotential; // 0x18
	private Image _imagePlus; // 0x20
	private Image _imageMax; // 0x28
	private Text _symbolUnapplicable; // 0x30
	private Transform _potentialTextContainer; // 0x38
	private GameObject _downArrow; // 0x40
	private GameObject _upArrow; // 0x48
	private UICommonTrackPoint _potentialTrackPoint; // 0x50
	public TrackPointViewProperty potentialTrackProp; // 0x58
	private Boolean m_isInited; // 0x60
	private List`1 m_potentialText; // 0x68
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_SetArrowTarget; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2d7c62c VA: 0x759539462c
	private Void _InitIfNot() { }
	// RVA: 0x2d7c6d4 VA: 0x75953946d4
	public Void SetArrowTarget(Boolean isHide) { }
	// RVA: 0x2d7c76c VA: 0x759539476c
	public Void Render(CharViewModel charViewModel) { }
	// RVA: 0x2d7c900 VA: 0x7595394900
	public Void .ctor() { }
}
```