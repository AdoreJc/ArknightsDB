# ClimbTowerLayerCard

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Int32 _preferredSize`

- `Int32 _arrowOffset`

- `GameObject _pnlLayerPassed`

- `GameObject _pnlLayerNotPassed`

- `CanvasGroup _canvasNormal`

- `CanvasGroup _canvasSelected`

- `UIColorGraphic _colorGraphic`

- `GameObject _objNotPassedImg`

- `GameObject _objNotPassedHardImg`

- `GameObject _objPassedImg`

- `GameObject _objPassedHardImg`

- `GameObject _objSelectedImg`

- `GameObject _objSelectedHardImg`

- `Boolean _needDiffNormOrHardMode`

- `Boolean m_inited`

- `UISwitchTween m_selectedSwitchTween`


## Properties

- `UIColorGraphic colorGraphic`


## Methods

- `UIColorGraphic get_colorGraphic()`

- `Void _InitIfNot()`

- `Int32 GetPreferredSize()`

- `Int32 GetArrowOffset()`

- `Void Render(ClimbTowerLevelModel, String, Boolean, Boolean, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerLayerCard : MonoBehaviour, IHotfixable
{
	private const Single SELECT_SWITH_TWEEN_DURATION; // 0x0
	private Int32 _preferredSize; // 0x18
	private Int32 _arrowOffset; // 0x1c
	private GameObject _pnlLayerPassed; // 0x20
	private GameObject _pnlLayerNotPassed; // 0x28
	private CanvasGroup _canvasNormal; // 0x30
	private CanvasGroup _canvasSelected; // 0x38
	private UIColorGraphic _colorGraphic; // 0x40
	private GameObject _objNotPassedImg; // 0x48
	private GameObject _objNotPassedHardImg; // 0x50
	private GameObject _objPassedImg; // 0x58
	private GameObject _objPassedHardImg; // 0x60
	private GameObject _objSelectedImg; // 0x68
	private GameObject _objSelectedHardImg; // 0x70
	private Boolean _needDiffNormOrHardMode; // 0x78
	private Boolean m_inited; // 0x79
	private UISwitchTween m_selectedSwitchTween; // 0x80
	private static DelegateBridge __Hotfix0_get_colorGraphic; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_GetPreferredSize; // 0x10
	private static DelegateBridge __Hotfix0_GetArrowOffset; // 0x18
	private static DelegateBridge __Hotfix0_Render; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public UIColorGraphic colorGraphic { get; }

	// RVA: 0x2c72c08 VA: 0x759528ac08
	public UIColorGraphic get_colorGraphic() { }
	// RVA: 0x2c72c70 VA: 0x759528ac70
	private Void _InitIfNot() { }
	// RVA: 0x2c72dd4 VA: 0x759528add4
	public Int32 GetPreferredSize() { }
	// RVA: 0x2c72e3c VA: 0x759528ae3c
	public Int32 GetArrowOffset() { }
	// RVA: 0x2c72ea4 VA: 0x759528aea4
	public Void Render(ClimbTowerLevelModel model, String selectedItem, Boolean isPassed, Boolean fastMode, Boolean isHardMode) { }
	// RVA: 0x2c73050 VA: 0x759528b050
	public Void .ctor() { }
}
```